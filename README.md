# css-max-widths 0.0.6

Css module of single purpose classes for max widths

#### Stats

242 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-max-widths
```

#### With Git

```
git clone https://github.com/tachyons-css/css-max-widths
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-max-widths";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-max-widths">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   MAX WIDTHS - KEYWORDS
*/
.mx-wi-none { max-width: none; }
.mx-wi-max { max-width: max-content; }
.mx-wi-min { max-width: min-content; }
.mx-wi-fit { max-width: fit-content; }
.mx-wi-fill { max-width: fill-available; }
@media screen and (min-width: 48em) {
 .mx-wi-none-ns { max-width: none; }
 .mx-wi-max-ns { max-width: max-content; }
 .mx-wi-min-ns { max-width: min-content; }
 .mx-wi-fit-ns { max-width: fit-content; }
 .mx-wi-fill-ns { max-width: fill-available; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .mx-wi-none-m { max-width: none; }
 .mx-wi-max-m { max-width: max-content; }
 .mx-wi-min-m { max-width: min-content; }
 .mx-wi-fit-m { max-width: fit-content; }
 .mx-wi-fill-m { max-width: fill-available; }
}
@media screen and (min-width: 64em) {
 .mx-wi-none-l { max-width: none; }
 .mx-wi-max-l { max-width: max-content; }
 .mx-wi-min-l { max-width: min-content; }
 .mx-wi-fit-l { max-width: fit-content; }
 .mx-wi-fill-l { max-width: fill-available; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

