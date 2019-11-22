## 1. What does the component do?
* It is used for the entry of text and numbers.


## 2. When should the component be used?
* When an entry is required from the user.


## 3. Rules 
* An entry field always has a label.
* A question mark in the circle can also be shown – in addition to the label – for detailed explanations. A [tooltip](https://digital.sbb.ch/en/webapps/components/tooltip) opens when this question mark is clicked on.
* The entry text is always single-line.
* If the text becomes longer than the width of the entry field during the entry, the text entered is pushed to the left so that what is currently being written can always be seen.
* After leaving the entry field with a long text, this is cut off at the end and designated with “…”.
* An entry field can contain a placeholder which is shown directly in the entry field provided no value has been entered by the user.
* If the user can never edit a form field, no entry field can be used (display as text).


## 4. Variants and statuses
The component has the following statuses:
* Default
* Hinted
* Focused
* Disabled
* Error

### 4.1 Standard
![Image of the text field component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/textfield/images/textfield_default.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318592/inspect)
* [Hinted](https://sbb.invisionapp.com/d/main#/console/17140415/355318593/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355318594/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318595/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355318596/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/field)

### 4.2 Password entry
![Image of the text field component in the password entry variant](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/textfield/images/textfield_password.png 'class: image')
* The entry field in the ‘password’ variant does not provide a ‘hinted’ status.

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318596/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/17140415/355318597/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318598/inspect)
* [Error](https://sbb.invisionapp.com/d/main#/console/17140415/355318600/inspect)
