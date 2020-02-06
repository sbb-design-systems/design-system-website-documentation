## 1. What does the component do?
It makes various information and functions available.

## 2. When should the component be used?
To complement content pages.

## 3. Rules
* The module is always used in the margin column (on the right).
* Several modules can be positioned beneath one another in the margin column.
* When scrolling all boxes in the margin column are sticky. The individual boxes are successively minimised as soon as they reach the top edge of the viewport.
* Individual boxes in the scrolled status can be expanded by the user.
* Only one box can ever be expanded in the scrolled status.

## 4. Variants and statuses
The Next Best Click container does not have any cross-viewport statuses as they behave differently. The individual variants also have different forms.

### 4.1 Action
![Image of the Next Best Click container image to trigger actions](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/nbc/images/nbc_action.png 'class: image')

####Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/345616913/inspect)
* [Double](https://sbb.invisionapp.com/d/main#/console/15744722/345616914/inspect)
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/345616915/inspect)

#### Code specification
In progress.

### 4.2 Contact
![Image of the Next Best Click container component as information on the contact options](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/nbc/images/nbc_contact.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/345616916/inspect)
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/345616917/inspect)

#### Code specification
In progress.

### 4.3 Link
![Image of the Next Best Click container component as a link list to other topics](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/nbc/images/nbc_link.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/345616918/inspect)
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/345616919/inspect)

#### Code specification
In progress.

### 4.4 Download
![Image of the Next Best Click container component with several download files](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/nbc/images/nbc_download.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/345616920/inspect)
* [App](https://sbb.invisionapp.com/d/main#/console/15744722/345616921/inspect)
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/345616922/inspect)

#### Code specification
In progress.

### 4.5 Chat
![Image of the Next Best Click container component to start the live chat](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/nbc/images/nbc_chat.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/345616923/inspect)
* [Collapsed](https://sbb.invisionapp.com/d/main#/console/15744722/345616924/inspect)

#### Code specification
In progress.

## 5. Behaviour
### 5.1 Desktop (and higher resolutions)
* All Next-Best-Click options are arranged on the content pages in the margin column (right column).
* When scrolling all boxes in the right column are sticky. The individual boxes are successively minimised as soon as they reach the upper edge of the viewport (below the sticky header) and below with already minimised boxes.
* In the minimised status, all boxes are always accessible for the user.
* The user can then open a box (and also close it again).
* Only one box can be opened at the same time in the scrolled status.
* The NBC box remains sticky until the user reaches the end of the content area. If the user continues to scroll down, the boxes with the content scroll away upwards.
* If the user then scrolls upwards again, the NBC box also reappears and is sticky again.

![Image of the behaviour of a Next Best Click container on desktops and with higher resolutions](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/nbc/images/nbc_behaviour_desktop_default.png 'class: image')

#### Special case: NBC box within an accordion
* A NBC box is never minimised when used within an [accordion](https://digital.sbb.ch/en/websites/components/accordion).
* Only one NBC box can be inserted into an accordion.
* When scrolling, the NBC box remains sticky on the top edge to the end of the content area of the accordion, after which the box continues to be scrolled with the content.

![Image of the behaviour of a Next Best Click within an accordion](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/nbc/images/nbc_behaviour_desktop_accordion.png 'class: image')

### 5.2 Tablet
* All Next-Best-Click options are always available via the sticky element on the bottom right.
* When clicked, a layer with all NBC modules alongside one another opens in the open status (two-column display)
* The icon in the sticky element then changes into the close button (toggle button).
* In the tablet variant, the NBC boxes at the end of the content area are displayed as redundant (open).
* If the user scrolls into the relevant area (and beyond) the element for opening the NBC layer is hidden.
* If the user scrolls up again, the sticky element also reappears.

![Image of the behaviour of a Next Best Click container on tablets](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/nbc/images/nbc_behaviour_tablet.png 'class: image')

### 5.3 Mobile
* All Next-Best-Click options are always accessible via the sticky element in the bottom right.
* When clicked, a layer with all NBC modules opens in closed status.
* Only one module can be opened at a time.
* The icon in the sticky element turns into the close icon (toggle button).
* In the mobile variant, the NBC boxes at the end of the content area are displayed as redundant (open).
* If the user scrolls into the relevant area (and beyond) the element for opening the NBC layer is hidden.
* If the user scrolls up again, the sticky element also reappears.

![Image of the behaviour of a Next Best Click container on mobiles](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/nbc/images/nbc_behaviour_mobile.png 'class: image')