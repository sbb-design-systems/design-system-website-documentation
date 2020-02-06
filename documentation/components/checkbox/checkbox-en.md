## 1. What does the component do?
* It is used for the entry of yes/no values.

## 2. When should the component be used?
* When selecting an option.
* When selecting several options that are independent of one another.

## 3. Rules
* A checkbox is only permitted within forms.
* A pre-selection is mandatory (active or inactive, no tristate).
* Several checkboxes can be arranged vertically or horizontally. The vertical layout is preferred as it allows the user to understand the options more quickly.
* Horizontal layout only for two to three options and short names.
* A horizontal layout is not permitted for mobile views.
* The text can be multi-line.
* In addition to the actual checkbox, the entire text can also be used as a click target.
* A title can be inserted above a checkbox group.
* A question mark in the circle can also be shown – in addition to the title – for detailed explanations. A [tooltip](https://digital.sbb.ch/en/websites/components/tooltip) opens when this question mark is clicked on.
 
## 4. Variants and statuses
The component has the following statuses: 
* Checked
* Unchecked
* Focused checked
* Focused unchecked
* Disabled checked
* Disabled unchecked

### 4.1 Standard
![Image of the checkbox component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/checkbox/images/checkbox_default.png 'class: image')

#### Design specification
* [Checked](https://sbb.invisionapp.com/d/main#/console/15744722/327724165/inspect)
* [Unchecked](https://sbb.invisionapp.com/d/main#/console/15744722/327724166/inspect)
* [Focused checked](https://sbb.invisionapp.com/d/main#/console/15744722/327724167/inspect)
* [Focused unchecked](https://sbb.invisionapp.com/d/main#/console/15744722/327724168/inspect)
* [Disabled checked](https://sbb.invisionapp.com/d/main#/console/15744722/327724169/inspect)
* [Disabled unchecked](https://sbb.invisionapp.com/d/main#/console/15744722/327724170/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/checkbox)

### 4.2 Vertical checkbox group 
![Image of the checkbox as a vertical group component](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/checkbox/images/checkbox_vertical.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327724171/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/checkbox)

### 4.3 Horizontal checkbox group
![Image of the checkbox as a horizontal group component](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/checkbox/images/checkbox_horizontal.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327724172/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/checkbox)