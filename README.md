# css-slider
A pure CSS 2-way or 3-way sliding switch

An easy-to-add pure CSS 2-way or 3-way sliding switch

## Include the stylesheet

```
<link rel="stylesheet" href="https://www.boddison.com/public/slider.css">
```

## Add HTML to form

Include the HTML as shown.  This can be included in an HTML form in the usual way.  Note that it is important that one option is initially `checked` for the switch to render properly.

```
<label class="slider">
<input class="sliderOption" type="radio" name="one" data-letter="N" value="N">
<input class="sliderOption" type="radio" name="one" data-letter="?" value="U" checked>
<input class="sliderOption" type="radio" name="one" data-letter="Y" value="Y">
</label>

<label class="slider">
<input class="sliderOption" type="radio" name="two" value="1">
<input class="sliderOption" type="radio" name="two" value="2" checked>
</label>
```

The switches will be labelled with the `value` attribute unless a `data-letter` attribute is included.  To omit the label, set a space character as the label using `data-letter=" "`

## Customisation

The following CSS custom properties can be defined to alter the appearance of the switches

`--slider-background-color` - background colour

`--slider-border-color` - border colour

`--slider-color` - colour for the switch positions

`--slider-first-color` - colour of slider in first (left) position

`--slider-last-color` - colour of slider in last (right) position

`--slider-text-color` - colour of the text labels

