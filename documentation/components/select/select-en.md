## 1. What does the component do?
It is used for the selection of one or more options from a pre-defined list.

## 2. When should the component be used?
* When selecting from several options (single or multiple choice) in a list.
* If a selection must be made where the entries mutually exclude one another and no default value is to be set (in contrast to the [radio button](https://digital.sbb.ch/en/components/radiobutton) element).
* When selection options are to be grouped.

## 3. Rules
* There must be at least two options available.
* The element always has a label.
* Optional selections include the text ‘(optional)’ behind the label. The text ‘(optional)’ can be abbreviated to ‘(opt.)’ in short fields.
* A question mark in the circle – in addition to the label – can be used for detailed explanations. A [tooltip](https://digital.sbb.ch/en/components/tooltip) opens when this question mark is clicked on.
* The text in the select element is always single-line.
* If an entry is longer than the available width of the element, the entry’s text is abbreviated with ‘…’.
* A pre-selection is not permitted with a mandatory field.
* If no selection has been made yet, the element text says “please select …”.

## 4. Variants and statuses
The component has the following statuses:
* Default
* Focused
* Disabled
* Error
* Expanded

### 4.1 Standard
![Image of the select component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/select/images/select_default.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327200956/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/327200957/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/15744722/327200958/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/15744722/327200959/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/15744722/327200960/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/select)

### 4.2 Multiple choice 
![Image of the select component with multiple choice](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/select/images/select_multi.png 'class: image')

#### Design specification
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/327200961/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/15744722/327200962/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/select)

### 4.3 Grouped single selection
![Image of the select component with grouped entries](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/select/images/select_grouped_single.png 'class: image')

#### Design specification
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/327200963/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/15744722/327200964/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/select)

### 4.4 Grouped multiple choice
![Image of the select component with grouped entries and multiple choice](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/select/images/select_grouped_multi.png 'class: image')

#### Design specification
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/327200965/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/15744722/327200966/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/select)