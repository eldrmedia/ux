+++
description = "An avatar is a visual representation of a user or entity."
directory = "components"
landingimage = "/images/components/avatar.jpg"
layout = "details"
title = "Avatar"
toc = true
+++
## Usage

An avatar acts as a proxy for a user or entity (such as a game or group listing). They're often combined with status or presence indicators to give more context. Users generally upload their own image, otherwise, a default image or text is displayed.

Use:
* circular avatars to quickly identify users
* square avatars to help identify large product entities like games, listings, groups, etc.
* a presence indicator to indicate presence for a single user
* a status icon to indicate a user’s status in a product


## Anatomy

<img src="/images/components/avatar-anatomy.jpg" alt="Image of Avatar Anatomy" class="img-fluid d-block mx-auto" />

1. **Body:** The image representing the user or entity.
2. **Status:** An icon that displays the avatar’s status.

## Best practices

Check you’re using the appropriately sized shape and sized avatar for your use case.

## Accessibility
Write an alt text equivalent for your avatar for screen readers.


## Examples

### Default
A circular avatar is used to represent a person

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <img alt="Avatar Image" src="/images/components/avatar-example.png" class="avatar rounded-circle" />
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <img alt="Avatar Image" src="/images/components/avatar-example.png" class="avatar rounded-circle" />
    {{< /highlight-code >}}
    </div>
</div>

## Size

### Large
Use large avatars where they’re needed to display prominently on a page.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <img alt="Avatar Image" src="/images/components/avatar-example.png" class="avatar avatar-lg rounded-circle" />
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <img alt="Avatar Image" src="/images/components/avatar-example.png" class="avatar avatar-lg" />
    {{< /highlight-code >}}
    </div>
</div>

### Medium

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <img alt="Avatar Image" src="/images/components/avatar-example.png" class="avatar rounded-circle" />
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <img alt="Avatar Image" src="/images/components/avatar-example.png" class="avatar" />
    {{< /highlight-code >}}
    </div>
</div>

### Small
Use small avatars in area with limited space but need to display entities (games or token markers).

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <img alt="Avatar Image" src="/images/components/avatar-example.png" class="avatar avatar-sm rounded-circle" />
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <img alt="Avatar Image" src="/images/components/avatar-example.png" class="avatar avatar-sm rounded-circle" />
    {{< /highlight-code >}}
    </div>
</div>


## Text

### Primary Text
Text can be added to the right of the avatar.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <div class="d-flex flex-row align-items-center">
      <img alt="Avatar Image" src="/images/components/avatar-example.png" class="avatar rounded-circle" />
      <div class="ml-2">
        <span class="h6">Khloe Waters</span>
      </div>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="d-flex flex-row align-items-center">
      <img alt="Avatar Image" src="/images/components/avatar-example.png" class="avatar rounded-circle" />
      <div class="ml-2">
        <span class="h6">Khloe Waters</span>
      </div>
    </div>
    {{< /highlight-code >}}
    </div>
</div>