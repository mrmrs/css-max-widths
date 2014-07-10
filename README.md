# CSS MAX WIDTHS

  Mobile-first classes for css-max-widths.
  Set the desired css-max-widths on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-max-widths
```
or download the css on github and include in your project.

## File Size


## The Code
```
.mx-wi-none { max-width: none; }
.mx-wi-max  { max-width: max-content; }
.mx-wi-min  { max-width: min-content; }
.mx-wi-fit  { max-width: fit-content; }
.mx-wi-fill { max-width: fill-available; }

@include break(not-small) {
  .mx-wi-none-ns { max-width: none; }
  .mx-wi-max-ns  { max-width: max-content; }
  .mx-wi-min-ns  { max-width: min-content; }
  .mx-wi-fit-ns  { max-width: fit-content; }
  .mx-wi-fill-ns { max-width: fill-available; }
}

@include break(medium) {
  .mx-wi-none-m { max-width: none; }
  .mx-wi-max-m  { max-width: max-content; }
  .mx-wi-min-m  { max-width: min-content; }
  .mx-wi-fit-m  { max-width: fit-content; }
  .mx-wi-fill-m { max-width: fill-available; }
}

@include break(large) {
  .mx-wi-none-l { max-width: none; }
  .mx-wi-max-l  { max-width: max-content; }
  .mx-wi-min-l  { max-width: min-content; }
  .mx-wi-fit-l  { max-width: fit-content; }
  .mx-wi-fill-l { max-width: fill-available; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

