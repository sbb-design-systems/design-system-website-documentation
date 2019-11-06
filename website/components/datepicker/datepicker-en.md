## 1. What does the component do?
It is used for the entry of a date.

## 2. When should the component be used?
Whenever a date value is required from the user.

## 3. Rules
* Date information is always single-line.
* The date selection always has a label.
* Optional date entries include the text ‘(optional)’ behind the label. The text ‘(optional)’ can be abbreviated as ‘(opt.)’ in short fields.
* A question mark in the circle can also be shown – in addition to the label – for detailed explanations. A [tooltip](https://digital.sbb.ch/en/components/tooltip) opens when this question mark is clicked on.
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
![Image of the datepicker component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/datepicker/images/datepicker_default.png 'class: image')
* The selected date is shown in the format, day of the week, DD.MM.YYYY (example: Fri, 04.08.2017).
* The calendar layer opens if the calendar icon is clicked on.
* If the focus is in the calendar layer, this can be operated as follows using the keyboard:
    * Arrow keys: Changing the marked day.
    * Space / Enter: Selection of the marked day.

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327605628/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/327605629/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/15744722/327605630/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/15744722/377703710/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/datepicker)

### 4.2 With scroll function
![Image of the datepicker component with scroll function](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/datepicker/images/datepicker_pageable.png 'class: image')
* The date selected is shown in the format day of the week, DD.MM.YYYY (example: Fri, 04.08.2017).
* The navigation arrows are only displayed if a preceding/subsequent date can also be selected.
* The calendar layer opens if the calendar icon is clicked on.
* If the focus is in the calendar layer, this can be operated as follows using the keyboard:
    * Arrow keys: Changing of the marked day.
    * Space / Enter: Selection of the marked day.

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327605631/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/327605632/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/15744722/327605633/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/datepicker)

### 4.3 Date range
* Two date pickers are combined to select a date range.
* If the from date is selected via the calendar layer and the to date has not yet been defined, the calendar layer of the to field opens. If the to date has already been selected, the calendar layer does not open.
* If the user selects a from date > to date, the to date is deleted and its calendar layer is shown.
* If two dates are selected, the selected date range is shown in colour in the calendar.
* The selected date is shown in the format, day of the week, DD.MM.YYYY (example: Fri, 04.08.2017).

### 4.4 Date of birth
![Image of the datepicker component with date of birth](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/datepicker/images/datepicker_birthdate.png 'class: image')
* The date of birth is shown in the format DD.MM.YYYY (example: 02.09.1986).

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327605634/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/327605635/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/15744722/327605636/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/15744722/377703711/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/datepicker)

### 4.5 Calendar layer
![Image of the datepicker component with visible date layer](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/website/components/datepicker/images/datepicker_picker.png 'class: image')
The tab sequence within the calender layer is defined as follows:
1. month back
2. month forward
3. year back
4. year forward
5. range of the individual days. If the focus is in the range of days, the arrow keys can be used to navigate left, right, up and down within the days.

#### Design specification
* [No selection](https://sbb.invisionapp.com/d/main#/console/15744722/327605637/inspect)
* [Date selected](https://sbb.invisionapp.com/d/main#/console/15744722/327605638/inspect)
* [Date with hover](https://sbb.invisionapp.com/d/main#/console/15744722/327605639/inspect)
* [Selection restrictions](https://sbb.invisionapp.com/d/main#/console/15744722/327605640/inspect)
* [Date range within a month](https://sbb.invisionapp.com/d/main#/console/15744722/327605641/inspect)
* [Date range beyond a month](https://sbb.invisionapp.com/d/main#/console/15744722/327605642/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/datepicker)