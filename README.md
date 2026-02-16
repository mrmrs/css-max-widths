# css-max-widths

Functional CSS for max-widths

## Filesize

| File | Size |
|------|------|
| `dist/max-widths.css` | 1065 bytes |
| `dist/max-widths.min.css` | 781 bytes (185 Gzipped) |

## Install

```sh
npm install css-max-widths
```

## Usage

### Import

```css
@import "css-max-widths";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-max-widths/dist/max-widths.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-max-widths/dist/max-widths.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.mx-wi-none` | `max-width: none;` |
| `.mx-wi-max` | `max-width: max-content;` |
| `.mx-wi-min` | `max-width: min-content;` |
| `.mx-wi-fit` | `max-width: fit-content;` |
| `.mx-wi-fill` | `max-width: fill-available;` |
| `.mx-wi-none-s` | `max-width: none;` |
| `.mx-wi-max-s` | `max-width: max-content;` |
| `.mx-wi-min-s` | `max-width: min-content;` |
| `.mx-wi-fit-s` | `max-width: fit-content;` |
| `.mx-wi-fill-s` | `max-width: fill-available;` |
| `.mx-wi-none-m` | `max-width: none;` |
| `.mx-wi-max-m` | `max-width: max-content;` |
| `.mx-wi-min-m` | `max-width: min-content;` |
| `.mx-wi-fit-m` | `max-width: fit-content;` |
| `.mx-wi-fill-m` | `max-width: fill-available;` |
| `.mx-wi-none-l` | `max-width: none;` |
| `.mx-wi-max-l` | `max-width: max-content;` |
| `.mx-wi-min-l` | `max-width: min-content;` |
| `.mx-wi-fit-l` | `max-width: fit-content;` |
| `.mx-wi-fill-l` | `max-width: fill-available;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.mx-wi-none-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/max-widths.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/max-widths.css` — formatted
- `dist/max-widths.min.css` — minified

## License

MIT
