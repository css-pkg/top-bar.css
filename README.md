# top-bar.css

A top bar navigation pattern.

[![npm][1]][2]
[![travis][3]][4]
[![standard][5]][6]
[![downloads][7]][2]

[1]: https://img.shields.io/npm/v/top-bar.css.svg?style=flat-square
[2]: https://www.npmjs.com/package/top-bar.css
[3]: https://img.shields.io/travis/css-pkg/top-bar.css/gh-pages.svg?style=flat-square
[4]: https://travis-ci.org/css-pkg/top-bar.css
[5]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square
[6]: http://standardjs.com/
[7]: https://img.shields.io/npm/dm/top-bar.css.svg?style=flat-square

# Install

```
npm install top-bar.css
```

## Usage

```html
<!DOCTYPE html>
<html>
  <head>
    ...
    <link rel="stylesheet" href="path/to/top-bar.css">
    ...
  </head>
  <body>
    ...
    <nav class="top-bar">
      <a href="#" class="top-bar-title">site title</a>
      <a href="#" class="top-bar-link">some nav link</a>
      <a href="#" class="top-bar-link">another one</a>
      <a href="#" class="top-bar-link current-page">current page</a>

      <div class="top-bar-right">
        <a href="#" class="top-bar-link">this one's on the right</a>
      </div>
    </nav>
    ...
  </body>
</html>
```

Everything is scoped to `.top-bar`.

Compatible with [css-via-npm](https://github.com/sethvincent/css-via-npm) workflows.

### Sass

You can also use this as a [Sass](http://sass-lang.com/) library.

```scss
@import '../node_modules/top-bar.css/source/top-bar';
```

You can set the font family like so:

```scss
$top-bar-family: 'Comic Sans';
@import '../node_modules/top-bar.css/source/top-bar';
```

## License

[ISC](LICENSE.md)
