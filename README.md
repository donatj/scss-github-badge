# SCSS Compass Github Badge Mixin

## Examples

![red](https://raw.github.com/donatj/scss-github-badge/master/examples/red.png)
![blue](https://raw.github.com/donatj/scss-github-badge/master/examples/blue.png)
![orange](https://raw.github.com/donatj/scss-github-badge/master/examples/orange.png)
![purple](https://raw.github.com/donatj/scss-github-badge/master/examples/purple.png)

## Usage

Add the following HTML immediately below `<body>`

```html
<div class="github_badge">
  <a href="https://github.com/donatj" target="_blank">Fork me on Github!</a>
</div>
```

Copy the `_github_badge.scss` file into your SASS/SCSS folder, and include the style.

```scss
@import "github_badge.scss";
@include github_badge( orange );
```

Then just make sure you're using `compass`
