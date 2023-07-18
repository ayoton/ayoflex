### No more unnecessary container, negative margin-padding and extra divs to make gap between rows and columns.

---

<p align="center">
  <a href="https://ayoflex.ayoton.com/">
    <img src="https://ayoflex.ayoton.com/ayoflex.png" alt="Ayoflex logo" width="216" height="100">
  </a>
</p>

# Advanced CSS layout utility library

AyoFlex is a modern open source CSS layout utility library based on `flex` layout module with twelve columns grid system to build mobile first responsive web interfaces. Ayoflex includes six default breakpoints known as responsive modifiers. These breakpoints can be customized using our source Sass file.

## Documentation

### You can find everything fully documented at the [Official Website](https://ayoflex.ayoton.com).

## Installation

To use AyoFlex on your project, you can use the pre-compiled css file and also can install the scss files so that you can customize it by yourself.

## Packages

Use your favorite package manager to install AyoFlex

### NPM:

```bash
$ npm install ayoflex
```

or

```bash
$ npm i ayoflex
```

### Yarn:

```bash
$ yarn add ayoflex
```

## Import ayoflex in your project

To import ayoflex in your project use the following code in your js file:

```bash
import 'ayoflex';
```

#### or

```bash
import 'ayoflex/dist/ayoflex.min.css';
```

<br>

Also you can easily import style to your existing CSS/SCSS/SASS file:

#### Import css in your stylesheet

```css
@import "ayoflex/dist/ayoflex.min.css";
```

#### or

#### Import scss in your SASS file

```scss
@import "ayoflex/src/ayoflex";
```

## CDN

You can also add AyoFlex in your project from CDN:

```html
<link
  rel="stylesheet"
  href="https://unpkg.com/ayoflex@1.0.4/dist/ayoflex.min.css"
/>
```

If you don't need responsiveness you can install a lite version:

```html
<link
  rel="stylesheet"
  href="https://unpkg.com/ayoflex@1.0.4/dist/ayoflex-no-responsive.min.css"
/>
```

---

## Copyright and license

Code and documentation copyright 2022 [Ayoton](https://ayoton.com). Code released under the [MIT License](https://github.com/ayoton/ayoflex/blob/main/LICENSE). Docs released under [Creative Commons](https://creativecommons.org/licenses/by/3.0/).
