![titlepicture](data/example_svg_file.svg)
# D3_javascript

Scripts for D3.js (Data Driven Documents) to present scientific data online. Based on the book [Interactive Data Visualization for the Web](https://www.oreilly.com/library/view/interactive-data-visualization/9781449340223/)
 
### Connect data to server (from csv and from variable)
- script 01
- data types of csv files have to be specified, otherwise it is recognized as string (no automatical recognition of numerical data)

### Bar chart via "div" and css via modified rectangles
- script 02
- strange way to plot something, because I basically create just different sized rectangles in a "division" ("div")

### SVG files
- script 03 importing svg files
- script 04 building svg files
- consist of creating an environment and adding objects to it
- if objects don't exist yet, just refer to them, add them with enter() and modify them afterward

![scatterplot](data/scatter-plot.png)

### Scale Method
- script 05
- scale a domain input to an output range (e.g. scale timeseries from 0s to 1200 s to a range of 0 to 100 px, if the window is only 100 px wide)
- add axis to the scatterplot and add ticks based on xScale and yScale
- additionally there are the methods:
  - nice() for rounding values
  - rangeRound() 
  - clamp() to never exceed the range when exceeding the domain
- there are different scale methods
  - scaleLinear used here
  - scaleTime used here
  - scaleSqrt
  - scalePow
  - scaleLog
  - scaleQuantize with discrete input
  - scaleOrdinal for non quantitative values
  - more

### Transition between visualizations
- script 06
- update data in a smooth way by using transitions



### Bug
- at the moment it is not possible to load data from csv and set the dtype to numerical types
- it seems that the data is not an array when loaded from csv (maybe formatting error)
## author
```
Eric Schmidt
```


