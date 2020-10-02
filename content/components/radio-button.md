+++
description = "A radio input allows people to select only one option from a number of choices. Radio is generally displayed in a radio group."
directory = "components"
landingimage = "/images/components/radio.jpg"
layout = "details"
title = "Radio"
toc = true
+++

## Usage
Use the radio component to customize how you present radio buttons. For example, options listed in a table.

Use radios when:

* users have to select one or more options from a list of related items
* an explicit action is required to apply settings.

## Anatomy

<img src="/images/components/radio-anatomy.jpg" alt="Image of Radio Anatomy" class="img-fluid d-block mx-auto" />

1. **Current selection** Indicates the selected option.
2. **Option:** The selection control.
3. **Label:** Text label associated with the radio input.

## Best Practices
* List options in a logical order:
  * most likely to least likely to be selected
  * simplest to most complex operation
  * least to most risk
* Make one radio group option the default. Select the safest, most secure, and private option first. If safety and security aren’t factors, select the most likely or convenient option.
* If you need an unselected state, add a radio group with a "None" option.
* If you can't have a list of all possible options, add an "Other" option.
* Avoid putting things in alphabetical order because it is language dependent and not localizable.

## Content guidelines
* Labels should be concise and provide context.


## Examples

### Default
The default way to present a single option from a list.

In most situations where you want to present a list of mutually exclusive options, you will want to use a radio group.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <div class="custom-control custom-radio">
        <input type="radio" id="customRadio1" name="customRadio" class="custom-control-input" checked>
        <label class="custom-control-label" for="customRadio1">Radio Label</label>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="custom-control custom-radio">
        <input type="radio" id="customRadio1" name="customRadio" class="custom-control-input">
        <label class="custom-control-label" for="customRadio1">Radio Label</label>
    </div>
    {{< /highlight-code >}}
    </div>
</div>

### Radio Group
The default way to select a single option from a list.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    Choose a color:
    <div class="custom-control custom-radio">
        <input type="radio" id="chooseColorRadio1" name="chooseColor" class="custom-control-input" checked>
        <label class="custom-control-label" for="chooseColorRadio1">Red</label>
    </div>
    <div class="custom-control custom-radio">
        <input type="radio" id="chooseColorRadio2" name="chooseColor" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio2">Blue</label>
    </div>
    <div class="custom-control custom-radio">
        <input type="radio" id="chooseColorRadio3" name="chooseColor" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio3">Yellow</label>
    </div>
    <div class="custom-control custom-radio">
        <input type="radio" id="chooseColorRadio4" name="chooseColor" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio4">Green</label>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="custom-control custom-radio">
        <input type="radio" id="chooseColorRadio1" name="chooseColor" class="custom-control-input" checked>
        <label class="custom-control-label" for="chooseColorRadio1">Red</label>
    </div>
    <div class="custom-control custom-radio">
        <input type="radio" id="chooseColorRadio2" name="chooseColor" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio2">Blue</label>
    </div>
    <div class="custom-control custom-radio">
        <input type="radio" id="chooseColorRadio3" name="chooseColor" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio3">Yellow</label>
    </div>
    <div class="custom-control custom-radio">
        <input type="radio" id="chooseColorRadio4" name="chooseColor" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio4">Green</label>
    </div>
    {{< /highlight-code >}}
    </div>
</div>


### Inline Radio Group

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    Choose a color:
    <div class="custom-control custom-radio custom-control-inline">
        <input type="radio" id="chooseColorRadio5" name="chooseColor2" class="custom-control-input" checked>
        <label class="custom-control-label" for="chooseColorRadio5">Red</label>
    </div>
    <div class="custom-control custom-radio custom-control-inline">
        <input type="radio" id="chooseColorRadio6" name="chooseColor2" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio6">Blue</label>
    </div>
    <div class="custom-control custom-radio custom-control-inline">
        <input type="radio" id="chooseColorRadio7" name="chooseColor2" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio7">Yellow</label>
    </div>
    <div class="custom-control custom-radio custom-control-inline">
        <input type="radio" id="chooseColorRadio8" name="chooseColor2" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio8">Green</label>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="custom-control custom-radio custom-control-inline">
        <input type="radio" id="chooseColorRadio5" name="chooseColor2" class="custom-control-input" checked>
        <label class="custom-control-label" for="chooseColorRadio5">Red</label>
    </div>
    <div class="custom-control custom-radio custom-control-inline">
        <input type="radio" id="chooseColorRadio6" name="chooseColor2" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio6">Blue</label>
    </div>
    <div class="custom-control custom-radio custom-control-inline">
        <input type="radio" id="chooseColorRadio7" name="chooseColor2" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio7">Yellow</label>
    </div>
    <div class="custom-control custom-radio custom-control-inline">
        <input type="radio" id="chooseColorRadio8" name="chooseColor2" class="custom-control-input">
        <label class="custom-control-label" for="chooseColorRadio8">Green</label>
    </div>
    {{< /highlight-code >}}
    </div>
</div>