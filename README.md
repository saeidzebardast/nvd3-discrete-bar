# &lt;nvd3-discrete-bar&gt; [![Build Status](https://travis-ci.org/saeidzebardast/nvd3-discrete-bar.svg?branch=master)](https://travis-ci.org/saeidzebardast/nvd3-discrete-bar)

Discrete bar chart element for [Polymer](https://www.polymer-project.org) using [nvd3](http://nvd3.org/). It's part of [nvd3 charting elements](https://github.com/saeidzebardast/nvd3-elements).

## Install

```
bower install nvd3-discrete-bar
```

## Usage

### Tag

```
<nvd3-discrete-bar data="[[data]]" auto-resize></nvd3-discrete-bar>
```

### Data Format

```
[
  {
    key: "Cumulative Return",
    values: [
      {
        "label" : "A" ,
        "value" : -29.765957771107
      } ,
      {
        "label" : "B" ,
        "value" : 0
      } ,
      {
        "label" : "C" ,
        "value" : 32.807804682612
      }
    ]
  }
]
```

## License

MIT © [Saeid Zebardast](http://zebardast.com)
