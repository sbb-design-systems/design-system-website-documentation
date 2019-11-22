## 1. What does the module do?
* It is used for the entry of simple search requests.


## 2. When should the module be used?
* When the user has to be provided with the option of entering a search request using one or several (partial) words.


## 3. Rules
* The search field always has a placeholder indicating which search terms are accepted.
* As soon as the focus is in the search field, the user can be shown up to nine most frequently searched-for keywords if required.
* After the second letter has been typed in, four possible results (auto-suggest mechanism) appear.
* Matches with the letters entered appear in bold in the hit list.
* If there are no hits, the most frequent keywords continue to appear alone. If no most frequent keywords are defined and there are no hits, the auto-suggest box is hidden.
* Auto-suggest terms that are too long are shortened and labelled with “…”.
* If the entry of webcodes is permitted, the auto-suggest mechanism is deactivated.
* The search is started by clicking on the ‘search’ button (magnifying glass) or by using the Enter key.
* If the text is longer than the width of the search field, the text entered is pushed to the left so that what is currently being written can always be seen.
* After leaving the search field with a long text, this is cut off at the end and designated with “…”.
* Clicking on an auto-suggest term from the list navigates directly to this page.


## 4. Variants and statuses
The module has the following statuses: * Initial * Suggested * NoResult

### 4.1 Standard
* The number of auto-suggest terms shown is defined for each usage scenario.
* Maximum of ten entries recommended.

### 4.2 In the header
This variant has the following statuses:
* Hover
* Focused

* The entry mask opens when ‘Search’ is clicked on.
* After starting the search, the entry mask is hidden and only the link ‘Search’ is shown.
* This module can only be used in the [header](https://digital.sbb.ch/de/webapps/modules/header).
* When the search is started, the results are shown on a separate page.
* A maximum of four auto-suggest proposals are shown when typing.
