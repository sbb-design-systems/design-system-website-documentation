## 1. What does the component do?
It is used for the entry of text and numbers.

## 2. When should the component be used?
When an entry is required from the user.

## 3. Rules
* An entry field always has a label.
* Optional entries include the text ‘(optional)’ behind the label text. The text ‘(optional)’ can be shortened to ‘(opt.)’ for short fields.
* A question mark in the circle – in addition to the label – can be used for detailed explanations. A [tooltip](https://digital.sbb.ch/en/websites/components/tooltip) opens when this question mark is clicked on.
* The entry text is always single-line.
* If the text becomes longer than the width of the entry field during the entry, the text entered is pushed to the left so that what is currently being written can always be seen.
* After leaving the entry field with a long text, this is cut off at the end and designated with “…”.
* An entry field may contain a placeholder which is displayed directly in the entry field provided no value has been entered by the user.
* An entry field can have three different widths:
    * Short → 1/6 of the available width of the container/parent element (1/4 with tablet portrait, 1/3 with mobile portrait).
    * Medium → 1/2 of the available width of the container/parent element (full width with mobile portrait).
    * Long → full available width of the container/parent element.
* If the user can never edit a form field, no entry field can be used (display as text).

## 4. Variants and statuses
The component has the following statuses:
* Default
* Hinted
* Focused
* Disabled
* Error

### 4.1 Standard
![Image of the entry field component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/textfield/images/textfield_default.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/lgGplV#Inspector)
* [Hinted](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/kPQ10P#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ozDKR3#Inspector)
* [Disabled](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/Rvo8xj#Inspector)
* [Error](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/1JPWjk#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/field)

### 4.2 Password entry
![Image of the entry field component for password entry](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/textfield/images/textfield_password.png 'class: image')
* The entry field in the ‘password’ variant does not provide a ‘hinted’ status.

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/pZKw1k#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/VOobQa#Inspector)
* [Disabled](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/Ya5dQd#Inspector)
* [Error](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/KPRqQK#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/field)