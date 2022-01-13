## 1. What does the component do?
It categorises a large amount of information.

## 2. When should the component be used?
* For filtering results with lots of categories.
* In a tag cloud as a link tag to use jump points to a new category page.

## 3. Rules
* A tag always has an indicator which shows how many results are behind it.
* The tag is always positioned on the left in content pages and is always centred in overview pages.
* The order of the tags is determined editorially.
* The term in the tag is always single-line (no line breaks) and the tag itself increases in width with the text.
* If a tag becomes too long for the viewport due to the text, the text is shortened with ‘…’.

## 4. Variants and statuses
The component has the following statuses:
* Active (Default)
* Inactive
* Hover active
* Hover inactive

### 4.1 Filter tag
![Image of the filter tag component used as filter](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tag/images/tag_filtertag.png 'class: image')
* The status of the tags in the filter is active or inactive.
* When a tag is clicked, the status concerned toggles to the other status and influences the filter result.
* A tag ‘all’ is always inserted within the filter. If this filter tag is clicked, it changes to the active status and all other tags in the filter are set to the inactive status.

Example:
![Image of an example for filter tag component](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tag/images/tag_filtertag_example.png 'class: image')

#### Design specification
* [Active](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ZAnzQ7#Inspector)
* [Inactive](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/J9JwQ5#Inspector)
* [Hover active](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/vOQPZb#Inspector)
* [Hover inactive](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/4e5zZZ#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/tag?variant=standard)

### 4.2 Link tag
![Image of the filter tag component used as link](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tag/images/tag_linktag.png 'class: image')
* Link tags only have the active status.
* Clicking on the tag takes the user to the relevant category page.

Example:
![Image of an example for link tag component](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/tag/images/tag_linktag_example.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ewdAGj#Inspector)
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/GLdVQ7#Inspector)

#### Code specification
* [SBB Angular Component Library](https://angular.app.sbb.ch/angular/components/tag?variant=standard)