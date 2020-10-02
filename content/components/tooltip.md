+++
description = "A tooltip is a floating, non-actionable label used to explain a user interface element or feature."
directory = "components"
landingimage = "/images/components/tooltip.jpg"
layout = "details"
title = "Tooltip"
toc = true
+++

## Usage
Use tooltips to identify or add a small amount of information to an element. Typically, tooltips are used to:

* help users understand the meaning or purpose of icons
* show the full version of truncated text
* display the alternative text for an image

Tooltips replace standard browser tooltips when more emphasis is required. Tooltips do not receive input focus.


## Best Practices
* Tooltips should only appear when the user has paused on the target element. They should remain visible if the user briefly moves the mouse off and back on to the target.
* Tooltips should not immediately disappear, unless the user hovers over another element with a tooltip.
* When the user scrolls, their attention is no longer on the tooltip. We take this opportunity to immediately hide the tooltip.


## Behavior
The position of tooltips is flexible and will change depending on how close the element is to the edge of the screen.

## Markup
The required markup for a tooltip is only a `data` attribute and `title` on the HTML element you wish to have a tooltip. The generated markup of a tooltip is rather simple, though it does require a position (by default, set to `top` by the plugin).

## Content guidelines
* When writing tooltips, be short and concise.


## Related
* When you need to add more than a single line of extra information, use an [inline dialog](/components/inline-dialog/).
* Use with [toggles](/components/switch/) to describe what happens when switched on or off.


## Examples

### Default

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="top" title="Tooltip on top">
      Tooltip on top
    </button>
    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="right" title="Tooltip on right">
      Tooltip on right
    </button>
    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="bottom" title="Tooltip on bottom">
      Tooltip on bottom
    </button>
    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="left" title="Tooltip on left">
      Tooltip on left
    </button>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="top" title="Tooltip on top">
      Tooltip on top
    </button>
    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="right" title="Tooltip on right">
      Tooltip on right
    </button>
    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="bottom" title="Tooltip on bottom">
      Tooltip on bottom
    </button>
    <button type="button" class="btn btn-primary" data-toggle="tooltip" data-placement="left" title="Tooltip on left">
      Tooltip on left
    </button>
    {{< /highlight-code >}}
    </div>
</div>