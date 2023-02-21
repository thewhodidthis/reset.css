## about

Just enough rules to cover wide enough a variety of cases opting for `auto` and `inherit` values where possible.

## setup

Download from GitHub directly:

```sh
# Add to package.json
pnpm install thewhodidthis/reset.css
```

## usage

May be easily consumed using [postcss-import](https://github.com/postcss/postcss-import)&hellip; or not!

```css
@import url("https://thewhodidthis.github.io/reset.css/reset.css");

ul,
ol {
  padding-left: 1rem;
}
```

## see also

- [Eric Meyer's reset reasoning](http://meyerweb.com/eric/thoughts/2007/04/18/reset-reasoning/)
- [Normalize.css](https://necolas.github.io/normalize.css/)
