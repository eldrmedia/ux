+++
description = "Breadcrumbs are a navigation system used to show a user's location in a site or app."
directory = "components"
landingimage = "/images/components/breadcrumb.jpg"
layout = "details"
title = "Breadcrumb"
toc = true
+++
## Usage

Breadcrumbs are an alternative way to help users orient themselves. They're a useful addition to, but shouldn’t replace, the main navigation on a page.

Use breadcrumbs for nested navigation, with each item acting as a link. They show the hierarchical progress from the highest item level to the lowest, one step at a time. This typically starts with the product landing page and goes to the current page or content.

## Best practices

* Use breadcrumbs when the user is most likely to have landed on the page from an external source.
* Use for large websites and complex products that have hierarchically arranged pages, so that users who land on the page can quickly know where they are.
* In products, breadcrumbs can adapt to the state of navigation by being toggled on, off, or auto-collapsing.
* Make sure breadcrumbs don’t visually overwhelm the page.
* Place breadcrumbs at the top left corner of the screen, above the page title.
* In product, avoid using the topmost level of the hierarchy unless the navigation sidebar is collapsed.

## Accessibility

Make sure your breadcrumb items reflect the page or product section titles exactly for screen readers.

## Example

### Default
The default form of breadcrumbs.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <nav aria-label="breadcrumb">
      <ol class="breadcrumb breadcrumb-links">
        <li class="breadcrumb-item"><a href="#">Home</a></li>
        <li class="breadcrumb-item"><a href="#">Library</a></li>
        <li class="breadcrumb-item active" aria-current="page">Data</li>
      </ol>
    </nav>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}
    <nav aria-label="breadcrumb">
      <ol class="breadcrumb breadcrumb-links">
        <li class="breadcrumb-item"><a href="#">Home</a></li>
        <li class="breadcrumb-item"><a href="#">Library</a></li>
        <li class="breadcrumb-item active" aria-current="page">Data</li>
      </ol>
    </nav>{{< /highlight-code >}}
    </div>
</div>