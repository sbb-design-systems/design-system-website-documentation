## 1. What does the component do?
It is used to structure the display of data and forms.

## 2. When should the component be used?
* When switching between different aspects within the same context.
* When the content of various aspects cannot be seen at the same time by the user.

## 3. Rules
* There are at least two tabs.
* The first tab is always selected by default.
* The tab names are always single-line.
* The tab name should be as simple and concise as possible so that the themes can be quickly understood.
* If the tab is too long for the viewport, the other tabs can be reached with a horizontal scrollbar (desktop) or by swiping (tablet/mobile).
* Another tab module is not permitted within a tab (tab-in-tab).

## 4. Variants and statuses
The component has the following statuses:
* Active
* Inactive
* Hover
* Focused

### 4.1 Standard
![Image of the tab component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tab/images/tab_default.png 'class: image')

#### Design specification
* [Active](https://sbb.invisionapp.com/d/main#/console/15744722/332819501/inspect)
* [Inactive](https://sbb.invisionapp.com/d/main#/console/15744722/332819502/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/332819503/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/332819504/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/tabs)

### 4.2 With quantity indicator 
![Image of the tab component with quantity indicator](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tab/images/tab_indicator.png 'class: image')
* The quantity indicator provides information about how many entries a list in the content of the tab shows.
* The quantity indicator only contains numbers and is a maximum of three digits.

#### Design specification
* [Active](https://sbb.invisionapp.com/d/main#/console/15744722/332819505/inspect)
* [Inactive](https://sbb.invisionapp.com/d/main#/console/15744722/332819506/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/332819507/inspect)
* [Focused](https://sbb.invisionapp.com/d/main#/console/15744722/332819508/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/tabs)