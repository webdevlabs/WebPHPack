# WebPHPack
WebPHPack is a php alternative to webpack for auto combining multiple JS and CSS files into single files. 

### Usage
```
$webphpack = new WebPHPack($htmlsource);
$webphpack->combineJS();
$webphpack->combineCSS();
$newHTMLsource = $webphpack->output();
```
