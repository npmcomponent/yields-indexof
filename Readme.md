*This repository is a mirror of the [component](http://component.io) module [yields/indexof](http://github.com/yields/indexof). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-indexof`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# indexof

  indexof the given element.

## Installation

    $ component install yields/indexof

## Example

```js
var ul = document.createElement('ul');
var li = document.createElement('li');
ul.appendChild(document.createElement('li'));
ul.appendChild(li);
indexof(li); // 1
```

   

## License

  MIT
