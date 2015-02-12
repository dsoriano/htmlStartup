Changes from Original KNACSS
----------------------------

### File _00-config.scss ###

Report settings parameters to _settings.scss root file, KNACSS mixins to _mixins.scss root file, disable __00-config.scss

Add boolean variable to use Knacss grids hacks for old IE (default false)

Add boolean variable to use IE6/7 box-sizing polyfill (default false)

### File _03-grids.scss ###

Disable file _03-grids.scss because we are using our own grid system. You can switch grid system in style.scss root file

### file _12-ie.scss ###

Replace class `.ie678` by `.oldie`

Add condition to use Knacss grids hacks for old IE

Add condition to use IE6/7 box-sizing polyfill

### file _knacss.scss ###

Disable file _knacss.scss, we are now using style.scss root file
