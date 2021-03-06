# Eku

Eku is a friendly, lightful and highly customizable css library to make modern and beaty web pages, applications and so much more; using the latest modern utilities to save time and apply useful styles.

## Usage

To use the [eku](https://github.com/ekucss/eku) library, you must link in the `head` section of your HTML page the link below.

```html
<link rel="stylesheet" href="https://unpkg.com/eku" />
```

Also, you can use the minified version, but it doesnt have a source map, is only for **production** or optimization purposes.

```html
<link rel="stylesheet" href="https://unpkg.com/eku@latest/css/eku.min.css" />
```

If you have a `Node.js` project, you can install it from `npm` or `yarn` using the commands below.

```
npm i eku
yarn add eku
```

## Theming

You can customize all the variables available using on a `scss` file when you import the library.

```scss
@use "eku" with (
    $primary: "#222",
    $text-family: "Poppins",
)
```

> Can i import just atoms? **YES, you can**.

Even you can import all components what you wanna got.

```scss
// CUSTOMIZE

@use "eku/variables" with (
    $primary: "#222",
    $text-family: "Poppins",
);

// IMPORT THEM!

@use "eku/atoms/all";
@use "eku/layout/dashboard.scss";
@use "eku/layout/container.scss";
```

Code by [@adwher](https://github.com/adwher)
