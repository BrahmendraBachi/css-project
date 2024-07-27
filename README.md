# CSS-PROJECT

## Selectors

1. Priority based styles is applied

    1. `id` > `class` > `tags`
    2. But style setting with is not recommended to use.

2. Not all properties can be inherited. Ex: `border`

3. Not all elements accept inheritance

    1. All Form elements will not accept inheritance Ex: `button`, `text`, `input`, etc
    2. We can use this property `inherit` for the styles to be inherited. Ex: `font-size`: `inherit`
    
4. https://specificity.keegan.st/  --> used for specifity calculator

## Colors

1. https://coolors.co/contrast-checker/112a46-45b69c

    1. helps in finding the best contrast for the selected background and text-color

## Units ans Sizes

1. Not always recommended to use absolute sizes `(ex: 16px, 32px...)`

2. https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units

## Typography

1. https://fonts.google.com/
    
    1. To download fonts and use it in our styles.css

## Styling Links

1. Element with pseupo-selector has more priority than the elements (only). ex: (`a:visited` > `a`)

## List Styles

1. `list-style-image` has more priority than `list-style-type`

## Display

1. `display: block` takes 100% available width

    1. `p`, `main`, etc.. are examples of block level elements
    2. `block` level elements does not stack on each other and always creates new line

2. `display: inline` takes width which is required

    1. `span` is an example of inline elements
    2. `inline` elements does stack on other and does not create new line

## Columns

1. Margin Collapsing

## Flex-Box

1. https://flexboxfroggy.com/

    1. visit to pracice more on styling in `flex-box`

## Grid Layout

1. https://cssgridgarden.com/

    1. visit to pracice more on styling in `grid`