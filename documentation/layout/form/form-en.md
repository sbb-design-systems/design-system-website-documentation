## 1. What does the module do?
It is used to collect, validate and send user entries.

## 2. When should the module be used?
When user data is needed, then it is a form.

## 3. Rules
* Form layout
    * If the form has its own page it always has a title and a [lead text](https://digital.sbb.ch/en/websites/basics/typography) as an option.
    * Individual form element can be combined into sections. These sections are divided by a horizontal line.
    * A section always has a title.
* Sending the form
    * Confirmation of dispatch appears after sending.
* Field validation
    * Field validation occurs when leaving an individual field.
    * Fields containing errors are immediately marked red (red frame and error message).
* Form validation
    * Is carried out if the form is sent via the ‘Submit’ button.
    * Errors in the form validation are shown with a [notification](https://digital.sbb.ch/en/websites/components/notification) (in the case of field validation errors, the [notification](https://digital.sbb.ch/en/websites/components/notification) is entered with jump markers).
* Inactive fields
    * Form fields are shown as disabled if they are still dependent on another selection. If fields can never be enabled (e.g. due to user authorisation), the field should be displayed as a label.
    * The ‘Submit’ button is always active.
* Optional entries in the form contain ‘(optional)’ in the field name.

## 4. Variants and statuses
The module has the following statuses:
* Valid
* Invalid

### 4.1 Floating layout (one field after the next with break)
* The form fields are arranged one after another with any line breaks.

### 4.2 Two-column layout