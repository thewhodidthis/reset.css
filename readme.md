Just enough rules to cover wide enough a variety of cases opting for `auto` and `inherit` values where possible,

```sh
npm install @thewhodidthis/reset.css
```

Consume using [postcss-import](https://github.com/postcss/postcss-import) for example,

```css
/* Need a plugin or symlink to handle path resolution here */
@import('@thewhodidthis/reset.css');

ul, 
ol {
  padding-left: 1rem;
}
```
