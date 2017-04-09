# 03 Hex Bins

In this step we create hex bin geometries using Turf.JS, and choose which values to style our hex bins using the [Jenks Natural Breaks classification](https://en.wikipedia.org/wiki/Jenks_natural_breaks_optimization).
*__NOTE:__ I'm not a statistician and by no means recommend this classification for this data in a real world application. We are using it here for demonstration purposes only.*

## Things to try out
- Change the value of `cellSize` for our hexbins to create different bin sizes. Notice how the data loads much faster when using a value such as 10. Why might this be?

- Try using a different color ramp from [Color Brewer](http://colorbrewer2.org/). When might you use another color scheme than the "sequential" type, the one we're using in this example?

- Try turning on the original crashes data layer underneath our hexbins, can you see the relationship between the two?

## Helpful Links:

- [Turf HexGrid Documentation](http://turfjs.org/docs/#hexgrid)
- [Another Hexbin example using Turf.JS](http://bl.ocks.org/danswick/ea0c209ae1e0f8d88bba)
