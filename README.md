# zoomable-bar-chart
A Polymer element that creates a bar chart using d3 with the ability to zoom in on specific areas of the data and preserve
that selection for use as a filter.

Example:
```html
<zoomable-bar-chart timeline
  load
  bar-property="bar"
  stack-property="stack"
  data="[[data]]"
  default-label="Unknown Location"
  height="300"
  loading="[[chartLoading]]"
  selected="[[selected]]">
</zoomable-bar-chart>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve
