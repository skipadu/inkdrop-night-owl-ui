# Night Owl'ish UI Theme for Inkdrop

Inkdrop's UI elements are styled based on [Semantic UI](http://semantic-ui.com/).
It's mostly common in customizing the theme with it, so [their documentation](http://learnsemantic.com/) is very helpful to get started.

Read [the documentation](http://doc.inkdrop.info/manual/creating-a-theme) for detailed instructions.

## Use Node v10

Since Semantic UI is no longer maintained, you have to use Node 10 or you will get errors on installing it.
You also need to install `gulp-cli`and `gulp` as a local devDependency.

## How to build

```
npm install
gulp build
```

## Which files to edit

- `src/site/globals/site.variables`
  - Variables for Inkdrop-specific components
- `src/site/globals/site.overrides`
  - Declarations of CSS variables
- `src/themes/default/globals/site.variables`
  - Common variables
- `src/colors.less`
  - Night Owl color variables