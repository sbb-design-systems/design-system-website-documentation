## 1. What does the component do?
It supports the user when entering suggestions.

## 2. When should the component be used? 
* When an entry field can have lots of pre-defined values.
* As an aid for previewing search results/fields.

## 3. Rules
* Autocompletion always has a label.
* Optional entries include the text ‘(optional)’ behind the label text. The text ‘(optional)’ can be abbreviated as ‘(opt.)’ in short fields.
* A question mark in the circle can also be shown – in addition to the label – for detailed explanations. A tooltip opens if this question mark is clicked on.
* During entry, suggestions appear directly (usually after three symbols but they can be modified on a project-specific basis).
* The entries listed can be scrolled through using the arrow keys and accepted with Enter.
* A maximum of ten suggestions are shown.
* The autocompletion selection closes when an element is selected.

## 4. Variants and statuses
The component has the following statuses:
* Default
* Hover

### 4.1 Standard
![Image of the autocompletion component in the standard variant](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/autocompletion/images/autocompletion_default.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327147336/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/327147337/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/autocomplete)

### 4.2 With display of hits
As an option to the standard variant, this variant can be used when an auto-completion list always contains more than the maximum ten hits shown.
![Image of the autocompletion component with display of hits](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/autocompletion/images/autocompletion_overflow.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/383235117/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/383235118/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/autocomplete)

### 4.3 Mit statischen Einträgen
![Image of the autocompletion component with static entries](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/autocompletion/images/autocompletion_static.png 'class: image')

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/327147338/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/327147339/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/autocomplete)