## about

Just enough rules to cover wide enough a variety of cases opting for `auto` and `inherit` values where possible.

## setupe

Fetch the latest version from the _npm_ registry:

```sh
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
