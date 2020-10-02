+++
description = "An inline dialog is a pop-up container for small amounts of information. It can also contain controls."
directory = "components"
landingimage = "/images/components/inline-dialog.jpg"
layout = "details"
title = "Inline Dialog"
toc = true

+++
## Usage

Inline dialogs are displayed when triggered by a user action, usually by clicking a button.

Menu items can include both radio buttons and checkboxes.

Some other uses for dropdown menus:

<img src="/images/components/inline-dialog-anatomy.jpg" alt="Image of Inline Dialog Anatomy" class="img-fluid d-block mx-auto" />

A "more" menu, where the control contains an icon.


## Best practices

* Inline dialogs should be used when sections within the page require further information or actions, but are not crucial to the page as a whole.
* Inline dialogs should be concise to get the point across as quickly as possible. This is a focused component, so only one dialog can be open at a time.
* A great use for inline dialogs is feature discovery.

## Content guidelines

Text in an inline dialog should be concise to get the point across as quickly as possible.

## Related

* To allow users to search and select one or more options from a list, use the select component.
* To collect user input from a related list of items use [checkboxes](/components/checkbox/).
* To allow users to make a single selection from a short list, use [radio buttons](/components/radio-button/).

## Examples

### Default
Inline dialogs are displayed when triggered by a user action, usually by clicking a button.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="top" data-content="Hello!">
        Click Me
    </button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <button type="button" class="btn btn-dark" data-container="body" data-toggle="popover" data-placement="top" data-content="Hello!">
        Click Me
    </button>
    {{< /highlight-code >}}
    </div>
</div>


### Positioning
Inline dialogs can appear at the top, bottom, left or right of the trigger location. The location of the dialog can be placed in context with the content on the page.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="top" data-content="This is a very beautiful popover, show some love.">
        Popover on top
    </button>
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="right" data-content="This is a very beautiful popover, show some love.">
        Popover on right
    </button>
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="bottom" data-content="This is a very beautiful popover, show some love.">
        Popover on bottom
    </button>
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="left" data-content="This is a very beautiful popover, show some love.">
        Popover on left
    </button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="top" data-content="This is a very beautiful popover, show some love.">
        Popover on top
    </button>
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="right" data-content="This is a very beautiful popover, show some love.">
        Popover on right
    </button>
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="bottom" data-content="This is a very beautiful popover, show some love.">
        Popover on bottom
    </button>
    <button type="button" class="btn btn-primary" data-container="body" data-toggle="popover" data-placement="left" data-content="This is a very beautiful popover, show some love.">
        Popover on left
    </button>
    {{< /highlight-code >}}
    </div>
</div>