## 1. Was macht die Komponente?
* It allows the user to show explanations if required.


## 2. Wann soll das Modul eingesetzt werden?
* For context-specific explanations on interaction elements or text.


## 3. Rules
* The tooltip consists of an icon and the overlay. The info-icon is standard and can be replaced by another icon if required.
* The overlay opens when the icon is clicked on.
* Alternatively the tooltip could be opened on hover.
* The tooltip can also be positioned/made accessible on texts or images.
* Only free text and [links](https://digital.sbb.ch/en/webapps/components/link) can be used in the overlay. The text can also be displayed as a list.
* The tooltip text can have a maximum of 300 characters.
* The overlay contains an ‘X’ icon to close the overlay.
* The overlay can also be hidden again by clicking anywhere next to the overlay.
* The pointer of the overlay, which points to the icon, can be positioned anywhere horizontally (depends on the position of the tooltip on the page).



## 4. Variants and statuses
The component has the following statuses:
* Hidden
* Hover
* Visible

### 4.1 Overlay above the icon
![Image of the tooltip component with textbox above it](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/tooltip/images/Tooltip_Above.png 'class: image')

#### Design specification
* [Hidden](https://sbb.invisionapp.com/d/main#/console/17140415/355318612/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318613/inspect)
* [Visible](https://sbb.invisionapp.com/d/main#/console/17140415/355318614/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/tooltip)

### 4.2 Overlay below the icon
![Image of the tooltip component with the textbox below it](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/tooltip/images/Tooltip_Underneath.png 'class: image')

#### Design specification
* [Hidden](https://sbb.invisionapp.com/d/main#/console/17140415/355318612/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318613/inspect)
* [Visible](https://sbb.invisionapp.com/d/main#/console/17140415/355318615/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/business/components/tooltip)
