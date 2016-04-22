# Release Notes

## Department Templates 

### Version 1.5 - April 22, 2016

In addition to the major items listed below, there may have been comments and code formatting updates to the files.

#### HTML
* All html pages:
  1. Updated top-nav
  2. Added copyright year js in footer
  2. Added "We Will" icon in footer
  3. Removed unnecessary js/css links
  4. New `html5shiv-printshiv.js` - links to common.northwestern.edu
  6. Misc improvements and bug fixes

* `/index.html`
  1. Updated page type list

* `/boilerplate.html`
  1. Added `ul.steps` for large numbers
  2. Changed table hover state
  2. New `.table-no-hover` option for `<table>`   

* `/form.html`
  1. Fixed issue with checkboxes/radio buttons on forms

* `/expand-collapse.html`
  1. Updated to accessible expand/collapse with 3 variants

* `/landing-page.html`
  1. Added **feature boxes 4 columns**
  2. Added one callout option for **stats callout**
  3. Added **announcement** option under hero
  4. Added **photo feature (2 across)** and **photo feature (3 across)**  with and without hover
  5. Added new **large feature** option with `#right-side` div for additional content (previous version still supported)

* `/news-story-page.html`
  1. New

* `/photo-grid.html`
  1. New

* `/standard-page.html`
  1. Added **background select** option
  2. Added **photo feature (2 across)** with and without hover

* `/standard-photo-grid.html`
  1. New – may be used in responsive tabs (as shown)

#### SASS
* `/scss/base/_buttons.scss`
  1. `<p class="button"><a href="#">Link</a></p>` now behaves like `<p><a href="#" class="button">Link</a></p>`

* `/scss/base/_forms.scss`
  1. Removed form specific variables
  2. Added smaller input field option

* `/scss/base/_variables.scss`
  1. Removed form specific variables

* `/scss/base/_typography.scss`
  1. Added media query for floating images
  2. Changed table hover state
  3. New `.table-no-hover` option for `<table>`
  4. Added line heights for header tags

* `/scss/page-types/landing-page/_announcement.scss`
  1. New announcement feature for home page under hero

* `/scss/page-types/landing-page/_feature_boxes-4-columns.scss`
  1. New
  
* `/scss/page-types/landing-page/_large-feature.scss`  
  1. Added new `#right-side` for additional content other than links (previous version still supported) 
 
* `/scss/page-types/landing-page/_photo-feature-2-across.scss`  
  1. Added missing flip option  
 
* `/scss/page-types/landing-page/_photo-grid.scss`  
  1. New

* `/scss/landing-page/_slider.scss`
  1. Changed slider controls behavior on mobile

* `/scss/landing-page/_stats-callout.scss`
  1. Added one callout option

* `/scss/standard-page/_background-select.scss`
  1. New

* `/scss/page-types/standard-page/_expand-collapse.scss` 
  1. Replaces old version
  2. Adds 3 variations

* `/scss/standard-page/_main.scss`
  1. Added `ul.steps` style

* `/scss/page-types/standard-page/_narrow-page.scss`
  1. Added news story page styles

* `/scss/page-types/standard-page/_news-event.scss`
  1. Removed grey triangle background image
  
* `/scss/page-types/standard-page/_photo.grid.scss`
  1. New - may also be used in responsive tabs (as shown)  

* `/scss/page-types/standard-page/_showcase.scss`
  1. Changed slider controls behavior on mobile

* `/scss/sections/_footer.scss`
  1. fixed long link text wrapping issue

* `/scss/sections/_top-nav.scss`
  1. Better spacing of links

#### CSS
* `/css/print.css`
  1. Updated 

* `/css/styles.css`
  1. Compiled css (expanded for dev use)

#### JS
* `/scripts/scripts.js`
  1. Removed old expander, added accessible minified jquery.expander to top
  2. **photo feature** no longer flips when there's no `.back`

### Version 1.0

Initial Commit

## Header/Footer Templates

### Version 1.5 - April 22, 2016

In addition to the major items listed below, there may have been comments and code formatting updates to the files.

#### HTML
* `/index.html`
  1. Added copyright year js in footer
  2. Added "We Will" icon in footer
  3. New `html5shiv-printshiv.js` - links to common.northwestern.edu
  5. Updated top-nav
  
#### SASS

* `/scss/base/_typography.scss`
  1. Added line heights for header tags  
 
* `/scss/sections/_footer.scss`
  1. Added "We Will" icon 

* `/scss/sections/_mobile-nav.scss`
  1. Added `#mobile-nav-bottom-right` style
 
#### CSS
* `/css/print.css`
  1. New  

* `/css/styles.css`
  1. Compiled css (expanded for dev use)
  
### Version 1.0
  
Initial Commit
