## 1. What does the component do?
It is used to display the navigation hierarchy of the current page.

## 2. When should the component be used? 
On every page where the user should be able to navigate quickly to a sister or parent page.

## 3. Rules
* The breadcrumb is always positioned directly beneath the [header](https://digital.sbb.ch/en/websites/modules/header). The exception is when a [ghettobox](https://digital.sbb.ch/en/websites/components/ghettobox) is shown, then the breadcrumb follows immediately after the last ghettobox.
* The breadcrumb can be multi-line for long entries.
* All levels are always shown on the desktop and tablet.
* Only the last levels are written out on the mobile. Preceding levels are shown on a single one with ‘…’. All intermediate levels are show if ‘…’ is clicked on.
* If the horizontal width of the viewport on the mobile is not sufficient to show all levels, the breadcrumb content is scrollable.

## 4. Variants and statuses 
The component has the following statuses:
* Default
* Hover

The following statuses exist for the ‘mobile’ viewport:
* Full
* Overflow

### 4.1 Standard
![Image of the breadcrumb component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/breadcrumb/images/breadcrumb_default.png 'class: image')

#### Design specification
* [Default/Full](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/PZoPvQ#Inspector)
* [Hover/Overflow](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/gLZlYz#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/breadcrumb?variant=standard)

### 4.2 With sister pages
This variant also has the following statuses:
* Expanded

![Image of the breadcrumb component with sister pages](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/breadcrumb/images/breadcrumb_sibling.png 'class: image')
* Clicking on the designator or arrow opens the dropdown.
* All sister pages are listed in the dropdown.
* This closes again when clicking outside of the dropdown.
* The active page is highlighted in the dropdown.

#### Design specification
* [Default / Full](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/8Dp4o7#Inspector)
* [Hover / Overflow](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/2vejDM#Inspector)
* [Expanded](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/MjM7zw#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/breadcrumb?variant=standard)