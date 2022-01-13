## 1. What does the component do?
It is used for the entry of large amounts of text in forms.

## 2. When should the component be used?
When the entry of longer text is required from the user.

## 3. Rules
* The text area always has a label.
* Optional entries include the text ‘(optional)’ behind the label text. The text ‘(optional)’ can be shortened to ‘(opt.)’ for short fields.
* A question mark in the circle – in addition to the label – can be used for detailed explanations. A [tooltip](https://digital.sbb.ch/en/websites/components/tooltip) opens when this question mark is clicked on.
* The number of characters still available is shown bottom right (outside the text area is disabled).
* The width of the text area is always the same as the entire width of the form.
* The basic height can be set when designing the form.
* If the text is longer than the basic height of the text area, the element increases in height with the content.

## 4. Variants and statuses
The component has the following statuses:
* Default
* Focused
* Disabled
* Error

### 4.1 Standard
![Image of the text area component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/textarea/images/textarea_default.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/OzREQ4#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/mjKVkJ#Inspector)
* [Disabled](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/DKwR1W#Inspector)
* [Error](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/apaOJZ#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/textarea?variant=standard)