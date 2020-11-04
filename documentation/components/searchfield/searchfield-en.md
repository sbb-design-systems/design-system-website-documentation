## 1. What does the component do?
It is used for the entry of simple search requests.

## 2. When should the component be used?
When the user has to be provided with the option of entering a search request using one or several (partial) words.

## 3. Rules
* The search field always has a placeholder indicating which search terms are accepted.
* As soon as the focus is in the search field, the user can be shown up to nine most frequently searched-for keywords if required.
* After the second letter has been typed in, four possible results (auto-suggest mechanism) appear.
* The matches of the letters entered are shown in bold in the hits.
* If there are no hits, the most frequent keywords continue to appear alone. If no frequent keywords are defined and there are no hits, the auto-suggest box is hidden.
* Auto-suggest terms that are too long are cut off and marked with “...”.
* If web codes are permitted as an entry, the auto-suggest mechanism is deactivated.
* The search is started by clicking on the ‘search’ button (magnifying glass) or by using the Enter key.
* If the text becomes longer than the width of the entry field during the entry, the text entered is pushed to the left so that what is currently being written can always be seen.
* After leaving the search field with a long text, this is cut off at the end and designated with “…”.
* If you click on an auto-suggest term from the list, you will navigate directly to this page.

## 4. Variants and statuses
The component has the following statuses: 
* Default
* No Result
* Suggested
 
### 4.1 Standard
![Image of the searchfield component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/searchfield/images/searchfield_default.png 'class: image')
* The number of the auto-suggest terms displayed has to be defined for each case.
* A maximum of ten entries is recommended.

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/ozDKx3#Inspector)
* [No Result](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/Rvo8qj#Inspector)
* [Suggested](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/1JPWRk#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/search)

### 4.2 In the header
The component has the following statuses:
* Default
* Hover
* Focused
* No Result
* Suggested

![Image of the searchfield component integrated in the header](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/searchfield/images/searchfield_header.png 'class: image')
* The entry mask opens when ‘search’ is clicked on.
* After the search has been started, the entry mask is hidden again and only the ‘Search’ link is displayed.
* This module can only be inserted in the [header](https://digital.sbb.ch/en/websites/modules/header).
* When the search is triggered, the results are displayed on a separate page.
* When typing a maximum of four auto-suggest proposals are shown.

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/pZKwyk#Inspector)
* [Hover](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/VOobqa#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/Ya5dqd#Inspector)
* [No Result](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/KPRq8K#Inspector)
* [Suggested](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/wmQgYV#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/search)