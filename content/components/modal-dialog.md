+++
description = "A modal dialog displays content that requires user interaction, in a layer above the page."
directory = "components"
landingimage = "/images/components/modal-dialog.jpg"
layout = "details"
title = "Modal Dialog"
toc = true

+++
## Usage

Use modal dialogs to present a short-term task the user needs to perform. This can include critical or warning information where a response is required, however they’re also intended to support efficient task completion without losing the context of the underlying page. Users won't be able to interact with the page until the dialog is closed.

In some cases, modals may contain information that requires additional help and support. Elements, such as filters or hint text, can be added to the modal dialog to help users respond with clarity and efficiency at the expense of dialog real estate.

Although highly versatile, this doesn't mean modal dialogs are fit for all purposes.


## Anatomy

<img src="/images/components/modal-dialog-anatomy.jpg" alt="Image of Modal Dialog Anatomy" class="img-fluid d-block mx-auto" />

1. **Header:** Contains the modal title.
2. **Body:** Provides an overview of the modal's purpose and, optionally, controls to complete a task.
3. **Footer:** Contains a primary action and the ability to cancel and close the dialog.


## Best Practice
* Modal dialogs are invasive and should be used sparingly. The ability of the user to access and view their own content is paramount to a good experience.
* Try to limit the number of interactions in a modal dialog. Simplify by removing unnecessary elements or content that does not support the task.
* Avoid multiple steps that require navigation within the modal dialog.
* Avoid complex decision making that requires additional sources of information unavailable in the modal.
* It's best to support multiple methods for dismissal.


## Content guidelines
* Modal dialog titles should use sentence case and prioritize keywords.
* Modal dialog body copy should contain only valuable and relevant information that is both helpful and concise.
* Label elements with action verbs that indicate what happens when the element is selected. For example, label a select menu with Choose a user instead of Users.

## Related
* Each page in the pagination control is a button link that allows the them to quickly navigate through the results.


## Examples

### Default
The default form of a modal dialog.

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <div class="modal position-relative d-block" style="height: auto;" tabindex="-1">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title">Modal title</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            <p>Modal body text goes here.</p>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-light" data-dismiss="modal">Close</button>
            <button type="button" class="btn btn-primary">Save changes</button>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <div class="modal" tabindex="-1">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title">Modal title</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            <p>Modal body text goes here.</p>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-light" data-dismiss="modal">Close</button>
            <button type="button" class="btn btn-primary">Save changes</button>
          </div>
        </div>
      </div>
    </div>
    {{< /highlight-code >}}
    </div>
</div>

### Live demo

<div class="ds-code-example">
  <div class="ds-code-example__showcase">
    <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal">
      Launch demo modal
    </button>
    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            Modal body text goes here.
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-light" data-dismiss="modal">Close</button>
            <button type="button" class="btn btn-primary">Save changes</button>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="ds-code-example__code">
    {{< highlight-code html >}}

    <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal">
      Launch demo modal
    </button>
    
    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            ...
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-light" data-dismiss="modal">Close</button>
            <button type="button" class="btn btn-primary">Save changes</button>
          </div>
        </div>
      </div>
    </div>
    {{< /highlight-code >}}
    </div>
</div>




## Appearance
A modal dialog is available in two other variations. The appearance of the primary action and icon will change per variation. See utility, Sweet Alerts for more information.
