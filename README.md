#Mass Shootings in the US

The visualization is using data from [www.shootingtracker.com](www.shootingtracker.com) and covers the period January 2013 through early December 2015. The event data (comprised of over 1000 shooting events) has been grouped into weeks. 

Notes:

1. The map can be dragged and zoomed with the mouse
2. The circles on the map corresponds to the shooting events in the selected weeks. The larger the circle the higher the dead/injured count 
3. The color coding means red for events where deaths occured and orange for events with injuries but no deaths
4. The bar chart at the bottom is interactive. There is a rectangular area called **brush** on the bar chart which is used to select the weeks of interest. When starting up, the visualization has preselected the weeks in the range of October 2014 to October 2015
5. The brush can be dragged sideways, or resized by dragging the brush "handles" at the right and left edge of the brush
6. By clicking outside the brush, all weeks (153 in total) will be selected (at which point in time, the brush will be hidden)
7. To re-engage the brush (and the weekly filter), simply drag across the bar chart with the mouse
8. When starting up, the visualization has selected the shooting event count per week as the data source for the bar chart. To change the data source to either dead or injured, use the "radio" buttons on the left of the bar chart
9. To animate the data week by week, use the **Start Animation** button on top of the bar chart. 
10. The animation can be stopped or resumed, single-stepped forwards or backwards, and the animation speed can be adjusted
11. The animation cycles through each week and when reaching the end, will restart at the first week

Technically, the visualization is using **D3.js**, **Crossfilter.js** and **Mapbox's API**. The map source is Mapbox and Open Streetmaps.

See the visualization in action [here](http://bl.ocks.org/boeric/c1fe5650da3d6e790706). 