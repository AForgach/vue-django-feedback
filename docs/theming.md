# Theming

### LESS files
> Instead of the standard pre-processed css it is possible to import the less files and refine your style trough the variables

```html
<style lang="less">
  @import "~vue-django-feedback/dist/styles/main.less";
  @import "~vue-django-feedback/dist/styles/variables.less";
</style>

```

### Variables

```less
// --------------------------------------------------
// Scaffolding
// --------------------------------------------------

@vdf-width:             400px;
@vdf-padding:           40px;
@vdf-button-size:       56px;
@vdf-offset:            calc(@vdf-width + @vdf-button-size);
@vdf-offset-:           calc((@vdf-width + @vdf-button-size) * -1);


// --------------------------------------------------
// Typography
// --------------------------------------------------

@import url('https://fonts.googleapis.com/css?family=Roboto:400,500');

@vdf-font-family:       'Roboto', sans-serif;
@vdf-base-font:         16px;
@vdf-line-height:       24px;


// --------------------------------------------------
// Colors
// --------------------------------------------------

@color-primary:         #3498DB;
@color-warning:         #F39C12;
@color-error:           #E74C3C;
@color-success:         #27AE60;

@text-primary:          rgba(0,0,0,.87);
@text-secondary:        rgba(0,0,0,.54);
@text-disabled:         rgba(0,0,0,.38);
@input-border:          rgba(0,0,0,.15);

@dialog-bg:             #FFFFFF;
@avatar-placeholder:    #999999;


// --------------------------------------------------
// Animation
// --------------------------------------------------

@ease-bounce:           cubic-bezier(0.68, -0.55, 0.265, 1.55);
@ease-in-out:           cubic-bezier(0.19, 1, 0.22, 1);

```
