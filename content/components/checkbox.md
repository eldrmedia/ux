+++
description = "A checkbox is an input control that allows a user to select one or more options from a number of choices."
directory = "components"
landingimage = "/images/components/checkbox.jpg"
layout = "details"
title = "Checkbox"
toc = true
+++

## Usage
Primarily for use in forms, checkboxes are used to collect input from users. Users can select a number of options ranging from zero to multiple options.

Use checkboxes when:

* users have to select one or more options from a list of related items
* an explicit action is required to apply settings.

## Anatomy

<img src="/images/components/checkbox-anatomy.jpg" alt="Image of Checkbox Anatomy" class="img-fluid d-block mx-auto" />

1. **Checkbox:** The selection control.
2. **Checkbox label:** Text label associated with the checkbox.

## Content guidelines
* Keep checkbox labels short and descriptive.
* Start all checkbox labels with a capital letter.
* Don't include punctuation after checkbox labels.

## Related
* To display a list of options where people can only make a single selection, use [radio buttons](/components/radio-button/).
* For a more compact way of displaying options, where people can only make a single selection, use a [dropdown menu](/components/dropdown-menu/).
* To allow people to turn an option on or off, use a [toggle](/components/toggle/).

## Examples

### Default
By default, a checkbox input includes a selected and unselected state.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <div class="custom-control custom-checkbox">
        <input type="checkbox" class="custom-control-input" id="customCheck1" checked>
        <label class="custom-control-label" for="customCheck1">Checkbox Label</label>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="custom-control custom-checkbox">
      <input type="checkbox" class="custom-control-input" id="customCheck1">
      <label class="custom-control-label" for="customCheck1">Checkbox Label</label>
    </div>
    {{< /highlight-code >}}
    </div>
</div>


### Disabled
Set `disabled` to disable a checkbox when another action has to be completed before the checkbox is usable.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <div class="custom-control custom-checkbox">
        <input type="checkbox" class="custom-control-input" id="customCheck2" disabled>
        <label class="custom-control-label" for="customCheck2">Checkbox Label</label>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="custom-control custom-checkbox">
      <input type="checkbox" class="custom-control-input" id="customCheck2" disabled>
      <label class="custom-control-label" for="customCheck2">Checkbox Label</label>
    </div>
    {{< /highlight-code >}}
    </div>
</div>