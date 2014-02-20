*This repository is a mirror of the [component](http://component.io) module [bmcmahen/target](http://github.com/bmcmahen/target). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/bmcmahen-target`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# target

  cross-browser e.target, because IE8 loves us

## Installation

  Install with [component(1)](http://component.io):

    $ component install bmcmahen/target

## Usage

```javascript
function someEvent(e){
  var el = target(e);
}
```

## License

  MIT
