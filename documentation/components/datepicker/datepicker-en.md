## 1. What does the component do?
It is used for the entry of a date.

## 2. When should the component be used?
Whenever a date value is required from the user.

## 3. Rules
* Date information is always single-line.
* The date selection always has a label.
* Optional date entries include the text ‘(optional)’ behind the label. The text ‘(optional)’ can be abbreviated as ‘(opt.)’ in short fields.
* A question mark in the circle can also be shown – in addition to the label – for detailed explanations. A [tooltip](https://digital.sbb.ch/en/websites/components/tooltip) opens when this question mark is clicked on.
* The date can be entered manually by clicking on the date field. The digit entry keypad of the system concerned appears on touch devices.
* The point must always be entered by the user with manual entry. The element then takes over the correct formatting, i.e. entries like 1.1.18 must be accepted and put into the required format.
* A calendar layer for the selection of the date opens when the calendar icon is clicked on. This is closed again by clicking outside of the calendar layer.
* The system date picker is never used on touch devices.
* Individual days or entire date ranges can be deactivated in the calendar layer.
* The navigation arrows in the calendar layer (month/year) are only displayed if a preceding/following date can also be selected.

## 4. Variants and statuses
The component has the following statuses: 
* Default
* Focused
* Disabled
* Error

### 4.1 Standard
![Image of the datepicker component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/datepicker/images/datepicker_default.png 'class: image')
* The selected date is shown in the format, day of the week, DD.MM.YYYY (example: Fri, 04.08.2017).
* The calendar layer opens if the calendar icon is clicked on.
* If the focus is in the calendar layer, this can be operated as follows using the keyboard:
    * Arrow keys: Changing the marked day.
    * Space / Enter: Selection of the marked day.

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/Rvo8Rx#Inspector)
* [Focused]((https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/1JPW8n#Inspector)
* [Disabled](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/pZKwmG#Inspector)
* [Error](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/VOob9A#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/datepicker?variant=standard)

### 4.2 With scroll function
![Image of the datepicker component with scroll function](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/datepicker/images/datepicker_pageable.png 'class: image')
* The date selected is shown in the format day of the week, DD.MM.YYYY (example: Fri, 04.08.2017).
* The navigation arrows are only displayed if a preceding/subsequent date can also be selected.
* The calendar layer opens if the calendar icon is clicked on.
* If the focus is in the calendar layer, this can be operated as follows using the keyboard:
    * Arrow keys: Changing of the marked day.
    * Space / Enter: Selection of the marked day.

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/Ya5d7m#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/KPRqDg#Inspector)
* [Disabled](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/wmQgoq#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/datepicker?variant=standard)

### 4.3 Date range
* Two date pickers are combined to select a date range.
* If the from date is selected via the calendar layer and the to date has not yet been defined, the calendar layer of the to field opens. If the to date has already been selected, the calendar layer does not open.
* If the user selects a from date > to date, the to date is deleted and its calendar layer is shown.
* If two dates are selected, the selected date range is shown in colour in the calendar.
* The selected date is shown in the format, day of the week, DD.MM.YYYY (example: Fri, 04.08.2017).

### 4.4 Date of birth
![Image of the datepicker component with date of birth](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/datepicker/images/datepicker_birthdate.png 'class: image')
* The date of birth is shown in the format DD.MM.YYYY (example: 02.09.1986).

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/qJVqE2#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/LgnLa3#Inspector)
* [Disabled](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/7mav8P#Inspector)
* [Error](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/yaQ2xa#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/datepicker?variant=standard)

### 4.5 Calendar layer
![Image of the datepicker component with visible date layer](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/datepicker/images/datepicker_picker.png 'class: image')
The tab sequence within the calender layer is defined as follows:
1. month back
2. month forward
3. year back
4. year forward
5. range of the individual days. If the focus is in the range of days, the arrow keys can be used to navigate left, right, up and down within the days.

#### Design specification
* [No selection](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/9aWe8z#Inspector)
* [Date selected](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/PZoPk8#Inspector)
* [Date with hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/gLZldj#Inspector)
* [Selection restrictions](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/8Dp4b8#Inspector)
* [Date range within a month](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/2vejnA#Inspector)
* [Date range beyond a month](hhttps://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/MjM7A7#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/datepicker?variant=standard)