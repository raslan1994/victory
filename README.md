[![Travis Status][trav_img]][trav_site]

Victory
=======
Victory is an opinionated set of data visualization tools built in React. This repo aggregates all of the stable Victory components so they can be conveniently included. 

IMPORTANT
=========

This project is in a pre-release state. We're hard at work fixing bugs and improving the API. Be prepared for breaking changes!

## Including components:

Components can be included individually

```
import {VictroyLine, VictoryAxis} from "victory"

<VictoryLine/>
```

Or imported as a set:

```
import * as V from "victory"

<V.VictoryLine/>
```

## Components

You can read about these Victory components via interactive docs!

- [VictoryAxis](https://formidablelabs.github.io/victory-axis)
- [VictoryBar](https://formidablelabs.github.io/victory-bar)
- [VictoryChart](https://formidablelabs.github.io/victory-chart)
- [VictoryLine](https://formidablelabs.github.io/victory-line)
- [VictoryPie](https://formidablelabs.github.io/victory-pie)
- [VictoryScatter](https://formidablelabs.github.io/victory-scatter)


## Animation
Wrap any Victory component with [VictoryAnimation](https://github.com/FormidableLabs/victory-animation) and it will transition smoothly between states whenever data changes. VictoryAnimation relies on d3's interpolator, so it knows how to transitions between colors, dates, numbers, strings etc.

## Development

Please see [DEVELOPMENT](DEVELOPMENT.md)

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md)

[trav_img]: https://api.travis-ci.org/formidablelabs/victory.svg
[trav_site]: https://travis-ci.org/formidablelabs/victory
