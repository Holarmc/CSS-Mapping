# CSS-Mapping
This is an atempt to make sense of the broad CSS syntax and utility made available; connecting the dots to make a bit of sense.
you are welcome to make additons. 


# CSS

## Introduction

CSS: Cascading Style Sheet.
CSS is connected to its corresponding html file via:

- inline
- Internal
- External

CSS consist of a bunch of pre-defined keywords which perform specific function.

> N.B: It is imperative to know each of the keywords and the function they perform for us to use CSS efficiently - **_thankfully, we don't need to know all to desgin beautiful websites; 60% of styling is done by 40% of the keywords._**)

Based on the functions performed, css keywords can be broadly categorized into:

- Selectors
- Declaration (property & value)
- Layering
- Animation
- aesthetics
- utilities.

### CSS Syntax

```javascript
 selector {
      property: value
      }
```

where `property: value` are collectively called _declaration_.

## Selectors

- Based on style of use, `Selectors` can be classified as _Grouped_ or _Ungrouped_.

  _Ungrouped selectors_:

  ```CSS
      h1 {
      outline:none;
      border: 1px solid red;
      }
      h1 { background-color: black}

      h2 {
          outline:none;
          border: 1px solid red;
      }
      h2 { background-color: black}

  ```

  _Grouped selectors:_

  ```CSS
      h1, h2 {
          outline: none;
          border: 1px solid red;
      }

      h1, h2 { background-color: black}

  ```

- Based on "how they select", `Selectors` can be classified into:
  - Element selector
  - Class selector
  - Id selector
  - Attribute selector
  - Relationship selector
  - Pseudo selector

## Declaration

- Based on the style of use, `Declaration` also can be either _Grouped_ or _Ungrouped_.

_Ungrouped declaration:_

```CSS
        h1 {outline: none}
        h1 {border: 1px solid red}
```

_Grouped declaration:_

```CSS
        h1 {
            outline: none;
            border: 1px solid red;
        }
```

`Declaration` consist of `property` & `value`, and for each `property` there is a list of corresponding `value` options, except "_special values_".

**Property**

CSS Property can be classified into:

- Typography (font & text)
- Color & Background
- Box
- classification
- Dimension

### Typography

|       parameter |                                                                                                    Note                                                                                                     |
| --------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|      font-style |                                                                                          normal,italics or oblique                                                                                          |
|    font-variant |                                                                                            normal or small-caps                                                                                             |
|     font-weight |                                                                                  normal, bold or numeric from 100 to 900.                                                                                   |
|       font-size |                                                                    The font size given in %, px, em, or any other valid CSS measurement                                                                     |
|     line-height |                                                                   The line height given in %, px, em, or any other valid CSS measurement                                                                    |
|     font-family |                                                                                   This is for defining the family's name.                                                                                   |
|           color |                                                               Any valid CSS color representation, like red, #00FF00, hsl(240, 100%, 50%) etc.                                                               |
|    font-stretch | Whether or not to use a confenced or expanded face from font. Valid values are normal, ultracondensed, extra-condensed, condensed, semi-condensed, semi-expanded, expanded, extraexpanded or ultra-expanded |
|      text-align |                                                                           start, end, left, right, center, justify, match-parent                                                                            |
| text-decoration |                                                                         none, underline, overline, line-through, initial, inherit;                                                                          |
|   text-overflow |                                                                                   ellipsis, clip, initial,inherit, unset                                                                                    |
|        overflow |                                                                           auto, hidden, scroll, visible, inherit, initial, unset                                                                            |
|          quotes |                                                              The quotes property is used to customize the opening and closing quotation marks                                                               |

**Special Values**
This are values that do not necessarily apply to a specific property, i.e. they are applicable to multiple property.

1. Units: - units are special values that are used to indicate measure. They are categorized into:
   -Absolute unit
   - Typographical unit
   - Relative unit
   - Font-relative unit
   - viewport unit
   - unit values
   - variables
     -calculated unit.

## Layering

These are CSS properties that directly affect the position and arrangement of elements. They are grouped thus:

- Positioning
- Vertical align/ vertical centering
- Centering (vertical + horizontal)
- Stacking
- Flexbox
- Grid

## Animation

This are CSS property that are used to bring about motion/ transitioning. They include:

- Transition
- Transform
- Keyframes

## aesthetics

This are CSS property that are used to bring about visual effect to elements. They include:

- Filter
- Blur
- Hue
- Shadows
- Shapes
- Cursor styling
- Clipping & Masking

## Utilities

This are CSS property that are used for specific use cases or a definite function. They include:

- Functions
- @ Rules

