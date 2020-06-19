## about

Just enough rules to cover wide enough a variety of cases opting for `auto` and `inherit` values where possible.

## setupe

Download the [latest version](https://www.npmjs.com/package/@thewhodidthis/reset.css) from the _npm_ registry:

```sh
# Add to 'package.json'
npm install @thewhodidthis/reset.css
```

## usage

May be easily consumed using [postcss-import](https://github.com/postcss/postcss-import) for example,

```css
/* Need a plugin or symlink to handle path resolution here */
@import('@thewhodidthis/reset.css');

ul, 
ol {
  padding-left: 1rem;
}
```

## see also

- [Reset reasoning](http://meyerweb.com/eric/thoughts/2007/04/18/reset-reasoning/)
- [Normalize.css](https://necolas.github.io/normalize.css/)
