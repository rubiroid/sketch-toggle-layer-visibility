Sketch Plugin: Toggle Layer Visibility
==============================

In our Sketch files, we often use "boundingBox" layers in eg. icon layer groups to see (and use) their actual dimension and bounds. Since we don't want to see "boundingBoxes" permanently, we created this little plugin to toggle their visibility with a keyboard shortcut (cmd + l).

By default, the plugin toggles all layers with their name starting with "boundingBox", so for example "boundingBox 2" will be toggled as well (this is pretty nifty if you duplicate layers and get this automatic number at the end of the name). You can easily change the affected layer name in the plugin code.

![sketch-toggle-layer-visibility](https://raw.githubusercontent.com/preciousforever/sketch-toggle-layer-visibility/master/toggle-layer-visibility.gif)
