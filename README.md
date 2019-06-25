# Styleguide

This guide defines the basic principles and templates of the ```cividi``` visual language in regards to maps, diagrams and other visual outputs.

## Maps

Many of ```cividi's``` publicly visible activities are based on 2D maps. At it's core a ```cividi``` map should be

* **easy** to read and understand
* be open (cf. [open definition](https://opendefinition.org/od/2.1/en/))
* have [**accessible colors**](https://www.w3.org/TR/WCAG/#visual-audio-contrast)
* tell a story
* be **responsive**
* show the relevant **context**
* expose only the relevant user interaction
* a self contained, reproduceable package (cf. [map data package](maps/map-setup.md#mdp))

In a sense maps are a form of a diagram. Hence they could also be seen as a data driven document. To simplify map behavior, style etc. we started developing [smartuse-gl](https://github.com/smartuse/smartuse-gl). smartuse-gl is built on top of [mapbox-gl-js](https://github.com/mapbox/mapbox-gl-js).

## Diagrams

Diagrams should be treated as ```data driven documents```. To help this effort ```cividi``` is building up a library for urban data diagrams. In reference to projects like [Observable](https://observablehq.com/) based on [D3.js](https://github.com/d3/d3).
