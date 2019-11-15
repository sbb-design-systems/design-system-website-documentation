## 1. What does the component do?
* It shows values and categories as compact elements.


## 2. When should the component be used?
* When it should be possible to assign several values to an attribute in a form.
* For filtering by categories.


## 3. Rules
* A filter chip always has an indicator that shows how many results lie behind it.
* The term in the chip is always single-line (no line breaks) and the chip itself increases in width with the text.
* If a chip is too long for the viewport because of the text, the text is shortened with “…”.
* The input chips are shown in a [text field](https://digital.sbb.ch/webapps/components/textfiled). This can also be multi-line depending on the number of chips.


## 4. Variants and statuses
The component has the following statuses:
* Active

### 4.1 Input
This variant has the following statuses:
* Disabled
* Hover
* On-Click/Dragged

![Image of the chip component as an entry value](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/chip/images/chip_input.png 'class: image')

* The chips can be generated via ‘autocomplete’ selection or with free text depending on the case.

#### Design specification
* [Active](https://sbb.invisionapp.com/d/main#/console/17140415/355318411/inspect)
* [Disabled](https://sbb.invisionapp.com/d/main#/console/17140415/355318412/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318413/inspect)
* [On-Click/Dragged](https://sbb.invisionapp.com/d/main#/console/17140415/355318414/inspect)

### 4.2 Filter
This variant has the following statuses:
* Inactive

![Image of the chip component for filtering](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/chip/images/chip_filter.png 'class: image')

* •	By clicking on a tag, the respective status toggles to the others and influences the filter result.

#### Design specification
* [Active](https://sbb.invisionapp.com/d/main#/console/17140415/355318415/inspect)
* [Inactive](https://sbb.invisionapp.com/d/main#/console/17140415/355318416/inspect)
