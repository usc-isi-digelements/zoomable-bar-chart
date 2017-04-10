# zoomable-bar-chart
A Polymer element that creates a bar chart using d3 with the ability to zoom in on specific areas of the data.

Example:
```html
    <zoomable-bar-chart timeline
        bar-property="bar"
        stack-property="stack"
        data="[[data]]"
        default-label="Unknown Location"
        height="300"
        chart-title="{{chartTitle}}"
        loading="[[chartLoading]]">
    </zoomable-bar-chart>
```

### Styling
`<zoomable-bar-chart>` provides the following custom properties and mixins for styling:

Custom property          | Description                                    | Default
-------------------------|------------------------------------------------|-------------------------
`--chart-axis-color`     | Color for axis lines and labels                | #727272
`--chart-text-color`     | Text color for title text                      | --paper-blue-grey-800
`--chart-color-1`        | Color for first bar in chart (16 colors total) | --paper-blue-500
`--chart-color-2`        | Second color for bars in chart                 | --paper-orange-500
`--chart-color-3`        | Third color for bars in chart                  | --paper-green-500
`--chart-color-4`        | Fourth color for bars in chart                 | --paper-red-500
`--chart-color-5`        | Fifth color for bars in chart                  | --paper-purple-500
`--chart-color-6`        | Sixth bar color                                | --paper-yellow-500
`--chart-color-7`        | Seventh bar color                              | --paper-indigo-500
`--chart-color-8`        | Eighth bar color                               | --paper-cyan-500
`--chart-color-9`        | Ninth bar color                                | --paper-deep-orange-500
`--chart-color-10`       | Tenth bar color                                | --paper-lime-500
`--chart-color-11`       | Eleventh bar color                             | --paper-pink-500
`--chart-color-12`       | Twelfth bar color                              | --paper-deep-purple-500
`--chart-color-13`       | Thirteenth bar color                           | --paper-amber-500
`--chart-color-14`       | Fourteenth bar color                           | --paper-teal-500
`--chart-color-15`       | Fifteenth bar color                            | --paper-light-green-500
`--chart-color-16`       | Sixteenth bar color                            | --paper-light-blue-500
`--chart-other-color`    | Color for potential other category             | --paper-grey-500
`--chart-overview-color` | Color for bars in overview used for zooming    | --paper-blue-grey-900
