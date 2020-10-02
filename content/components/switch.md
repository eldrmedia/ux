+++
description = "Used to view or switch between enabled or disabled states or off and on states."
directory = "components"
landingimage = "/images/components/switch.jpg"
layout = "details"
title = "Switch"
toc = true
+++

## Usage
Use switches when your intent is to turn something on or off instantly, for example, if you need to enable compendium access to a resource.

If a physical switch would work for the action, a switch is probably the best component to use.


## Best Practices
* Use a pairing label with your switch using an id to set the relationship. [For more information see labels on MDN web docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label).
* Let people know what happens when the toggle is switched by using a tooltip.
* Switches should never require users to press a button to apply the settings.


## Content guidelines
When writing tooltips for toggle states, be short and concise.


## Related
* To be able to select options that require a button press to apply the setting use a [checkbox](/components/checkbox/).
* Use a [dropdown menu](/components/dropdown-menu/) to select a single option from a list.
* Use [radio buttons](/components/radio-button/) to select a single option from a set of visible options.


## Examples

### Default
The default form of a toggle.

<div class="ds-code-example">
  <div class="ds-code-example__showcase bg-white">
    <div class="custom-control custom-switch">
    <input type="checkbox" class="custom-control-input" id="customSwitch1">
    <label class="custom-control-label" for="customSwitch1">Toggle this switch element</label>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="custom-control custom-switch">
        <input type="checkbox" class="custom-control-input" id="customSwitch1">
        <label class="custom-control-label" for="customSwitch1">Toggle this switch element</label>
    </div>
    {{< /highlight-code >}}
    </div>
</div>


### Disabled

<div class="ds-code-example">
  <div class="ds-code-example__showcase bg-white">
    <div class="custom-control custom-switch">
    <input type="checkbox" class="custom-control-input" disabled id="customSwitch2">
    <label class="custom-control-label" for="customSwitch2">Disabled switch element</label>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="custom-control custom-switch">
        <input type="checkbox" class="custom-control-input" disabled id="customSwitch2">
        <label class="custom-control-label" for="customSwitch2">Disabled switch element</label>
    </div>
    {{< /highlight-code >}}
    </div>
</div>

