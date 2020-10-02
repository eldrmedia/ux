+++
description = "A spinner is an animated spinning icon that lets users know content is being loaded."
directory = "components"
landingimage = "/images/components/spinner.jpg"
layout = "details"
title = "Spinner"
toc = true

+++
## Usage

Spinners indicate that a system process is going on that will end with content being displayed to the user. They animate as soon as user action is initiated and disappear once the content appears.

## Best practices

* If a spinner is triggered by a button, place the spinner in the button, and disable the button while the spinner is visible.
* If only a portion of a page is displaying new content or being updated, place the spinner in that part of the page.
* If you are unsure where to place the spinner, place it where you want the user's attention to be when loading is finished.
* Only show a spinner if the expected wait time is more than a second.
* There should only be a single spinner on a page at one time.


## Examples

### Default

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <div class="spinner-border text-primary" role="status">
        <span class="sr-only">Loading...</span>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="spinner-border text-primary" role="status">
        <span class="sr-only">Loading...</span>
    </div>
    {{< /highlight-code >}}
    </div>
</div>


### Sizes

#### Small
Use within elements such as buttons or form fields, or when there are other space constraints.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
        <div class="spinner-border spinner-border-sm text-primary" role="status">
            <span class="sr-only">Loading...</span>
        </div>
    </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="spinner-border spinner-border-sm text-primary" role="status">
        <span class="sr-only">Loading...</span>
    </div>
    {{< /highlight-code >}}
    </div>
</div>

#### Medium
The default size which is used for most use cases.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
        <div class="spinner-border text-primary" role="status">
            <span class="sr-only">Loading...</span>
        </div>
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


### Alignment
Spinners use `rems`, `currentColor`, and `display: inline-flex`. This means they can easily be resized, recolored, and quickly aligned.

#### Flex
Use [flexbox utilities](https://getbootstrap.com/docs/4.3/utilities/flex/) to place spinners exactly where you need them in any situation.


<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <div class="d-flex justify-content-center">
        <div class="spinner-border text-primary" role="status">
            <span class="sr-only">Loading...</span>
        </div>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="d-flex justify-content-center">
        <div class="spinner-border text-primary" role="status">
            <span class="sr-only">Loading...</span>
        </div>
    </div>
    {{< /highlight-code >}}
    </div>
</div>


### Buttons
Use spinners within buttons to indicate an action is currently processing or taking place. You may also swap the text out of the spinner element and utilize button text as needed.

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