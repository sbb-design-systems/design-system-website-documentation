## 1. What does the component do?
It is used for the entry of a time.

## 2. When should the component be used?
Whenever a time is required from the user.

## 3. Rules
* The current time is pre-entered as standard except where it is not useful in the context.
* The time can be entered without a colon. Entries such as 130, 1.30 or 1,30 are correctly reformated as 01:30 after leaving the field.
* The number entry keypad of the system concerned appears on touch devices.

## 4. Variants and statuses
The component has the following statuses: 
* Default
* Hinted
* Focused
* Disabled
* Error

### 4.1 Standard
![Image of the entry field for times component](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/timefield/images/timefield_default.png 'class: image')

#### Design specification
* [Default](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/wmQgJV#Inspector)
* [Hinted](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/qJVqpd#Inspector)
* [Focused](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/LgnLQ5#Inspector)
* [Disabled](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/7mav4w#Inspector)
* [Error](https://www.sketch.com/s/80f12b3b-58e5-4b4c-98cd-c553bae18db0/a/yaQ2p8#Inspector)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/public/components/time-input)