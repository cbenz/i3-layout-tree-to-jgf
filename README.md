# i3 layout viewer

[![npm version](https://badge.fury.io/js/i3-layout-viewer.svg)](https://badge.fury.io/js/i3-layout-viewer)

The [i3](http://i3wm.org/) window manager allows to [save the layout](http://i3wm.org/docs/layout-saving.html) in a JSON file.

This tool converts this JSON file to a [DOT](http://www.graphviz.org/content/dot-language) file (see [GraphViz](http://www.graphviz.org/) tool).

![example layout](https://cdn.rawgit.com/cbenz/i3-layout-viewer/master/examples/layout.svg)

To actually visualize the graph, you'll need a viewer like [xdot](https://github.com/jrfonseca/xdot.py).
So the full chain is:

```
i3-save-tree | i3-layout-to-dot | xdot -
```

This tool was inspired by [this video](https://www.youtube.com/watch?v=AWA8Pl57UBY).

## Install

As root:

```
# npm install -g i3-layout-viewer
```
