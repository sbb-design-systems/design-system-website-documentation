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
* [Active](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/bVamvo#Inspector)
* [Inactive](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/WmnWQg#Inspector)
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/34xdzD#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/rvrLVx#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/tabs?variant=standard)

### 4.2 With quantity indicator 
![Image of the tab component with quantity indicator](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tab/images/tab_indicator.png 'class: image')
* The quantity indicator provides information about how many entries a list in the content of the tab shows.
* The quantity indicator only contains numbers and is a maximum of three digits.

#### Design specification
* [Active](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ndDYoW#Inspector)
* [Inactive](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/QJ1gQ8#Inspector)
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/xDQ8vA#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/EwG1pY#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/tabs?variant=standard)