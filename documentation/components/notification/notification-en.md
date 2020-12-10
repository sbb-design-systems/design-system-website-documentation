## 1. What does the component do?
It is used to display messages that concern an entire page.

## 2. When should the component be used?
* When a user has triggered an action on a page and should receive feedback from the system.

## 3. Rules
* Notifications only ever appear after an action has been triggered by the user.
* The width is always the same as the content area.
* The height is based on the length of the message text.

## 4. Variants
### 4.1 Confirmation
![Image of the notification component to display confirmation messages](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/notification/images/notification_confirmation.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/rvrL4A#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/notification)

### 4.2 Information
![Image of the notification component to display information messages](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/notification/images/notification_information.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ndDYMl#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/notification)

### 4.3 Error 
![Image of the notification component to display error messages](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/notification/images/notification_error.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/QJ1g7b#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/notification)

### 4.4 Error with jump marker 
![Image of the notification component to display error messages with jump marker](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/notification/images/notification_link.png 'class: image')
* The individual jump markers are separated by a ‘/’.
* Clicking on a skip marker scrolls directly to the cause of the error.
* The jump marker target is always on the same page as the notification (no jumping to other pages).

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/xDQ8E0#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/public/components/notification)