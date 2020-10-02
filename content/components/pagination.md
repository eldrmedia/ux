+++
description = "Pagination allows you to divide large amounts of content into smaller chunks across multiple pages."
directory = "components"
landingimage = "/images/components/pagination.jpg"
layout = "details"
title = "Pagination"
toc = true

+++
## Usage

Use pagination when there are too many results to show on the one page, so the user isn't overwhelmed by too much information.

Pagination is commonly used for things like table listings, search results, and directories. What constitutes “too many results” can be influenced by:

* system load times
* amount of data in each entry
* screen space

Pagination is a control that sits at the bottom of the page and allows the user to easily move between each page.

## Related
* Each page in the pagination control is a button link that allows the them to quickly navigate through the results.


## Examples

### Default

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <nav aria-label="Page navigation">
      <ul class="pagination align-items-center">
        <li class="page-item disabled"><a href="#" class="page-link" tabindex="-1" aria-disabled="true">First</a></li>
        <li class="page-item disabled"><a href="#" class="page-link" tabindex="-1" aria-disabled="true">Previous</a></li>
        <li class="page-item px-3">Page 1/68</li>
        <li class="page-item"><a href="#" class="page-link" href="#">Next</a></li>
        <li class="page-item"><a href="#" class="page-link" href="#">Last</a></li>
      </ul>
    </nav>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <nav aria-label="Page navigation">
      <ul class="pagination align-items-center">
        <li class="page-item disabled"><a href="#" class="page-link" tabindex="-1" aria-disabled="true">First</a></li>
        <li class="page-item disabled"><a href="#" class="page-link" tabindex="-1" aria-disabled="true">Previous</a></li>
        <li class="page-item px-3">Page 1/68</li>
        <li class="page-item"><a href="#" class="page-link" href="#">Next</a></li>
        <li class="page-item"><a href="#" class="page-link" href="#">Last</a></li>
      </ul>
    </nav>
    {{< /highlight-code >}}
    </div>
</div>