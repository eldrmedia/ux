+++
description = "A button triggers an event or action. They let users know what will happen next."
directory = "components"
landingimage = "/images/components/button.jpg"
layout = "details"
title = "Button"
toc = true
+++
## Usage

Buttons are triggers for events or actions. They’re commonly used as part of larger components or patterns such as [forms](/patterns/forms) or [modal dialogs](/components/modal-dialog).

Buttons:

* move users through a sequence of screens
* act as calls to action (CTAs)
* with an icon to convey meaning quicker
* with a badge indicate a value

## Anatomy

<img src="/images/components/button-anatomy.jpg" alt="Image of Avatar Anatomy" class="img-fluid d-block mx-auto" />

1. **Icon:** Use an icon to convey more meaning.
2. **Label:** Text that indicates the result of selecting the button.

## Best practices

* Use a primary button to indicate the main action of a group button set.
* Subtle or secondary buttons should use a less dominant color.
* Button size matters - make sure the size of the button is large enough to interact with on web or other device but not too large so as to be visually overwhelming.
* Use action verbs or phrases to tell the user what will happen next.

## Alignment
* Right align the primary button to visually support navigation when using buttons to prompt a user to move through a sequence of screens (e.g. getting started guides).
* Center align buttons for modals, with the primary button on the right.
* Left align buttons for single-page forms and focused tasks, and sort by importance from left to right.


## Appearance

### Default

The default form of a button, used for most cases. They are not impactful enough to represent the primary action in a container. Therefore should **not** be used.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button class="btn">Default Button</button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

      <button class="btn">Button Example</button>
    {{< /highlight-code >}}
    </div>
</div>


### Primary
Use a Primary `.btn-primary` button to call attention to an action on a form or to highlight the strongest call to action on a page. Primary buttons should only appear once per container (not including the application header or in a modal dialog). Not every screen requires a primary button.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button class="btn btn-primary">Primary Button</button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

      <button class="btn btn-primary">Primary Button</button>
    {{< /highlight-code >}}
    </div>
</div>


### Subtle/Light
Use a Subtle `.btn-light` button with a Primary `.btn-primary` button for secondary actions, such as "Cancel".

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button class="btn btn-light">Subtle Button</button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

      <button class="btn btn-light">Subtle Button</button>
    {{< /highlight-code >}}
    </div>
</div>


### Warning
A Warning `.btn-warning` button appears before we request the user to take action, usually in anticipation of a significant change.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button class="btn btn-warning">Warning Button</button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html>}}

      <button class="btn btn-warning">Warning Button</button>
    {{< /highlight-code >}}
    </div>
</div>


### Danger
The Danger `.btn-danger` button appears as a final confirmation for a destructive action such as deleting. These are found mostly in confirmation modals.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button class="btn btn-danger">Danger Button</button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

      <button class="btn btn-danger">Danger Button</button>
    {{< /highlight-code >}}
    </div>
</div>


## States
### Disabled

Set `.disabled` to disable a button when another action has to be completed before the button is usable, such as changing a text field value or waiting for a system response.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button class="btn btn-primary" disabled>Disabled Button</button>
    <a href="#" class="btn btn-primary disabled" tabindex="-1" role="button" aria-disabled="true">Disabled Anchor Button</a>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

      <button class="btn btn-primary btn-disabled">Disabled Button</button>
      <a href="#" class="btn btn-primary disabled" tabindex="-1" role="button" aria-disabled="true">Disabled Anchor Button</a>
    {{< /highlight-code >}}
    </div>
</div>


### Loading
Use spinners within buttons to indicate an action is currently processing or taking place. You may also swap the text out of the spinner element and utilize button text as needed. Learn more about the [spinner](/components/spinner/) and its uses.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button class="btn btn-primary" type="button" disabled>
        <span class="spinner-border spinner-border-sm" role="status" aria-hidden="true"></span>
        Loading...
    </button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <button class="btn btn-primary" type="button" disabled>
        <span class="spinner-border spinner-border-sm" role="status" aria-hidden="true"></span>
        Loading...
    </button>
    {{< /highlight-code >}}
    </div>
</div>


### Full width
Buttons can be expanded to full width to fill its parent container.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button class="btn btn-primary btn-block">Button Block</button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

      <button class="btn btn-primary btn-block">Button Block</button>
    {{< /highlight-code >}}
    </div>
</div>


## Button with icon
Buttons may include an icon before or after the text.

### Icon Before
<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button type="button" class="btn btn-primary btn-icon">
        <span class="btn-inner--icon">
            <i class="far fa-pencil"></i>
        </span>
        <span class="btn-inner--text">Edit Profile</span>
    </button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

      <button type="button" class="btn btn-primary btn-icon">
          <span class="btn-inner--icon">
              <i class="far fa-pencil"></i>
          </span>
          <span class="btn-inner--text">Edit Profile</span>
      </button>
    {{< /highlight-code >}}
    </div>
</div>

### Icon After
<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button type="button" class="btn btn-primary btn-icon">
        <span class="btn-inner--text">Edit Profile</span>
        <span class="btn-inner--icon">
            <i class="far fa-pencil"></i>
        </span>
    </button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

      <button type="button" class="btn btn-primary btn-icon">
          <span class="btn-inner--text">Edit Profile</span>
          <span class="btn-inner--icon">
              <i class="far fa-pencil"></i>
          </span>
      </button>
    {{< /highlight-code >}}
    </div>
</div>