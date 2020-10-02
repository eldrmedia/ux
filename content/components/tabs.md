+++
description = "Tabs are used to organize content by grouping similar information on the same page."
directory = "components"
landingimage = "/images/components/tabs.jpg"
layout = "details"
title = "Tabs"
toc = true
+++

## Usage
Tabs are an easy way to organize content by grouping similar information on the same page. This allows content to be viewed without having to navigate away from that page.

## Anatomy

<img src="/images/components/tabs-anatomy.jpg" alt="Image of Tabs Anatomy" class="img-fluid d-block mx-auto" />

1. **Selected** The active tab.
2. **Unselected:** The other available tabs.
3. **Divider:** Separates the tab navigation and content.

## Behavior
Tab behavior during standard, focus, hover, and active states are important because it lets users know where they are in the experience.

1. **Standard:** The default view.
2. **Focus:** Keyboard focus on a tab.
3. **Hover:** Hovering over a tab.
4. **Active:** Indicates the page that the user is viewing.


## Content guidelines
Tab labels provide clear and concise explanations of the content within. Each tab's content is independently categorized and mutually exclusive of the content of other tabs.

<img src="/images/components/tabs-content-guidelines.jpg" alt="Image of Tabs Content Guidelines" class="img-fluid d-block mx-auto" />


## Examples

### Default
The default form of tabs.

<div class="ds-code-example">
  <div class="ds-code-example__showcase bg-white">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
            <li class="nav-item" role="presentation">
                <a class="nav-link active" id="tab1-tab" data-toggle="tab" href="#tab1" role="tab" aria-controls="tab 1" aria-selected="true">Tab 1</a>
            </li>
            <li class="nav-item" role="presentation">
                <a class="nav-link" id="tab2-tab" data-toggle="tab" href="#tab2" role="tab" aria-controls="tab 2" aria-selected="false">Tab 2</a>
            </li>
            <li class="nav-item" role="presentation">
                <a class="nav-link" id="tab3-tab" data-toggle="tab" href="#tab3" role="tab" aria-controls="tab 3" aria-selected="false">Tab 3</a>
            </li>
        </ul>
        <div class="tab-content" id="myTabContent">
            <div class="tab-pane fade show active text-center" id="tab1" role="tabpanel" aria-labelledby="tab1-tab"><span class="h2 py-6 d-block bg-gray-100">Content for Tab 1</span></div>
            <div class="tab-pane fade text-center" id="tab2" role="tabpanel" aria-labelledby="tab2-tab"><span class="h2 py-6 d-block bg-gray-100">Content for Tab 2</span></div>
            <div class="tab-pane fade text-center" id="tab3" role="tabpanel" aria-labelledby="tab3-tab"><span class="h2 py-6 d-block bg-gray-100">Content for Tab 3</span></div>
        </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <ul class="nav nav-tabs" id="myTab" role="tablist">
        <li class="nav-item" role="presentation">
            <a class="nav-link active" id="tab1-tab" data-toggle="tab" href="#tab1" role="tab" aria-controls="tab 1" aria-selected="true">Tab 1</a>
        </li>
        <li class="nav-item" role="presentation">
            <a class="nav-link" id="tab2-tab" data-toggle="tab" href="#tab2" role="tab" aria-controls="tab 2" aria-selected="false">Tab 2</a>
        </li>
        <li class="nav-item" role="presentation">
            <a class="nav-link" id="tab3-tab" data-toggle="tab" href="#tab3" role="tab" aria-controls="tab 3" aria-selected="false">Tab 3</a>
        </li>
    </ul>
    <div class="tab-content" id="myTabContent">
        <div class="tab-pane fade show active" id="tab1" role="tabpanel" aria-labelledby="tab1-tab">Content for Tab 1</div>
        <div class="tab-pane fade" id="tab2" role="tabpanel" aria-labelledby="tab2-tab">Content for Tab 2</div>
        <div class="tab-pane fade" id="tab3" role="tabpanel" aria-labelledby="tab3-tab">Content for Tab 3</div>
    </div>
    {{< /highlight-code >}}
    </div>
</div>