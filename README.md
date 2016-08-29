# Stacked-to-Grouped Bars

A visualization example alternating between stacked and grouped layouts built
with [D3.js v4](https://github.com/d3/d3/releases/tag/v4.2.2), and based on 
this [older example from Mike Bostock for d3.js v3](https://bl.ocks.org/mbostock/3943967)

## Stacked view

![](https://raw.githubusercontent.com/buruzaemon/d3_stacked_to_grouped/master/stacked.png)

The age groups for each US state are stacked up to show the total population in
relation to the others.

## Grouped view

![](https://raw.githubusercontent.com/buruzaemon/d3_stacked_to_grouped/master/grouped.png)

Toggling from stacked to grouped, the total populations for each state are now
broken out into their separate age group categories. 

## Features

* [d3.scaleBand](https://github.com/d3/d3-scale/blob/master/README.md#scaleBand)
  for dynamically adjusting the width of the bars
* [d3.scaleLinear](https://github.com/d3/d3-scale/blob/master/README.md#scaleLinear)
  for automatically scaling the bar heights
* [d3.scaleOrdinal](https://github.com/d3/d3-scale/blob/master/README.md#scaleOrdinal)
  for setting the categorical color pallete for each age group
* [d3.csv](https://github.com/d3/d3-request/blob/master/README.md#csv) to
  handle the comma-separated value data
