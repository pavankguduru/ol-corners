
# Openlayers Corners
Corner positions for **OpenLayers** controls with stacking similar to what Leaflet `position` option does. 

## Usage
Import the CSS file **ol-corners.css**
```html
<link rel="stylesheet" href="./ol-corners.css" />
```

The following HTML code is required for setting up the positions
```html
<div id="ol-corners" class="ol-corners">
    <div id="top-right" class="top-right"></div>
    <div id="top-left" class="top-left"></div>
    <div id="top-center" class="top-center"></div>
    <div id="bottom-right" class="bottom-right"></div>
    <div id="bottom-left" class="bottom-left"></div>
    <div id="bottom-center" class="bottom-center"></div>
</div>
```

When adding a control to the map use the option `target` to add the control to the desired position.
```javascript
new  ol.control.Zoom({
    target:  "top-left"
})
```

Check this [JS fiddle](https://jsfiddle.net/pavankguduru/wnm5o42e/) to see it in action.