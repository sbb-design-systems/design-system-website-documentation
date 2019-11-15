## 1. What does the component do? 
* It is used for the selection of one or more options from a pre-defined list.


## 2. When should the component be used?
* For the selection of several options (selection of single or multiple options) from a list.
* If a selection must be made where the entries mutually exclude one another and no default value is to be set (in contrast to the [radio button](https://digital.sbb.ch/de/webapps/components/radiobutton) element.
* When selection options are to be grouped.


## 3. Rules
* There must be a choice of at least two options.
* The element always has a label.
* A question mark in the circle can also be shown – in addition to the label – for detailed explanations. A [tooltip](https://digital.sbb.ch/de/webapps/components/tooltip) opens when this question mark is clicked on.
* The text in the select element is always single-line.
* If an entry is longer than the available width of the element, the entry’s text is abbreviated with ‘…’.
* A pre-selection is not permitted with a mandatory field.
* If no selection has been made yet, the element text says “please select …”.


## 4. Variants and statuses
The component has the following statuses:
- Default
- Focused
- Disabled
- Error
- Expanded

### 4.1 Standard
![Image of the select component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_default.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355347615/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355347616/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355347617/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355347618/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347619/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355347620/inspect)
* [Active](https://sbb.invisionapp.com/d/main#/console/17140415/355347621/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/select)

### 4.2 Multiple choice 
![Image of the select component with multiple choice](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_multi.png 'class: image')

#### Design specification
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/17140415/355347622/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347623/inspect)
* [Expanded Autocomplete](https://sbb.invisionapp.com/d/main#/console/17140415/371074705/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/select)

### 4.3 Grouped single choice
![Image of the select component with grouped entries](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_grouped_single.png 'class: image')

#### Design specification
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347624/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/select)

### 4.4 Grouped multiple choice
![Image of the select component with grouped entries and multiple choice](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/select/images/select_grouped_multi.png 'class: image')

#### Design specification
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355347625/inspect)
* [Expanded Tree Checkbox](https://sbb.invisionapp.com/d/main#/console/17140415/371074670/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/select)
