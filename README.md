# Stacked-to-Grouped Bars

A visualization example alternating between stacked and grouped layouts built
with [D3.js v4](https://github.com/d3/d3/releases/tag/v4.2.2), and based on 
this [older example from Mike Bostock for v3](https://bl.ocks.org/mbostock/3943967)

## Stacked view

![stacked bars](https://raw.githubusercontent.com/buruzaemon/d3_stacked_to_grouped/master/stacked.png)

The age groups for each US state are stacked up to show the total population in
relation to the others. Bar heights are scaled in accordance to the maximum of
the total populations.

## Grouped view

![grouped bars](https://raw.githubusercontent.com/buruzaemon/d3_stacked_to_grouped/master/grouped.png)

Toggling from stacked to grouped, the total populations for each state are now
broken out into their separate age group categories. Note how the bar heights
are now scaled in accordance to the maximum of the age group categories.

## Features

* [d3.scaleBand](https://github.com/d3/d3-scale/blob/master/README.md#scaleBand)
  for dynamically adjusting the width of the bars
* [d3.scaleLinear](https://github.com/d3/d3-scale/blob/master/README.md#scaleLinear)
  for automatically scaling the bar heights
* [d3.scaleOrdinal](https://github.com/d3/d3-scale/blob/master/README.md#scaleOrdinal)
  for setting the [sequential, multi-hued color pallete](http://colorbrewer2.org/#type=sequential&scheme=GnBu&n=9) representing each age group
* [d3.csv](https://github.com/d3/d3-request/blob/master/README.md#csv) to
  handle the comma-separated value data
* D3.js
  [selection.transition](https://github.com/d3/d3-transition/blob/master/README.md#selection_transition)
  for staged animations that improve graphical perception while preserving object constancy
