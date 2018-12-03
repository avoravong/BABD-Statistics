---
title       : Gun Violence in the United States
subtitle    : BABD
author      : Group Members
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2
<!-- GeoChart generated in R 3.5.1 by googleVis 0.6.3 package -->
<!-- Mon Dec 03 12:50:29 2018 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartID400c2dc7187b () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
"alabama",
0.14
],
[
"alaska",
0
],
[
"arizona",
0.44
],
[
"arkansas",
0
],
[
"california",
0.74
],
[
"colorado",
0.43
],
[
"connecticut",
1
],
[
"delaware",
1
],
[
"florida",
0.37
],
[
"georgia",
0.29
],
[
"hawaii",
1
],
[
"idaho",
0
],
[
"illinois",
0.56
],
[
"indiana",
0.22
],
[
"iowa",
0.25
],
[
"kansas",
0
],
[
"kentucky",
0.17
],
[
"kentucky",
0.17
],
[
"louisiana",
0.17
],
[
"maine",
0.5
],
[
"maryland",
0.88
],
[
"massachusetts",
1
],
[
"michigan",
0.36
],
[
"minnesota",
0.63
],
[
"mississippi",
0.25
],
[
"missouri",
0.25
],
[
"montana",
0
],
[
"nebraska",
0.33
],
[
"nevada",
0.25
],
[
"new hampshire",
0.5
],
[
"new jersey",
0.5
],
[
"new mexico",
0.67
],
[
"new york",
0.67
],
[
"north carolina",
0.23
],
[
"north dakota",
0
],
[
"ohio",
0.25
],
[
"oklahoma",
0
],
[
"oregon",
0.8
],
[
"pennsylvania",
0.28
],
[
"rhode island",
1
],
[
"south carolina",
0.14
],
[
"south dakota",
0
],
[
"tennessee",
0.22
],
[
"texas",
0.31
],
[
"utah",
0
],
[
"vermont",
1
],
[
"virginia",
0.27
],
[
"washington",
0.6
],
[
"west virginia",
1
],
[
"wisconsin",
0.38
],
[
"wyoming",
0
] 
];
data.addColumn('string','state');
data.addColumn('number','pct.d');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoChartID400c2dc7187b() {
var data = gvisDataGeoChartID400c2dc7187b();
var options = {};
options["width"] = 556;
options["height"] = 347;
options["region"] = "US";
options["displaymode"] = "regions";
options["resolution"] = "provinces";
options["colorAxis"] = {colors:['red', 'blue']};

    var chart = new google.visualization.GeoChart(
    document.getElementById('GeoChartID400c2dc7187b')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "geochart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartGeoChartID400c2dc7187b);
})();
function displayChartGeoChartID400c2dc7187b() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartID400c2dc7187b"></script>
 
<!-- divChart -->
  
<div id="GeoChartID400c2dc7187b" 
  style="width: 556; height: 347;">
</div>

--- .class

## Slide 3

![Correlation](C:/Users/amvor/OneDrive/Desktop/All Matieral - R Studio/Project/slidifydemo/assets/img/cor - number of incidents v number of guns.png)

--- .class

## Slide 4
