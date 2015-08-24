# pagarme-sass-styleguide
The awesome angular.js styleguide that we follow at Pagar.me

## Table of Contents

  1. [Syntax & Formatting](#syntax--formatting)
  1. [Selectors](#selectors)
  1. [Variables](#variables)

## Syntax & Formatting

* Ideally, 80-characters wide lines
* One (1) tab for indentation
* One (1) space after `:`
* No spaces between property value and `;`
* One (1) space between selector and first `{`
* One (1) line-break after first `{`
* One (1) line-break after last property

```
// Awesome
.some-style {
  background: red;
  width: 100%;
  height: 40px;
  overflow: hidden;
}
```

## Selectors

* Should be written in [kebab-case](http://c2.com/cgi/wiki?KebabCase)
* Use classes for everything, ids should be restricted for javascript purposes only, such as testing or `document.getElementById`
 
```
```
 
## Variables

* Should be written in [kebab-case](http://c2.com/cgi/wiki?KebabCase)
* Should have meaningful names
* nested variables should have one `_` per nesting level
