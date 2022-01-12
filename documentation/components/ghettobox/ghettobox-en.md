## 1. What does the component do?
It is used to display cross-page messages.

## 2. When should the component be used?
For information and errors that concern an entire application.

## 3. Rules
* The ghettobox can be hidden with the X-icon until the next page reload.
* The ghettobox is always directly below the [header](https://digital.sbb.ch/en/websites/modules/header).
* The ghettobox is not sticky but instead scrolls away with the content.
* The text can be multi-line.
* There is always an [icon](https://digital.sbb.ch/en/brand_elemente/icons) in a red area (HIM/CUS icons) in front of the text.
* If several ghettoboxes are used at the same time, they are arranged beneath one another.

## 4. Variants and statuses
### 4.1 Standard
![Image of the ghettobox component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/ghettobox/images/ghettobox_default.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/34xd8m#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/alert?variant=standard)

### 4.2 Link
This variant has the following statuses:
* Default
* Hover

![Image of the ghettobox with link](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/ghettobox/images/ghettobox_link.png 'class: image')
* If the text contains another [link](https://digital.sbb.ch/en/components/link), the ghettobox distinguishes between the statuses of normal and hover.
* There is always an arrow icon at the end of the text.
* The entire area of the ghettobox can be clicked on and opens the link inserted (except above the X-icon).

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/rvrLaA#Inspector)
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ndDYzl#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/alert?variant=standard)