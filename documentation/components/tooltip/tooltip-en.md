## 1. What does the component do?
It allows the user to show explanations if required.

## 2. When should the component be used?
For context-specific explanations on interaction elements or text.

## 3. Rules
* The tooltip consists of an icon and the overlay → in exceptional circumstances, another icon can be used for the tooltip (e.g. info icon).
* The overlay opens when the ??? is clicked on.
* Only free text and [links](https://digital.sbb.ch/en/websites/components/link) may be used in the overlay. The text may also be displayed as a list.
* The tooltip text can have a maximum of 300 characters.
* A link may open content in a [lightbox](https://digital.sbb.ch/en/websites/components/lightbox) or on a new page (new tab). It cannot be loaded in the current browser window.
* The overlay contains a ??? to close the overlay.
* The overlay can also be hidden again by clicking anywhere next to the overlay.
* The pointer of the overlay, which points to the icon, can be positioned anywhere horizontally (depends on the position of the tooltip on the page).

## 4. Variants and statuses
The component has the following statuses:
* Hidden
* Visible

### 4.1 Overlay above the icon
![Image of the tooltip component with text box above it](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tooltip/images/tooltip_above.png 'class: image')

#### Design specification
* [Hidden](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/WmnWOg#Inspector)
* [Visible](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/34xdgD#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/tooltip)

### 4.2 Overlay below the icon
![Image of the tooltip component with text box below it](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tooltip/images/tooltip_underneath.png 'class: image')

#### Design specification
* [Hidden](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/rvrLEx#Inspector)
* [Visible](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ndDYOW#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/tooltip)