# Line chart labels plugin for Chartist.js

Please visit http://gionkunz.github.io/chartist-js/plugins.html for more information.

## Available options and their defaults

```javascript
var defaultOptions = {
  labels: [], // An array of chart labels for chart series
  labelClass: 'ct-label', // Default css class for chart label
  labelOffset: {
      x: 5, // Label position shift on X axis
      y: -5 // Label position shift on Y axis
  },
  labelSpacing: '100px' // default label spacing
};
```

## Sample usage in Chartist.js


```javascript
var chart = new Chartist.Line('.ct-chart', {
  series: [/* */]
}, {
  plugins: [
    Chartist.plugins.lineChartLabels({
      labels: ['Max', 'Min']
    })
  ]
});
```