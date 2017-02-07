# sass-basis-margin-between-children
This is a css module for the Basis.

## Basis
* Repository: https://github.com/sass-basis/basis/
* Documents : https://sass-basis.github.io/

## Get Started

### Install
```
$ yarn add sass-basis
$ yarn add sass-basis-margin-between-children
```

### Stylus
```
// The bottom margin of HTML Elements is 0.
$_margin-bottom: 0;

@import 'node_modules/sass-basis/src/css/basis';
@import 'node_modules/sass-basis-margin-between-children/src/css/core/mixin/margin-between-children';

.entry-content {
  @include _margin-between-children(1);
}
```

## Browser support
Modern Browser and IE10+

## License
MIT License
