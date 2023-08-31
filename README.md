# css-slider
A pure CSS 2-way or 3-way sliding switch

An easy-to-add pure CSS 2-way or 3-way sliding switch

```
<label class="slider">
<input class="sliderOption" type="radio" name="test1" data-letter="N" value="N">
<input class="sliderOption" type="radio" name="test1" data-letter="?" value="U" checked>
<input class="sliderOption" type="radio" name="test1" data-letter="Y" value="Y">
</label>

<label class="slider">
<input class="sliderOption" type="radio" name="test3" value="1">
<input class="sliderOption" type="radio" name="test3" value="2" checked>
</label>
```

The switches will be labelled with the `value` attribute unless a `data-letter` attribute is included.

## Customisation

The following CSS custom properties can be defined to alter the appearance of the switches

`--slider-background-color` - background colour

`--slider-border-color` - border colour

`--slider-color` - colour for the switch positions

`--slider-first-color` - colour of slider in first (left) position

`--slider-last-color` - colour of slider in last (right) position

`--slider-text-color` - colour of the text labels

