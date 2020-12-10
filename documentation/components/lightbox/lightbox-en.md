## 1. What does the component do?
It is used to display detailed information of a content page.

## 2. When should the component be used?
* If detailed or additional information has to be shown on-demand on part of a page (for example, additional support when the [tooltip](https://digital.sbb.ch/en/websites/components/tooltip) is not sufficient).
* To display the editing mode on forms.
* For an enlarged view of images.

## 3. Rules
* The referenced page is not left.
* When the lightbox opens, it always fills the browser window.
* The lightbox has its own header which is always sticky.
* Only content-describing information may appear in the header (for example, the train number).
* The lightbox content can be created as part of basic design.

## 4. Variants and statuses
### 4.1 Standard
![Image of the lightbox component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/lightbox/images/lightbox_default.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/QJ1g5b#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/lightbox)

### 4.2 With form components
![Image of the lightbox component with form components](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/lightbox/images/lightbox_form.png 'class: image')
* A lightbox with form elements contains at least a ‘cancel’ and an ‘apply’ button.
* The ‘cancel’ button closes the lightbox again.
* If the lightbox is closed (‘cancel’ or X-button) when existing entries in the form have been changed, a warning message appears indicating that the form contains unsaved data.
* The buttons of a form (‘cancel’, ‘apply’, other functions) may be inserted in the footer. * The footer is always sticky and is displayed across the entire width of the lightbox (the same as the header).

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/xDQ8a0#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/lightbox)