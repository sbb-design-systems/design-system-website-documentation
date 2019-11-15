## 1. What does the component do?
* It provides context-specific actions, either dynamically via right mouse click on an element or statically via an icon.


## 2. When should the component be used?
* •	When actions for efficient execution are to be provided on an object depending on the status or role of the user.


## 3. Rules
* A context menu can be provided via the right mouse click or via an icon.
* The context menu may contain icons but does not have to.
* On a level of the context menu, there is either an icon for all menu items or none at all.
* Menu items can be grouped. Groups are separated by a dash.
* A context menu can be used for sorting elements. In this case, an arrow is used to show which attribute is used for sorting and in which direction.
* Providing deeper level structures is also permitted. However, it is worth noting that the more complex, the less efficient it is to use.


## 4. Variants and statuses
The component has the following statuses:
* Default
* Hover

### 4.1 Standard
This variant also has the following statuses:
* Expanded (optional)

![Image of the context menu component for opening via the right mouse button](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/contextmenu/images/contextmenu_default.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318417/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318418/inspect)
* [Expanded](https://sbb.invisionapp.com/d/main#/console/17140415/355318419/inspect)

### 4.2 Icon
This variant also has the following statuses:
* Default
* Hover
* Expanded Hover
* Expanded Active

![Image of the context menu component for opening with the icon](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/contextmenu/images/contextmenu_icon.png 'class: image')

* The three dots are used for the icon as default. 

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/17140415/355318420/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318421/inspect)
* [Expanded Hover](https://sbb.invisionapp.com/d/main#/console/17140415/355318422/inspect)

### 4.3 Sorting
This variant also has the following statuses:
* Expanded Hover
* Expanded Active

![Image of the context menu component to sort content](https://raw.githubusercontent.com/sbb-design-systems/sbb-design-system/master/webapp/components/contextmenu/images/contextmenu_sorting.png 'class: image')
* The arrow icon is used to display the sorting.
* Sorting is ascending by default.
* When hovering over an active sorted attribute, the arrow icon is turned around.
* The entire menu entry (name and icon) is clickable.

#### Design specification
* [Hover](https://sbb.invisionapp.com/d/main#/console/17140415/369105601/inspect)
* [Active](https://sbb.invisionapp.com/d/main#/console/17140415/355318423/inspect)
