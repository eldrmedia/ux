+++
description = "A text field is an input that allows a user to write or edit text."
directory = "components"
landingimage = "/images/components/text-field.jpg"
layout = "details"
title = "Text Field"
toc = true
+++

## Usage
Use text fields in [forms](/patterns/forms/) to help people enter, select, and search for text. Text fields are normally found within a form but can also be part of a modal, search, or card.

Common text input types include: usernames, descriptions, URLs, emails, addresses, and plain text searches.


## Anatomy

<img src="/images/components/text-field-anatomy.jpg" alt="Image of Text Field Anatomy" class="img-fluid d-block mx-auto" />

1. **Label:** Should indicate what sort of information the field requires and is left-aligned directly above the input area.
2. **Placeholder text:** Lets people know how they should use the field, for example, “Start typing to see names.”
3. **Input area:** This is where people enter text.
4. **Helper text:** Gives context about a field's input.


## Best Practices
* Only supply placeholder text where clarification is required, try not to overuse it.
* Place labels directly above the input, and align to the left.


## Content guidelines
* For helper text provide an example or specific syntax for the input, rather than in the input area, so that it's visible after text has been entered. Only use this where clarification is required, and try not to overuse it.
* Field label text above the input area should be short and concise.


## Related
* Text fields are commonly used in [forms](/patterns/forms/).


## Examples

### Default
The default form of a text field.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <input type="text" class="form-control" placeholder="Default input">
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}
    <input type="text" class="form-control" placeholder="Default input">
    {{< /highlight-code >}}
    </div>
</div>


### Form
Text field used in forms.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <label for="formInput1">Username</label>
    <input type="text" class="form-control" id="formInput1" placeholder="Username">
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}
    <label for="formInput1">Username</label>
    <input type="text" class="form-control" id="formInput1" placeholder="Username">
    {{< /highlight-code >}}
    </div>
</div>


### Validation
Validation can display an error message related to the restrictions of the field. Keep this text as short as possible.

<div class="ds-code-example">
    <div class="ds-code-example__showcase">
        <label for="validatedInput1">Username</label>
        <input type="text" class="form-control is-invalid" id="validatedInput1" placeholder="" required>
        <div class="invalid-feedback">
            <i class="fa fa-exclamation-circle fa-sm"></i> Please provide a username.
        </div>
    </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}
    <label for="validatedInput1">Username</label>
    <input type="text" class="form-control is-invalid" id="validatedInput1" placeholder="" required>
    <div class="invalid-feedback">
        <i class="fa fa-exclamation-circle fa-sm"></i> Please provide a username.
    </div>
    {{< /highlight-code >}}
    </div>
</div>


### Disabled

<div class="ds-code-example">
    <div class="ds-code-example__showcase">
        <input type="text" class="form-control" placeholder="Disabled" disabled>
    </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}
      <input type="text" class="form-control" placeholder="Disabled" disabled>
    {{< /highlight-code >}}
    </div>
</div>