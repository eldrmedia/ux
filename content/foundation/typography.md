+++
layout = "details"
title = "Typography"
description = "Typography is our system of fonts. Each font conveys the appropriate sentiment to assist our users through each stage of their journey."
directory = "foundation"
toc = true
+++

## Brand Typography
We use the font, Nunito, for almost everything brand and marketing—from banner ads to social media assets. It was chosen because we found it to be incredibly versatile with lots of range in terms of tone and playfulness. It can be quirky and expressive when it needs to be, or neutral when the situation calls for something a bit more serious.

There are also uses where the Chalet family looks better. When using Chalet, please make sure you are using a Nineteen-Sixty version. This is set in London Nineteen-Sixty. The Paris and London version are also acceptable, but please ensure it’s the Nineteen-Sixty versions. They just look better.

{{< callout warning >}}
Previous versions of the brand used the more rounded versions of the Chalet family. These should not be used going forward. If necessary, a Helvetica-ish font can be used, but Chalet is preferred. Tracking is set at 5.
{{< /callout >}}

## Usage

Keeping typography consistent and sticking to logical hierarchies ensures that elements in the UI are clear and easily recognizable when scanning the page. Text sizes, styles, and layouts were selected to balance content and UI and to foster familiarity.

### Headings
All HTML headings, `<h1>` through `<h6>`, are available.

<table class="table">
  <thead>
    <tr>
      <th>Heading</th>
      <th>Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        {{< markdown >}}`<h1></h1>`{{< /markdown >}}
      </td>
      <td><span class="h1">h1. Bootstrap heading</span></td>
    </tr>
    <tr>
      <td>
        {{< markdown >}}`<h2></h2>`{{< /markdown >}}
      </td>
      <td><span class="h2">h2. Bootstrap heading</span></td>
    </tr>
    <tr>
      <td>
        {{< markdown >}}`<h3></h3>`{{< /markdown >}}
      </td>
      <td><span class="h3">h3. Bootstrap heading</span></td>
    </tr>
    <tr>
      <td>
        {{< markdown >}}`<h4></h4>`{{< /markdown >}}
      </td>
      <td><span class="h4">h4. Bootstrap heading</span></td>
    </tr>
    <tr>
      <td>
        {{< markdown >}}`<h5></h5>`{{< /markdown >}}
      </td>
      <td><span class="h5">h5. Bootstrap heading</span></td>
    </tr>
    <tr>
      <td>
        {{< markdown >}}`<h6></h6>`{{< /markdown >}}
      </td>
      <td><span class="h6">h6. Bootstrap heading</span></td>
    </tr>
  </tbody>
</table>


### Formatting

<table class="table">
    <thead>
        <tr>
            <th width="18%">Style</th>
            <th width="18%">Size</th>
            <th>Content</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>Bold</strong></td>
            <td>16px (1rem)</td>
            <td>Use {{< markdown >}}`<strong>`{{< /markdown >}} to <strong>emphasize text.</strong></td>
        </tr>
        <tr>
            <td><em>Italics</em></td>
            <td>16px (1rem)</td>
            <td>Use {{< markdown >}}`<em>`{{< /markdown >}} to italicize text.</td>
        </tr>
        <tr>
            <td><small>Small</small></td>
            <td>12px (0.75rem)</td>
            <td>Use {{< markdown >}}`<small>`{{< /markdown >}}  primarily on help text under form fields, and as secondary supporting text in applications. It should be used sparingly.</td>
        </tr>
    </tbody>
</table>