*This repository is a mirror of the [component](http://component.io) module [component/sparkline](http://github.com/component/sparkline). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-sparkline`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# sparkline

  Tiny javascript sparkline canvas graphs.

  ![js sparkline](http://f.cl.ly/items/06470C043x150Q3N321L/spark.png)

## Installation

    $ component install component/sparkline

## API

### Sparkline(canvas)

  Initialize with the given `canvas`.

### Sparkline#update(data)

  Update `data` points, a series of floats. The sparkline
  will be drawn and automatically compressed to fit within
  the `canvas` dimensions.

## License

  MIT
