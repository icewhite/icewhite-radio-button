[![Build status](https://travis-ci.org/PolymerElements/icewhite-radio-button.svg?branch=master)](https://travis-ci.org/PolymerElements/icewhite-radio-button)

_[Demo and API docs](https://elements.polymer-project.org/elements/icewhite-radio-button)_


## &lt;icewhite-radio-button&gt;

Material design: [Radio button](https://www.google.com/design/spec/components/selection-controls.html#selection-controls-radio-button)

`icewhite-radio-button` is a button that can be either checked or unchecked.
User can tap the radio button to check or uncheck it.

Use a `<paper-radio-group>` to group a set of radio buttons.  When radio buttons
are inside a radio group, exactly one radio button in the group can be checked
at any time.

Example:

```html
<icewhite-radio-button></icewhite-radio-button>
<icewhite-radio-button>Item label</icewhite-radio-button>
```

### Styling

The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--icewhite-radio-button-unchecked-background-color` | Radio button background color when the input is not checked | `transparent` |
| `--icewhite-radio-button-unchecked-color` | Radio button color when the input is not checked | `--primary-text-color` |
| `--icewhite-radio-button-unchecked-ink-color` | Selected/focus ripple color when the input is not checked | `--primary-text-color` |
| `--icewhite-radio-button-checked-color` | Radio button color when the input is checked | `--primary-color` |
| `--icewhite-radio-button-checked-ink-color` | Selected/focus ripple color when the input is checked | `--primary-color` |
| `--icewhite-radio-button-size` | Size of the radio button | `16px` |
| `--icewhite-radio-button-label-color` | Label color | `--primary-text-color` |
| `--icewhite-radio-button-label-spacing` | Spacing between the label and the button | `10px` |

This element applies the mixin `--paper-font-common-base` but does not import `paper-styles/typography.html`.
In order to apply the `Roboto` font to this element, make sure you've imported `paper-styles/typography.html`.
