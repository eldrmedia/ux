+++
description = "Accessible design lets people of all abilities interact with, understand, and navigate our products."
directory = "foundation"
layout = "details"
title = "Accessibility"
toc = true

+++
<p class="lead">Products and web properties should be accessible to everyone, including those with vision, hearing, cognitive, or motor impairments.</p>

Keep in mind that:

* Accessibility is about having a good understanding of our user's journeys and proactively anticipating their needs.
* Accessible design is everyone's responsibility, from information and user experience design, through to development, and on into help and support.

## Structure and hierarchy

Consistent, clear hierarchy helps people who navigate the page using links or headers. Use headings and titles to outline the page so people can see the structure and how sections relate. Give people feedback so they know where they are in the application.

### Have a consistent hierarchy

Create and maintain a consistent hierarchy so that people can use alternative input methods to move through the page. Headings are in order without skipping levels.

{{< do-dont
    do-html="<h1>, <h2>, <h3>, <h4>"
    do-description="Use a consistent heading hierarchy."

    dont-html="<h2>, <h1>, <h3>, <h3>"
    dont-description="Use headings out of order."
>}}

### Text scaling

Test the UI with color correction, magnification, and other accessibility settings to ensure the layout works with assistive settings.

### Group similar items

Group items under titles or headings that clearly communicate the content of the group.

{{< do-dont
    do-description="Clear title with related items: Fruit - wildberry, strawberry, blueberries."

    dont-description="Vague category with unrelated items: Things - rocket, fuel, bring home milk."
>}}


## Keyboard navigation

Some people can't use a mouse and navigate through applications using tools such as a keyboard, mouth wand, or eye tracking system. People should be able to navigate and use the product with a keyboard or screenreader. Make sure anything that can be seen by hovering with a mouse is also accessible to keyboard focus and screen readers.

When creating an application, check if a keyboard can be used to:

* navigate
* perform the same tasks as people who use a mouse
* locate where you are on the page
* tell where the keyboard focus is

### Use tooltips

Tooltips can be activated by keyboard. When an element gets keyboard focus, a tooltip displays. When that element loses focus, the tooltip disappears.

### Validate forms inline

Validate forms inline so keyboard users don't have to navigate far to get feedback.

## Meaningful text

Consistent and helpful text makes the user interface accessible to people who use a screen reader. Screen readers help people with visual impairments by reading both visible and non-visible alternative text aloud.

All text should support accessibility, whether it's visible (UI labels, headings, buttons, forms, hyperlinks, and help text) or non-visible (alternative text for images and buttons).

### Be concise

Keep content and accessibility text concise. People using screen readers hear every UI element read aloud, so the shorter the text, the faster they can navigate the content.

### Use consistent labels

Consistently label elements and components that have the same functionality. When people encounter these elements in different contexts, they should be able to recognize and understand the function or actions of an element. For instance, a menu item that is labelled All sprints should open a page that is titled All sprints. A dialogue with the title Copy page has a button labeled Copy.

{{< do-dont
    do-description="Copy game, save changes"

    dont-description="Clone game, save changes"
>}}

### Describe what an element does

Label elements with action verbs that indicate what happens when the element is selected.

{{< do-dont
    do-description="Edit account - When read aloud, the text indicates the action."

    dont-description="Preferences - Just labeling the element doesn't make it clear what will happen when it is selected."
>}}

### Buttons

In buttons, describe what the action does and, if you can, reveal what will happen.

{{< do-dont
    do-description="Add room"

    dont-description="Go for it!"
>}}

### Hyperlinks

Link text should indicate where the link navigates to.

## Colors

We comply with [AA standard contrast ratios](https://webaim.org/resources/contrastchecker/). To do this, we choose primary, secondary and extended colors that support usability. This ensures sufficient color contrast between elements so that people with low vision can see and use our products.

### Include visual cues

Don't convey information using color alone. Use multiple visual cues, such as stroke weight, patterns, shape, text, or illustrations to ensure that everyone receives the same information. This helps people who are unable to, or have difficulty with, distinguishing one color from another. This includes people who are color blind, have low vision, or are blind.

For example, these inline validation messages use both color and icons to distinguish severity:

### Use high contrast

High color contrast helps people who are partially or completely color blind see differences between certain colors. It creates a strong visual hierarchy and improves usability for everyone. Make sure that the combination of text and background color do not fall below the WCAG recommended threshold ratio of 4.5:1 for standard text and 3:1 for larger text.

Decorative images and disabled states don't have contrast requirements.

## Testing and research

These guidelines will help improve accessibility in your applications, but they don't guarantee a fully accessible experience. We also recommend you:

* Test the entire application and journeys using various assistive technologies and text scaling.
* Include people with impairments when testing.
* Ensure that the tasks in your applications can be accomplished by anyone, regardless of ability.

When in doubt, refer to the following guidelines:

* [WebAIM](https://webaim.org/)
* [Web Accessibility Initiative](https://www.w3.org/)