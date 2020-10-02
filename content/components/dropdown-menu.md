+++
description = "A dropdown menu displays a list of actions or options to a user."
directory = "components"
landingimage = "/images/components/dropdown-menu.jpg"
layout = "details"
title = "Dropdown Menu"
toc = true

+++
## Usage
Dropdown menus are typically used when you have 5-15 items to choose from. They're used for navigation or command menus, where an action is initiated based on the selection.

Menu items can include both radio buttons and checkboxes.

A "more" menu, where the control contains an icon.


## Anatomy

<img src="/images/components/dropdown-menu-anatomy.jpg" alt="Image of Dropdown Menu Anatomy" class="img-fluid d-block mx-auto" />

1. **Control:** A button that may contain an icon, or be labeled with text.
2. **Trigger:** Used if the button is labeled with text.
3. **Menu:** Container for links and action items.


## Behavior

In cases where a menu item is longer than the button's text label, the menu will grow to the width of the longest item listed. However, there is a maximum width specified by the component. If the menu item exceeds the maximum width it will be truncated.


## Best Practices
* A number of components can be used to give people the ability to select options. See the list of related components below for advice on choosing the right one.
* When organizing dropdown menu items, sort the list in a logical order by putting the most selected option at the top, if known. Test and refine over time to re-evaluate if all menu items are needed.
* For long lists, group related menu items. If including radio buttons and checkboxes as menu items, try grouping related actions.
* Grouped items are separated by a short, uppercase title that describes the options in that sub-category.

1. Groupe Title (not selectable)
2. Grouped menu items


## Content guidelines
* People navigate menus and choose menu items based on their labels, so it’s important that they're accurate and informative.
* In general, use sentence case and write concise labels that clearly indicate the purpose of the selection.
* For action menu items, use verbs and verb phrases to describe the action that occurs when the item is chosen. For example, “Add”, “Delete”, or “Convert”.
* In most cases, links should be nouns. For example, Profile or Keyboard shortcuts.
* Exclude articles in menu items. For example, use "Add flag" instead of "Add a flag".
* Keep menu items to a single line of text.


## Related
* To allow users to search and select one or more options from a list, use the select component.
* To collect user input from a related list of items use [checkboxes](/components/checkbox/).
* To allow users to make a single selection from a short list, use [radio buttons](/components/radio-button/).


## Examples

### Default

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <div class="dropdown">
        <button class="btn btn-primary dropdown-toggle" type="button" id="dropdownMenuButton1" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Dropdown Menu
        </button>
        <div class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
            <a class="dropdown-item" href="#">Game Settings</a>
            <a class="dropdown-item" href="#">API Scripts</a>
            <a class="dropdown-item" href="#">Convert Lighting</a>
            <a class="dropdown-item" href="#">Copy Game</a>
        </div>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="dropdown">
        <button class="btn btn-primary dropdown-toggle" type="button" id="dropdownMenuButton1" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Dropdown button
        </button>
        <div class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
            <a class="dropdown-item" href="#">Game Settings</a>
            <a class="dropdown-item" href="#">API Scripts</a>
            <a class="dropdown-item" href="#">Convert Lighting</a>
            <a class="dropdown-item" href="#">Copy Game</a>
        </div>
    </div>
    {{< /highlight-code >}}
    </div>
</div>
