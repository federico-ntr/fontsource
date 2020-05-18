# Fontsource Love Ya Like A Sister

The CSS and web font files to easily self-host the “Love Ya Like A Sister” font. Please visit the main [Fontsource monorepo](https://github.com/DecliningLotus/fontsource) to view more details on this package.

## Installation

Fontsource assumes you are using a bundler, such as Webpack, to load in CSS. Tools like [CRA](https://create-react-app.dev/), [Gatsby](https://www.gatsbyjs.org/) and [Next.js](https://nextjs.org/) are prebuilt example solutions that are compatible.

```javascript
yarn add fontsource-love-ya-like-a-sister // npm install fontsource-love-ya-like-a-sister
```

Then within your app entry file or site component, import it in. For example in Gatsby, you could simply import it into your `layout.js` component or `gatsby-browser.js` for limited circumstances.

```javascript
import "fontsource-love-ya-like-a-sister" //require("fontsource-love-ya-like-a-sister")
```

Fontsource allows you to select font subsets, weights and even individual styles, allowing you to cut down on payload sizes to the last byte! The default selection above, however, sticks to the Latin subset including all weights and styles.

```javascript
import "fontsource-love-ya-like-a-sister/latin-ext.css" // All weights and styles included.
import "fontsource-love-ya-like-a-sister/cyrillic-ext-400.css" // All styles included.
import "fontsource-love-ya-like-a-sister/greek-700-normal.css" // Select either normal or italic.
```

Alternatively, the same solutions could be imported via SCSS!

```scss
@import "~fontsource-love-ya-like-a-sister/index";
@import "~fontsource-love-ya-like-a-sister/vietnamese-300-italic";
```

_Do confirm on Google Fonts (or elsewhere) whether your font supports a certain subset, weight or style beforehand as these examples may not reflect actual compatibility._

## Other Notes

Feel free to star and contribute new ideas to this repository that aim to improve the performance of font loading, as well as expanding the existing library we already have. Any suggestions or ideas can be voiced via an [issue](https://github.com/DecliningLotus/fontsource/issues).