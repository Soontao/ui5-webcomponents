# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.0.0-rc.5](https://github.com/SAP/ui5-webcomponents/compare/v1.0.0-rc.4...v1.0.0-rc.5) (2019-12-02)

##  [Migration guide](https://github.com/SAP/ui5-webcomponents/blob/master/docs/Migration-guides.md) from v1.0.0-rc.4 to v1.0.0-rc.5
The current release includes several new npm packages, such as `@ui5/webcomponents-fiori` and `@ui5/webcomponents-icons`.
To make the transition from v1.0.0-rc.4 to v1.0.0-rc.5 smoother, we prepared this [migration guide](https://github.com/SAP/ui5-webcomponents/blob/master/docs/Migration-guides.md).

### Bug Fixes

* **ui5-button:** prevents setting 0 height to icons in IE ([#902](https://github.com/SAP/ui5-webcomponents/issues/902)) ([20511c6](https://github.com/SAP/ui5-webcomponents/commit/20511c6))
* **ui5-checkbox:** fix layouting in IE ([#926](https://github.com/SAP/ui5-webcomponents/issues/926)) ([ffdc271](https://github.com/SAP/ui5-webcomponents/commit/ffdc271))
* **ui5-checkbox:** fix truncation in compactSize ([#998](https://github.com/SAP/ui5-webcomponents/issues/998)) ([3cdcede](https://github.com/SAP/ui5-webcomponents/commit/3cdcede))
* **ui5-datepicker:** fix hover effect ([#999](https://github.com/SAP/ui5-webcomponents/issues/999)) ([44d6c27](https://github.com/SAP/ui5-webcomponents/commit/44d6c27))
* **ui5-datepicker:** enable setting an empty placeholder ([#997](https://github.com/SAP/ui5-webcomponents/issues/997)) ([3eca602](https://github.com/SAP/ui5-webcomponents/commit/3eca602))
* **ui5-input:** correct ACC implementation ([#846](https://github.com/SAP/ui5-webcomponents/issues/846)) ([7d547ec](https://github.com/SAP/ui5-webcomponents/commit/7d547ec))
* **ui5-input:** fix input pushed downward ([#891](https://github.com/SAP/ui5-webcomponents/issues/891)) ([bda9714](https://github.com/SAP/ui5-webcomponents/commit/bda9714))
* **ui5-multi-combobox:** close popover & empty value on selection ([#832](https://github.com/SAP/ui5-webcomponents/issues/832)) ([1b3e40d](https://github.com/SAP/ui5-webcomponents/commit/1b3e40d))
* **ui5-popover:** restrict max content height when overflowing the screen ([#908](https://github.com/SAP/ui5-webcomponents/issues/908)) ([6671793](https://github.com/SAP/ui5-webcomponents/commit/6671793))
* **ui5-select:** remove unsupported method in IE ([#919](https://github.com/SAP/ui5-webcomponents/issues/919)) ([f1bceea](https://github.com/SAP/ui5-webcomponents/commit/f1bceea))
* **ui5-tabcontainer:** adjust tabs to take 100% of TC height ([#895](https://github.com/SAP/ui5-webcomponents/issues/895)) ([6fcf259](https://github.com/SAP/ui5-webcomponents/commit/6fcf259))
* **ui5-tabcontainer:** fix overflow items default semantic color ([#989](https://github.com/SAP/ui5-webcomponents/issues/989)) ([a003189](https://github.com/SAP/ui5-webcomponents/commit/a003189)), closes [#988](https://github.com/SAP/ui5-webcomponents/issues/988)
* **ui5-tabcontainer:** fix overflow items appearance and selection  ([#988](https://github.com/SAP/ui5-webcomponents/issues/988)) ([8cd2a8b](https://github.com/SAP/ui5-webcomponents/commit/8cd2a8b))
* **ui5-list:** prevent item navigaion with Left/Right keys([#985](https://github.com/SAP/ui5-webcomponents/issues/985)) ([3d46e2d](https://github.com/SAP/ui5-webcomponents/commit/3d46e2d))
* **ui5-table:** pressing SPACE works for HTML elements inside ui5-table ([#964](https://github.com/SAP/ui5-webcomponents/issues/964)) ([2384236](https://github.com/SAP/ui5-webcomponents/commit/2384236))
* **ui5-table:** fix JS error when there are less cells than columns ([#841](https://github.com/SAP/ui5-webcomponents/issues/841)) ([fd3b690](https://github.com/SAP/ui5-webcomponents/commit/fd3b690))
* **ui5-table:** fix row navigation and focus handling ([#876](https://github.com/SAP/ui5-webcomponents/issues/876)) ([f69f42c](https://github.com/SAP/ui5-webcomponents/commit/f69f42c))
* **ItemNavigation:** fix Item Navigation cycling ([#985](https://github.com/SAP/ui5-webcomponents/issues/985)) ([3d46e2d](https://github.com/SAP/ui5-webcomponents/commit/3d46e2d))
* **Framework:** order slots in state as in Light DOM ([#874](https://github.com/SAP/ui5-webcomponents/issues/874)) ([b8efea0](https://github.com/SAP/ui5-webcomponents/commit/b8efea0)), closes [#873](https://github.com/SAP/ui5-webcomponents/issues/873)
* **Framework:** skip waiting for polyfill in case already loaded ([#851](https://github.com/SAP/ui5-webcomponents/issues/851)) ([d5e19f6](https://github.com/SAP/ui5-webcomponents/commit/d5e19f6))
* **Framework:** trigger DOM mutation observer independent of insertion order ([#847](https://github.com/SAP/ui5-webcomponents/issues/847)) ([d7d96ec](https://github.com/SAP/ui5-webcomponents/commit/d7d96ec)), closes [#839](https://github.com/SAP/ui5-webcomponents/issues/839)
* **JS Doc** enable release candidates versions to be displayed as since tags ([#983](https://github.com/SAP/ui5-webcomponents/issues/983)) ([3051d76](https://github.com/SAP/ui5-webcomponents/commit/3051d76))

### Features
* **ui5-product-switch:** introduce new component within @ui5/webcomponents-fiori package([#971](https://github.com/SAP/ui5-webcomponents/pull/971)) ([4646fcd](https://github.com/SAP/ui5-webcomponents/commit/70d44b1ebf4b47c7e99ebf96feb19e5c04646fcd))
* **ui5-input:** introduce maxlength property ([#976](https://github.com/SAP/ui5-webcomponents/issues/976)) ([c149f5f](https://github.com/SAP/ui5-webcomponents/commit/c149f5f))
* **ui5-label:** introduce showColon property ([#965](https://github.com/SAP/ui5-webcomponents/issues/965)) ([ae95a8d](https://github.com/SAP/ui5-webcomponents/commit/ae95a8d))
* **ui5-multicombobox:** implement ACC support ([#937](https://github.com/SAP/ui5-webcomponents/issues/937)) ([0a44a92](https://github.com/SAP/ui5-webcomponents/commit/0a44a92))
* **ui5-multicombobox:** introduce open property and openChange event ([#930](https://github.com/SAP/ui5-webcomponents/issues/930)) ([c0b51f5](https://github.com/SAP/ui5-webcomponents/commit/c0b51f5))
* **ui5-panel:** improve accessibility ([#864](https://github.com/SAP/ui5-webcomponents/issues/864)) ([b133468](https://github.com/SAP/ui5-webcomponents/commit/b133468))
* **ui5-textarea:** implement input event ([#543](https://github.com/SAP/ui5-webcomponents/issues/543)) ([7c5647e](https://github.com/SAP/ui5-webcomponents/commit/7c5647e))
* **Documentation:** introduce new playground app ([#751](https://github.com/SAP/ui5-webcomponents/pull/751)) ([fdcddaa](https://github.com/SAP/ui5-webcomponents/commit/fdcddaa241cd14b182010f7815a26833655f95c4))
* **Configuration:** introduce animationMode configuration ([#905](https://github.com/SAP/ui5-webcomponents/issues/905)) ([c90e3b0](https://github.com/SAP/ui5-webcomponents/commit/c90e3b0))
* **Framework:** render SVG content with lit svg` ([#904](https://github.com/SAP/ui5-webcomponents/issues/904)) ([59fead4](https://github.com/SAP/ui5-webcomponents/commit/59fead4))
* **Framework:** introduce navigationMode property ([#910](https://github.com/SAP/ui5-webcomponents/issues/910)) ([9c43533](https://github.com/SAP/ui5-webcomponents/commit/9c43533))

### Code Refactoring
* **ui5-button:** subscribe event handlers via HBS template
* **ui5-shellbar:** move component to @ui5/webcomponents-fiori package ([#887](https://github.com/SAP/ui5-webcomponents/pull/887)) ([06f1770](https://github.com/SAP/ui5-webcomponents/commit/17c25ff123436c1f6e11513055b33977b06f1770))
* **ui5-card:** replace "avatar" property with "avatar" slot ([#928](https://github.com/SAP/ui5-webcomponents/issues/928)) ([0489673](https://github.com/SAP/ui5-webcomponents/commit/0489673))
* **ui5-icon:** change "src" property to "name" ([#928](https://github.com/SAP/ui5-webcomponents/issues/928)) ([0489673](https://github.com/SAP/ui5-webcomponents/commit/0489673))
* **ui5-shellbar:** rename "icon" slot to "startButton" ([#901](https://github.com/SAP/ui5-webcomponents/issues/901)) ([5ca3280](https://github.com/SAP/ui5-webcomponents/commit/5ca3280))
* **ui5-shellbar:** extract animated co-pilot SVG as add-on asset ([#904](https://github.com/SAP/ui5-webcomponents/pull/904)) ([c25e0a7](https://github.com/SAP/ui5-webcomponents/commit/59fead49d7a3222d55270584bb048190dc25e0a7))
* **ui5-shellbar:** optimize animated co-pilot SVG size from 15kb to 8kb ([#960](https://github.com/SAP/ui5-webcomponents/pull/960)) ([42bd7cd](https://github.com/SAP/ui5-webcomponents/commit/66d8c62658648cfeb7392607e9b66548c42bd7cd))
* **ui5-shellbar-item:**  rename "src" property to "name" ([#928](https://github.com/SAP/ui5-webcomponents/pull/928)) ([8e060d1](https://github.com/SAP/ui5-webcomponents/commit/0489673610ce2fd0e96d0a3a1f4e0465d8e060d1))

### BREAKING CHANGES

* **icons:** move all individual icons to a new npm package called `@ui5/webcomponents-icons`.

You have to install the package 
```js
npm i @ui5/webcomponents-icons --save
```
The import statements should be changed

Before:
```js
@ui5/webcomponents/dist/icons/add.js
```

After:
```js
@ui5/webcomponents-icons/dist/icons/add.js
```
*Note:* The `ui5-icon` web component is not affected by this change, it is still in the `@ui5/webcomponents` package. Only the icons themselves (the icon assets) have been moved.

* **ui5-icon:** "src" property was renamed to "name".

The "name" poperty accepts icon name (such as "add") instead of icon src (such as "sap-icon://add").
Note: the src property will continue to work until the next release due to the impact of the change, but will produce a warning in the console.

* **ui5-shellbar:** move component to new `@ui5/webcomponents-fiori` package ([#887](https://github.com/SAP/ui5-webcomponents/pull/887)) ([06f1770](https://github.com/SAP/ui5-webcomponents/commit/17c25ff123436c1f6e11513055b33977b06f1770))

Now, you have to import the `<ui5-shellbar>` from the newly created package as follows:
```js
import @ui5/webcomponents-fiori/dist/ShellBar.js
```

* **ui5-shellbar:** rename "icon" slot to "startButton" ([#901](https://github.com/SAP/ui5-webcomponents/issues/901)) ([5ca3280](https://github.com/SAP/ui5-webcomponents/commit/5ca3280))

Now, the slot accepts a ui5-button, that would be overstyled to match ui5-shellbar viusal design.

* **ui5-shellbar:** extract animated co-pilot SVG as add-on asset ([#904](https://github.com/SAP/ui5-webcomponents/pull/904)) ([c25e0a7](https://github.com/SAP/ui5-webcomponents/commit/59fead49d7a3222d55270584bb048190dc25e0a7))

Now, to get the coPilot animated version, you have to import the following module:
```js
import @ui5/webcomponents-fiori/dist/features/CoPilotAnimation.js`
```

* **ui5-shellbar-item:** "src" property renamed to "name" ([#928](https://github.com/SAP/ui5-webcomponents/pull/928)) ([8e060d1](https://github.com/SAP/ui5-webcomponents/commit/0489673610ce2fd0e96d0a3a1f4e0465d8e060d1))

The "src" property has been renamed to icon and it accepts icon name (such as "add") instead of icon src (such as "sap-icon://add")

* **ui5-card:** replace "avatar" property with "avatar" slot ([#928](https://github.com/SAP/ui5-webcomponents/issues/928)) ([0489673](https://github.com/SAP/ui5-webcomponents/commit/0489673))

The "avatar" property has been removed, use the "avatar" slot instead - you can pass an icon(`<ui5-icon>`) or an image(`<img/>`).

Before:
```html
<ui5-card avatar="sap-icon://add"></ui5-card>
```

After:
```html
<ui5-card><ui5-icon name="add" slot="avatar"></ui5-icon></ui5-card>`
```
and respectively:
```html
<ui5-card avatar="http://url/to/my/image"></ui5-card>`
```
becomes:
```html
<ui5-card><img src="http://url/to/my/image" slot="avatar"/></ui5-card>`
```



# [1.0.0-rc.4](https://github.com/SAP/ui5-webcomponents/compare/v1.0.0-rc.3...v1.0.0-rc.4) (2019-10-11)


### Bug Fixes

* **ui5-button:** apply correct "font-family: 72" ([#825](https://github.com/SAP/ui5-webcomponents/issues/825)) ([21ec559](https://github.com/SAP/ui5-webcomponents/commit/21ec559))
* **ui5-badge:** fix icon visual issue on IE ([#809](https://github.com/SAP/ui5-webcomponents/issues/809)) ([150a100](https://github.com/SAP/ui5-webcomponents/commit/150a100))

### Code Refactoring

* **framework:** stop icon fonts loading ([#827](https://github.com/SAP/ui5-webcomponents/pull/827))([21ec559](https://github.com/SAP/ui5-webcomponents/commit/21ec559))
* **framework:** add components' events info to UI5ElementMetadata([#833](https://github.com/SAP/ui5-webcomponents/issues/833))([68c30f4](https://github.com/SAP/ui5-webcomponents/pull/837/commits/68c30f4))


# [1.0.0-rc.3](https://github.com/SAP/ui5-webcomponents/compare/v1.0.0-rc.2...v1.0.0-rc.3) (2019-10-03)


### Bug Fixes

* **ui5-badge:** correct component sizing ([#733](https://github.com/SAP/ui5-webcomponents/issues/733)) ([f5a4798](https://github.com/SAP/ui5-webcomponents/commit/f5a4798))
* **ui5-badge:** fix icon size ([#729](https://github.com/SAP/ui5-webcomponents/issues/729)) ([f1e1343](https://github.com/SAP/ui5-webcomponents/commit/f1e1343))
* **ui5-busyindicator:** change z-index not to overlap popover or dialog ([#624](https://github.com/SAP/ui5-webcomponents/issues/624)) ([c91c811](https://github.com/SAP/ui5-webcomponents/commit/c91c811))
* **ui5-button:** align buttons with and without icons on same line ([#796](https://github.com/SAP/ui5-webcomponents/issues/796)) ([8420492](https://github.com/SAP/ui5-webcomponents/commit/8420492))
* **ui5-button:** fix Transparent button border in Fiori 3 & HCB ([#789](https://github.com/SAP/ui5-webcomponents/issues/789)) ([bc00f1f](https://github.com/SAP/ui5-webcomponents/commit/bc00f1f))
* **ui5-checkbox:** set default font-size to checkmark ([#618](https://github.com/SAP/ui5-webcomponents/issues/618)) ([d3a9197](https://github.com/SAP/ui5-webcomponents/commit/d3a9197))
* **ui5-datepicker:** date selection works on IE ([#623](https://github.com/SAP/ui5-webcomponents/issues/623)) ([5a0b7ad](https://github.com/SAP/ui5-webcomponents/commit/5a0b7ad))
* **ui5-datepicker:** icon from datepicker no longer flickers on IE ([#723](https://github.com/SAP/ui5-webcomponents/issues/723)) ([80c4f32](https://github.com/SAP/ui5-webcomponents/commit/80c4f32))
* **ui5-icon:** enable default icon size to be changed ([#629](https://github.com/SAP/ui5-webcomponents/issues/629)) ([a44cdc6](https://github.com/SAP/ui5-webcomponents/commit/a44cdc6))
* **ui5-icon:** icon no longer flickers on IE ([#722](https://github.com/SAP/ui5-webcomponents/issues/722)) ([964af67](https://github.com/SAP/ui5-webcomponents/commit/964af67))
* **ui5-input:** inputs now support placeholder on IE ([#781](https://github.com/SAP/ui5-webcomponents/issues/781)) ([559109d](https://github.com/SAP/ui5-webcomponents/commit/559109d))
* **ui5-input:** use translated text ([#783](https://github.com/SAP/ui5-webcomponents/issues/783)) ([1e9a4e6](https://github.com/SAP/ui5-webcomponents/commit/1e9a4e6))
* **ui5-link:** fix link hover effect ([#803](https://github.com/SAP/ui5-webcomponents/issues/803)) ([46bfaf1](https://github.com/SAP/ui5-webcomponents/commit/46bfaf1))
* **ui5-multi-combobox:** overflow tokens correctly when not enough space ([#714](https://github.com/SAP/ui5-webcomponents/issues/714)) ([c67fe0a](https://github.com/SAP/ui5-webcomponents/commit/c67fe0a))
* **ui5-multi-combobox:** enable closing on icon click ([#719](https://github.com/SAP/ui5-webcomponents/issues/719)) ([8d98def](https://github.com/SAP/ui5-webcomponents/commit/8d98def))
* **ui5-switch:** don't mirror checkmark icon in RTL ([#742](https://github.com/SAP/ui5-webcomponents/issues/742)) ([ad2609d](https://github.com/SAP/ui5-webcomponents/commit/ad2609d))
* **ui5-tabcontainer:** fix selected tab text color in HCB ([#805](https://github.com/SAP/ui5-webcomponents/issues/805)) ([3ccf80e](https://github.com/SAP/ui5-webcomponents/commit/3ccf80e))
* **ui5-table:** call resize handler on initial rendering ([#625](https://github.com/SAP/ui5-webcomponents/issues/625)) ([c20c85c](https://github.com/SAP/ui5-webcomponents/commit/c20c85c))
* **ui5-token:** correct visual in RTL/Compact ([#804](https://github.com/SAP/ui5-webcomponents/issues/804)) ([71c9caa](https://github.com/SAP/ui5-webcomponents/commit/71c9caa))
* **ui5-tokenizer:** use i18nbundle instead of resource bundle ([#757](https://github.com/SAP/ui5-webcomponents/issues/757)) ([d6668bc](https://github.com/SAP/ui5-webcomponents/commit/d6668bc))
* **UI5Element:** parent elements properly await for children upgrade ([#645](https://github.com/SAP/ui5-webcomponents/issues/645)) ([0e976f8](https://github.com/SAP/ui5-webcomponents/commit/0e976f8))
* **CSS Transform:** host selector not removed when there is trailing whitespace ([#780](https://github.com/SAP/ui5-webcomponents/issues/780)) ([b5d8fde](https://github.com/SAP/ui5-webcomponents/commit/b5d8fde))
* **doc:** fix typos in docs ([#680](https://github.com/SAP/ui5-webcomponents/issues/680)) ([f884643](https://github.com/SAP/ui5-webcomponents/commit/f884643))
* **DOMEventHandler:** does not crash in edge cases ([#774](https://github.com/SAP/ui5-webcomponents/issues/774)) ([2576883](https://github.com/SAP/ui5-webcomponents/commit/2576883))
* **FocusHelper:** handles SVG's focus method on IE ([#721](https://github.com/SAP/ui5-webcomponents/issues/721)) ([52517c4](https://github.com/SAP/ui5-webcomponents/commit/52517c4))
* **InputFormSupport:** enable form support for nested input elements ([#656](https://github.com/SAP/ui5-webcomponents/issues/656)) ([57adb04](https://github.com/SAP/ui5-webcomponents/commit/57adb04))


### Code Refactoring

* **ui5-datepicker:** hide week number in Islamic, Buddhist and Japanese calendars ([#806](https://github.com/SAP/ui5-webcomponents/issues/806)) ([a5ccb80](https://github.com/SAP/ui5-webcomponents/commit/a5ccb80))
* **ui5-li:** remove background CSS Variable ([#802](https://github.com/SAP/ui5-webcomponents/issues/802)) ([9bf57ab](https://github.com/SAP/ui5-webcomponents/commit/9bf57ab))
* **ui5-multi-combobox:** replace validate-input with allow-custom-values ([#749](https://github.com/SAP/ui5-webcomponents/issues/749)) ([f501df4](https://github.com/SAP/ui5-webcomponents/commit/f501df4))
* **ui5-panel:** update toggle button visual design to Fiori 3 ([#794](https://github.com/SAP/ui5-webcomponents/pull/794))
* **ui5-popover:** improve layouting, styling and positioning ([#779](https://github.com/SAP/ui5-webcomponents/issues/779)) ([1d377ba](https://github.com/SAP/ui5-webcomponents/commit/1d377ba))
* **ui5-table:** component is now supported on IE 11 ([#704](https://github.com/SAP/ui5-webcomponents/pull/704))
* **ui5-table:** width property of column is removed ([#784](https://github.com/SAP/ui5-webcomponents/issues/784)) ([dedb51e](https://github.com/SAP/ui5-webcomponents/commit/dedb51e))
* **ui5-input,ui5-select,ui5-multicombobox,ui5-datepicker:** make the components share same CSS for input field styling ([#793](https://github.com/SAP/ui5-webcomponents/pull/793))
* **All components CSS:** Styles improvements and clean up
[#632](https://github.com/SAP/ui5-webcomponents/pull/632)
[#646](https://github.com/SAP/ui5-webcomponents/pull/646)
[#647](https://github.com/SAP/ui5-webcomponents/pull/647)
[#648](https://github.com/SAP/ui5-webcomponents/pull/648)
[#650](https://github.com/SAP/ui5-webcomponents/pull/650)
[#657](https://github.com/SAP/ui5-webcomponents/pull/657)
[#658](https://github.com/SAP/ui5-webcomponents/pull/658)
[#659](https://github.com/SAP/ui5-webcomponents/pull/659)
[#660](https://github.com/SAP/ui5-webcomponents/pull/660)
[#662](https://github.com/SAP/ui5-webcomponents/pull/662)
[#664](https://github.com/SAP/ui5-webcomponents/pull/664)
[#667](https://github.com/SAP/ui5-webcomponents/pull/667)
[#669](https://github.com/SAP/ui5-webcomponents/pull/669)
[#670](https://github.com/SAP/ui5-webcomponents/pull/670)
[#671](https://github.com/SAP/ui5-webcomponents/pull/671)
[#673](https://github.com/SAP/ui5-webcomponents/pull/673)
[#674](https://github.com/SAP/ui5-webcomponents/pull/674)
[#678](https://github.com/SAP/ui5-webcomponents/pull/678)
[#684](https://github.com/SAP/ui5-webcomponents/pull/684)
[#686](https://github.com/SAP/ui5-webcomponents/pull/686)
[#687](https://github.com/SAP/ui5-webcomponents/pull/687)
[#688](https://github.com/SAP/ui5-webcomponents/pull/688)
[#700](https://github.com/SAP/ui5-webcomponents/pull/700)
* **All Components:** adapt CSS for IE 11 and remove all IE11 duplicate CSS ([#704](https://github.com/SAP/ui5-webcomponents/pull/704))
* **i18n:** make i18n more efficient ([#720](https://github.com/SAP/ui5-webcomponents/pull/720))
* **i18n, Theming, CLDR:** unify assets handling ([#744](https://github.com/SAP/ui5-webcomponents/pull/744))
* **Configuration:** make configuration initial only ([#638](https://github.com/SAP/ui5-webcomponents/issues/638)) ([86ad25b](https://github.com/SAP/ui5-webcomponents/commit/86ad25b)))


### Features

* **ui5-datepicker:** adds public getter dateValue ([#726](https://github.com/SAP/ui5-webcomponents/issues/726)) ([1ba3e25](https://github.com/SAP/ui5-webcomponents/commit/1ba3e25))
* **ui5-datepicker:** implement ACC support ([#763](https://github.com/SAP/ui5-webcomponents/issues/763)) ([188627e](https://github.com/SAP/ui5-webcomponents/commit/188627e))
* **ui5-icon:** accessibility implementation ([#709](https://github.com/SAP/ui5-webcomponents/issues/709)) ([1357c16](https://github.com/SAP/ui5-webcomponents/commit/1357c16))
* **ui5-icon:** use SVG icons instead of icon font ([#649](https://github.com/SAP/ui5-webcomponents/issues/649)) ([b6352d8](https://github.com/SAP/ui5-webcomponents/commit/b6352d8))
* **ui5-list:** added new param for selectionChange event ([#798](https://github.com/SAP/ui5-webcomponents/issues/798)) ([28c4181](https://github.com/SAP/ui5-webcomponents/commit/28c4181))
* **ui5-select:** adds readonly property selectedOption ([#718](https://github.com/SAP/ui5-webcomponents/issues/718)) ([5d9a1ac](https://github.com/SAP/ui5-webcomponents/commit/5d9a1ac))
* **ui5-switch:** accessibility implementation ([#692](https://github.com/SAP/ui5-webcomponents/issues/692)) ([7304a31](https://github.com/SAP/ui5-webcomponents/commit/7304a31))
* **ui5-tabcontainer:** update ACC of header and content ([#756](https://github.com/SAP/ui5-webcomponents/issues/756)) ([8550365](https://github.com/SAP/ui5-webcomponents/commit/8550365))
* **ui5-link, ui5-textarea, ui5-input, ui5-checkbox, ui5-button, ui5-badge, ui5-busyindicator, ui5-messagestrip:** Improve accessibility of components ([#613](https://github.com/SAP/ui5-webcomponents/issues/613)) ([16568c2](https://github.com/SAP/ui5-webcomponents/commit/16568c2))
* **Configuration:** add configuration for calendar first day of the week ([#627](https://github.com/SAP/ui5-webcomponents/issues/627)) ([9c6df48](https://github.com/SAP/ui5-webcomponents/commit/9c6df48))
* add support for angular two way data binding ([#706](https://github.com/SAP/ui5-webcomponents/issues/706)) ([16820e4](https://github.com/SAP/ui5-webcomponents/commit/16820e4))
* **Tooling:** add new component script ([#747](https://github.com/SAP/ui5-webcomponents/issues/747)) ([171a36f](https://github.com/SAP/ui5-webcomponents/commit/171a36f))
* **docs:** maintain documentation for released version ([#400](https://github.com/SAP/ui5-webcomponents/issues/400)) ([476f8e2](https://github.com/SAP/ui5-webcomponents/commit/476f8e2))

### BREAKING CHANGES

* **ui5-popover:** stayOpenOnScroll is now removed
Popover will no longer close when the browser is scrolled
and its parent (opener) is visible in the viewport.
* **ui5-li:** CSS variable --ui5-listitem-background-color is removed,
set the desired background directly on the tag.
* **ui5-table:** width property of the ui5-table-column has been removed, use CSS to give width to the columns.
`<ui5-table-column style="width: 100px">...`
* **ui5-multi-combobox:** property validate-input is removed,
use the property allow-custom-values, note built in validation is enabled by default.
* **Theming:** Theming.js no longer has getTheme and setTheme methods, use the Configuration.js instead.
* **i18n, Theming:** unify assets handling ([#744](https://github.com/SAP/ui5-webcomponents/pull/744)).
Use `"@ui5/webcomponents/dist/json-imports/i18n.js"`, instead of `"@ui5/webcomponents/dist/MessageBundleAssets.js"` to enable i18n.
Use `"@ui5/webcomponents/dist/json-imports/Themes.js"`, instead of import `"@ui5/webcomponents/dist/ThemePropertiesProvider.js"` to enable theming.



# [1.0.0-rc.2](https://github.com/SAP/ui5-webcomponents/compare/v1.0.0-rc.1...v1.0.0-rc.2) (2019-07-04)

### Bug Fixes

* **popup:** remove body styles in onExitDOM ([#593](https://github.com/SAP/ui5-webcomponents/issues/593)) ([410b8f6](https://github.com/SAP/ui5-webcomponents/commit/410b8f6))
* **framework:** fix redundant event dispatch ([#599](https://github.com/SAP/ui5-webcomponents/issues/599)) ([dc0cda2](https://github.com/SAP/ui5-webcomponents/commit/dc0cda2))

### Code Refactoring

* **ui5-shellbar-item:** Rename press event to itemClick ([#606](https://github.com/SAP/ui5-webcomponents/issues/606)) ([5bfab39](https://github.com/SAP/ui5-webcomponents/commit/5bfab39))
* **ui5-popover, ui5-dialog**: remove noHeader property (#615) ([6a990a7](https://github.com/SAP/ui5-webcomponents/commit/6a990a7)), closes [#615](https://github.com/SAP/ui5-webcomponents/issues/615)


### BREAKING CHANGES

* **ui5-shellbar-item:** ui5-shellbar-item press event is renamed to itemClick
* **ui5-popover, ui5-dialog**: the property noHeader is removed, the presence of header is based on the values of "headerText" property and "header" slot



## [1.0.0-rc.1](https://github.com/SAP/ui5-webcomponents/compare/v0.13.1...v1.0.0-rc.1) (2019-06-28)

### Bug Fixes
* **ui5-button:** fix disable click events when disabled ([#586](https://github.com/SAP/ui5-webcomponents/pull/586))
* **ui5-select:** prevent scrolling when changing selection with arrows(#588](https://github.com/SAP/ui5-webcomponents/pull/588))

### Refactoring

* **all components:** remove press event in favour of click (#597](https://github.com/SAP/ui5-webcomponents/pull/597))

### BREAKING CHANGES
* **ui5-button:** BREAKING CHANGE: ui5-button press event is renamed to click (#597](https://github.com/SAP/ui5-webcomponents/pull/597))
* **ui5-card:** headerPress event is renamed to headerClick (#597](https://github.com/SAP/ui5-webcomponents/pull/597))
* **ui5-link:** press event is renamed to click (#597](https://github.com/SAP/ui5-webcomponents/pull/597))
* **ui5-list:** itemPress event is renamed to itemClick (#597](https://github.com/SAP/ui5-webcomponents/pull/597))
* **ui5-shellbar:** notificationsPress event is renamed to notificationsClick (#597](https://github.com/SAP/ui5-webcomponents/pull/597))
* **ui5-shellbar:** profilePress event is renamed to profileClick (#597](https://github.com/SAP/ui5-webcomponents/pull/597))
* **ui5-shellbar:** productSwitchPress event is renamed to productSwitchClick (#597](https://github.com/SAP/ui5-webcomponents/pull/597))
* **ui5-shellbar:** logoPress event is renamed to logoClick (#597](https://github.com/SAP/ui5-webcomponents/pull/597))
* **ui5-shellbar:** coPilotPress event is renamed to coPilotClick (#597](https://github.com/SAP/ui5-webcomponents/pull/597))
* **ui5-shellbar:** menuItemPress event is renamed to menuItemClick (#597](https://github.com/SAP/ui5-webcomponents/pull/597))
* **ui5-timeline-item:** ui5-timeline-item itemNamePress event is renamed to itemNameClick (#597](https://github.com/SAP/ui5-webcomponents/pull/597))

## [0.13.1](https://github.com/SAP/ui5-webcomponents/compare/v0.13.0...v0.13.1) (2019-06-22)

### Bug Fixes

* **ui5-table-column:** fix default slot rendering ([#579](https://github.com/SAP/ui5-webcomponents/pull/579))






# [0.13.0](https://github.com/SAP/ui5-webcomponents/compare/v0.12.0...v0.13.0) (2019-06-21)


### Bug Fixes

* **ui5-badge:** correct text font ([#535](https://github.com/SAP/ui5-webcomponents/issues/535)) ([3da0dd5](https://github.com/SAP/ui5-webcomponents/commit/3da0dd5))
* **ui5-icon:** correct RTL appearance ([#569](https://github.com/SAP/ui5-webcomponents/issues/569)) ([591d81a](https://github.com/SAP/ui5-webcomponents/commit/591d81a))
* **ui5-switch:** change getters names ([#566](https://github.com/SAP/ui5-webcomponents/issues/566)) ([2d94b60](https://github.com/SAP/ui5-webcomponents/commit/2d94b60))
* **ui5-tabcontainer:** set initial tab index ([#545](https://github.com/SAP/ui5-webcomponents/issues/545)) ([0127c2f](https://github.com/SAP/ui5-webcomponents/commit/0127c2f))
* **framework:** remove custom "falsy" checks from ifDefined ([#544](https://github.com/SAP/ui5-webcomponents/issues/544)) ([92a85fa](https://github.com/SAP/ui5-webcomponents/commit/92a85fa))
* **framework:** fix broken translations ([#548](https://github.com/SAP/ui5-webcomponents/issues/548)) ([37b2b07](https://github.com/SAP/ui5-webcomponents/commit/37b2b07))


### Code Refactoring

* **ui5-button:** rename type property to design ([#504](https://github.com/SAP/ui5-webcomponents/issues/504)) ([a62b471](https://github.com/SAP/ui5-webcomponents/commit/a62b471))
* **ui5-link:** rename type property to design ([#505](https://github.com/SAP/ui5-webcomponents/issues/505)) ([3965a00](https://github.com/SAP/ui5-webcomponents/commit/3965a00))
* **ui5-messagestrip:** rename hideIcon property to noIcon ([#507](https://github.com/SAP/ui5-webcomponents/issues/507)) ([2314fc3](https://github.com/SAP/ui5-webcomponents/commit/2314fc3))
* **ui5-popover:** hideHeader property renamed to noHeader ([#553](https://github.com/SAP/ui5-webcomponents/issues/553)) ([11dc3b1](https://github.com/SAP/ui5-webcomponents/commit/11dc3b1))
* **ui5-popover:** rename hideArrow property to noArrow ([#509](https://github.com/SAP/ui5-webcomponents/issues/509)) ([efff863](https://github.com/SAP/ui5-webcomponents/commit/efff863))
* **ui5-select:** change default slot from list items to options ([#532](https://github.com/SAP/ui5-webcomponents/issues/532)) ([2e4486b](https://github.com/SAP/ui5-webcomponents/commit/2e4486b))
* **ui5-switch:** rename type property to graphical ([#506](https://github.com/SAP/ui5-webcomponents/issues/506)) ([0040e85](https://github.com/SAP/ui5-webcomponents/commit/0040e85))
* **ui5-title:** remove unneeded accessibility role ([#573](https://github.com/SAP/ui5-webcomponents/pull/573))
* **ui5-button:** remove aria-disabled ([#558](https://github.com/SAP/ui5-webcomponents/pull/558))
* **framework:** stop calling focusout and focusin by convention ([#576](https://github.com/SAP/ui5-webcomponents/pull/558))


### Features

* **ui5-card:** add "headerInteractive" property ([#439](https://github.com/SAP/ui5-webcomponents/issues/439)) ([98f7075](https://github.com/SAP/ui5-webcomponents/commit/98f7075))
* **ui5-label:** expose font-weight property on root tag ([#534](https://github.com/SAP/ui5-webcomponents/issues/534)) ([88c794a](https://github.com/SAP/ui5-webcomponents/commit/88c794a))
* **ui5-li:** add info and infoState properties ([#539](https://github.com/SAP/ui5-webcomponents/issues/539)) ([f1d8a85](https://github.com/SAP/ui5-webcomponents/commit/f1d8a85))
* **ui5-select:** add form support([#565](https://github.com/SAP/ui5-webcomponents/issues/565)) ([89e3508](https://github.com/SAP/ui5-webcomponents/commit/89e3508))


### BREAKING CHANGES

* **ui5-select:** the parameter of the change event is now called "selectedOption"; ui5-select enforces ui5-option as children in the metadata
* **ui5-select:** Use ui5-option instead of ui5-li in ui5-select
* **ui5-link:** property "type" is removed, use property design
* **ui5-button:** property "type" is removed, use property design
* **ui5-switch:** property "type" is removed, use property graphical
* **ui5-messagestrip:** property hideIcon is renamed to noIcon
* **ui5-popover:** property hideIcon is renamed to noArrow
* **ui5-popover:**property hideIcon is renamed to noHeader





# [0.12.0](https://github.com/SAP/ui5-webcomponents/compare/v0.11.0...v0.12.0) (2019-06-10)


### Bug Fixes

* all: hide components when hidden attribute is set ([#464](https://github.com/SAP/ui5-webcomponents/issues/464)) ([f7f07d2](https://github.com/SAP/ui5-webcomponents/commit/f7f07d2))
* access DOM in connectedCallback instead of constructor ([#524](https://github.com/SAP/ui5-webcomponents/issues/524)) ([0f3b8e4](https://github.com/SAP/ui5-webcomponents/commit/0f3b8e4))
* do not use assignedElements ([#432](https://github.com/SAP/ui5-webcomponents/issues/432)) ([c54c812](https://github.com/SAP/ui5-webcomponents/commit/c54c812))
* **ui5-table:** fix scrolling on space ([#232](https://github.com/SAP/ui5-webcomponents/issues/232)) ([cd63e9a](https://github.com/SAP/ui5-webcomponents/commit/cd63e9a))
* **ui5-button:** bold text in fiori_3 when button is emphasized ([#512](https://github.com/SAP/ui5-webcomponents/issues/512)) ([53cdc93](https://github.com/SAP/ui5-webcomponents/commit/53cdc93))
* **ui5-button:** fix focus outline color of emphasized button ([#499](https://github.com/SAP/ui5-webcomponents/issues/499)) ([1e0690c](https://github.com/SAP/ui5-webcomponents/commit/1e0690c))
* **ui5-checkbox:** fix touchArea size ([#448](https://github.com/SAP/ui5-webcomponents/issues/448)) ([8831139](https://github.com/SAP/ui5-webcomponents/commit/8831139))
* **ui5-li:** remove active state onmouseup ([#525](https://github.com/SAP/ui5-webcomponents/issues/525)) ([a07880d](https://github.com/SAP/ui5-webcomponents/commit/a07880d))
* **ui5-list:** fix list footer font family ([#494](https://github.com/SAP/ui5-webcomponents/issues/494)) ([5543d30](https://github.com/SAP/ui5-webcomponents/commit/5543d30))
* **ui5-messagestrip:** improve screen reader announcements ([#467](https://github.com/SAP/ui5-webcomponents/issues/467)) ([b68443c](https://github.com/SAP/ui5-webcomponents/commit/b68443c))
* **ui5-multi-combobox:** docs and API improvements ([#438](https://github.com/SAP/ui5-webcomponents/issues/438)) ([c559ac0](https://github.com/SAP/ui5-webcomponents/commit/c559ac0))
* **ui5-radiobutton:** make readonly radiobuttons not selectable via keyboard ([#500](https://github.com/SAP/ui5-webcomponents/issues/500)) ([2261f1c](https://github.com/SAP/ui5-webcomponents/commit/2261f1c))
* **ui5-select:** fix component clickable area ([#462](https://github.com/SAP/ui5-webcomponents/issues/462)) ([9c59de5](https://github.com/SAP/ui5-webcomponents/commit/9c59de5))
* **ui5-tabcontainer:** remove typo from component template ([#446](https://github.com/SAP/ui5-webcomponents/issues/446)) ([e701562](https://github.com/SAP/ui5-webcomponents/commit/e701562))


### Code Refactoring

* **ui5-button:** remove activeIcon property ([#513](https://github.com/SAP/ui5-webcomponents/issues/513)) ([8d8c343](https://github.com/SAP/ui5-webcomponents/commit/8d8c343))


### Features

* i18n: inline English texts if no translation is fetched ([#479](https://github.com/SAP/ui5-webcomponents/issues/479)) ([abfb221](https://github.com/SAP/ui5-webcomponents/commit/abfb221))
* **base:** implement late validation ([#522](https://github.com/SAP/ui5-webcomponents/issues/522)) ([c452d60](https://github.com/SAP/ui5-webcomponents/commit/c452d60))
* **ui5-badge:** initial implementation ([#521](https://github.com/SAP/ui5-webcomponents/issues/521)) ([8496211](https://github.com/SAP/ui5-webcomponents/commit/8496211))
* **ui5-busyindicator:** initial implementation ([#416](https://github.com/SAP/ui5-webcomponents/issues/416)) ([6b6b544](https://github.com/SAP/ui5-webcomponents/commit/6b6b544))
* **ui5-busyindicator:** introduce active property and simplify usage ([#519](https://github.com/SAP/ui5-webcomponents/issues/519)) ([ff59a98](https://github.com/SAP/ui5-webcomponents/commit/ff59a98))
* **ui5-li:** parameterize listitembase border bottom ([#520](https://github.com/SAP/ui5-webcomponents/issues/520)) ([da1c430](https://github.com/SAP/ui5-webcomponents/commit/da1c430))
* **ui5-table:** add noDataText for ui5-table without rows ([#402](https://github.com/SAP/ui5-webcomponents/issues/402)) ([907d513](https://github.com/SAP/ui5-webcomponents/commit/907d513)), closes [#389](https://github.com/SAP/ui5-webcomponents/issues/389)


### BREAKING CHANGES

* **ui5-button:** activeIcon property is removed





## [0.11.1](https://github.com/SAP/ui5-webcomponents/compare/v0.11.0...v0.11.1) (2019-05-30)

**Note:** No code changes.





# [0.11.0](https://github.com/SAP/ui5-webcomponents/compare/v0.10.1...v0.11.0) (2019-05-22)


### Bug Fixes

* **ui5-checkbox:** correct default values of the boolean props  ([#408](https://github.com/SAP/ui5-webcomponents/issues/408)) ([9bdd2c5](https://github.com/SAP/ui5-webcomponents/commit/9bdd2c5))
* **ui5-messagestrip:** remove height 100% from element tag ([#387](https://github.com/SAP/ui5-webcomponents/issues/387)) ([4b64a9c](https://github.com/SAP/ui5-webcomponents/commit/4b64a9c))
* **ui5-panel:** add missing dependency for ui5-icon ([#406](https://github.com/SAP/ui5-webcomponents/issues/406)) ([650bcb0](https://github.com/SAP/ui5-webcomponents/commit/650bcb0))
* fix broken child property observation ([#423](https://github.com/SAP/ui5-webcomponents/issues/423)) ([b3e3b3f](https://github.com/SAP/ui5-webcomponents/commit/b3e3b3f))
* fix API build for composite components  ([#391](https://github.com/SAP/ui5-webcomponents/issues/391)) ([dcb829b](https://github.com/SAP/ui5-webcomponents/commit/dcb829b))
* prevent dual event dispatching in no conflict mode ([#363](https://github.com/SAP/ui5-webcomponents/issues/363)) ([4cbe3de](https://github.com/SAP/ui5-webcomponents/commit/4cbe3de))
* update tab container documentation ([#370](https://github.com/SAP/ui5-webcomponents/issues/370)) ([7117430](https://github.com/SAP/ui5-webcomponents/commit/7117430)), closes [#369](https://github.com/SAP/ui5-webcomponents/issues/369)


### Code Refactoring

* make custom CSS theme independent ([#386](https://github.com/SAP/ui5-webcomponents/issues/386)) ([d6b4ab5](https://github.com/SAP/ui5-webcomponents/commit/d6b4ab5))
* **ui5-datepicker:** rename event 'liveChange' to 'input' ([#394](https://github.com/SAP/ui5-webcomponents/pull/394))
* **ui5-panel:** remove backgroundDesign property ([#384](https://github.com/SAP/ui5-webcomponents/pull/384))
* **ui5-panel:** remove backgroundDesign property ([#383](https://github.com/SAP/ui5-webcomponents/pull/383))
* **ui5-checkbox:** rename "readOnly" to "readonly" ([#413](https://github.com/SAP/ui5-webcomponents/pull/413))
* **ui5-radiobutton:** rename "readOnly" to "readonly" ([#413](https://github.com/SAP/ui5-webcomponents/pull/413))


### Features

* **ui5-multi-combobox:** initial implementation ([#379](https://github.com/SAP/ui5-webcomponents/issues/379)) ([115900b](https://github.com/SAP/ui5-webcomponents/commit/115900b))
* **ui5-list:** selectionChange event provides previously selected items ([#418](https://github.com/SAP/ui5-webcomponents/issues/418)) ([f0fc8f2](https://github.com/SAP/ui5-webcomponents/commit/f0fc8f2))
* **ui5-shellbar:** API improvements ([#421](https://github.com/SAP/ui5-webcomponents/issues/421)) ([e0ff36d](https://github.com/SAP/ui5-webcomponents/commit/e0ff36d))
* add CSS variables section in API Ref ([#399](https://github.com/SAP/ui5-webcomponents/issues/399)) ([e198fa5](https://github.com/SAP/ui5-webcomponents/commit/e198fa5))
* add data-ui5-compact-size attribute to root when compact is set ([#382](https://github.com/SAP/ui5-webcomponents/issues/382)) ([cbf00a8](https://github.com/SAP/ui5-webcomponents/commit/cbf00a8))
* fetch ui5-datepicker assets from CDN ([#420](https://github.com/SAP/ui5-webcomponents/issues/420)) ([1f62dda](https://github.com/SAP/ui5-webcomponents/commit/1f62dda))
* simplify slots usage ([e4907b9](https://github.com/SAP/ui5-webcomponents/commit/e4907b9))


### BREAKING CHANGES

* **ui5-list:** the "selectionChange" event param "items" has been renamed to "selectedItems".
* **ui5-list:** the "backgroundDesign" property has been removed, use the corresponding
CSS variable (--_ui5_listitem_background_color) to alter the list items` background.
* **ui5-panel:** the "backgroundDesign" property has been removed, use the corresponding
CSS variables (--_ui5_panel_background_color) to alter the panel background.
* **ui5-datepicker:** 'liveChange' event has been renamed to 'input'.
* **ui5-checkbox:** property "readOnly" has been renamed to "readonly".
* **ui5-radiobutton:** property "readOnly" has been renamed to "readonly".
* the signature of the addCustomCSS method exported by "@ui5/webcomponents-base/Theming.js" is changed from addCustomCSS(tag, theme, css) to addCustomCSS(tag, css)





## [0.10.1](https://github.com/SAP/ui5-webcomponents/compare/v0.10.0...v0.10.1) (2019-04-24)


### Bug Fixes

* **ui5-li:** fix styles import extension ([#351](https://github.com/SAP/ui5-webcomponents/issues/351)) ([4fae1ff](https://github.com/SAP/ui5-webcomponents/commit/4fae1ff))
* **ui5-messagestrip:** fix layout in ie ([#353](https://github.com/SAP/ui5-webcomponents/issues/353)) ([ca5f62c](https://github.com/SAP/ui5-webcomponents/commit/ca5f62c))
* switch theme for single imported components ([#356](https://github.com/SAP/ui5-webcomponents/issues/356)) ([dcd64a9](https://github.com/SAP/ui5-webcomponents/commit/dcd64a9))
* **ui5-radiobutton:** fix single selection within group ([#355](https://github.com/SAP/ui5-webcomponents/issues/355)) ([371fb88](https://github.com/SAP/ui5-webcomponents/commit/371fb88))
* **ui5-select:** preselect first item if none is selected ([#358](https://github.com/SAP/ui5-webcomponents/issues/358)) ([3d18420](https://github.com/SAP/ui5-webcomponents/commit/3d18420))
* **ui5-togglebutton:** add base styles ([#352](https://github.com/SAP/ui5-webcomponents/issues/352)) ([f4dee1c](https://github.com/SAP/ui5-webcomponents/commit/f4dee1c))


### Code Refactoring

* **ui5-radiobutton:** improve group handling ([#348](https://github.com/SAP/ui5-webcomponents/issues/348)) ([4d7d9c3](https://github.com/SAP/ui5-webcomponents/commit/4d7d9c3))
* **ui5-radiobutton:** enable radio button form support ([#357](https://github.com/SAP/ui5-webcomponents/issues/357)) ([96a0517](https://github.com/SAP/ui5-webcomponents/commit/96a0517))


### BREAKING CHANGES

* **ui5-radiobutton:** the property "group" is replaced by the "name" property.





# [0.10.0](https://github.com/SAP/ui5-webcomponents/compare/v0.9.0...v0.10.0) (2019-04-22)


### Bug Fixes

* **configuration:** fix map literals ([#324](https://github.com/SAP/ui5-webcomponents/issues/324)) ([515121f](https://github.com/SAP/ui5-webcomponents/commit/515121f))
* **docs:** fix card sample page ([#305](https://github.com/SAP/ui5-webcomponents/issues/305)) ([d91f237](https://github.com/SAP/ui5-webcomponents/commit/d91f237))
* add missing dependency to jquery-shim in resource bundle ([#242](https://github.com/SAP/ui5-webcomponents/issues/242)) ([3c5bd6f](https://github.com/SAP/ui5-webcomponents/commit/3c5bd6f))
* **ui5-button:** fix height ([#331](https://github.com/SAP/ui5-webcomponents/issues/331)) ([98a2c4e](https://github.com/SAP/ui5-webcomponents/commit/98a2c4e))
* **ui5-button:** fix width in ie11 ([#325](https://github.com/SAP/ui5-webcomponents/issues/325)) ([b00ab52](https://github.com/SAP/ui5-webcomponents/commit/b00ab52))
* **ui5-button:** removes active state after tabbing on an pressed button ([#335](https://github.com/SAP/ui5-webcomponents/issues/335)) ([0776e01](https://github.com/SAP/ui5-webcomponents/commit/0776e01))
* **ui5-checkbox:** correct setting of aria-readonly ([#220](https://github.com/SAP/ui5-webcomponents/issues/220)) ([c1f98a3](https://github.com/SAP/ui5-webcomponents/commit/c1f98a3))
* **ui5-checkbox:** fIx checkbox width in ie11 ([d58320b](https://github.com/SAP/ui5-webcomponents/commit/d58320b))
* **ui5-checkbox:** fixes issues with focus outline and wrapping ([#238](https://github.com/SAP/ui5-webcomponents/issues/238)) ([02bb56e](https://github.com/SAP/ui5-webcomponents/commit/02bb56e))
* **ui5-checkbox:** remove background from touchable area ([#226](https://github.com/SAP/ui5-webcomponents/issues/226)) ([3412ef3](https://github.com/SAP/ui5-webcomponents/commit/3412ef3))
* **ui5-li:** fix delete list item button height ([#221](https://github.com/SAP/ui5-webcomponents/issues/221)) ([a008022](https://github.com/SAP/ui5-webcomponents/commit/a008022))
* **ui5-li:** fix description text in compact mode ([#211](https://github.com/SAP/ui5-webcomponents/issues/211)) ([cadf996](https://github.com/SAP/ui5-webcomponents/commit/cadf996))
* checks navigator language for rtl enabling ([#253](https://github.com/SAP/ui5-webcomponents/issues/253)) ([c29d970](https://github.com/SAP/ui5-webcomponents/commit/c29d970))
* correct constructable stylesheet feature detection ([#271](https://github.com/SAP/ui5-webcomponents/issues/271)) ([816e6de](https://github.com/SAP/ui5-webcomponents/commit/816e6de))
* make fallback script work with multiple variables per line ([#252](https://github.com/SAP/ui5-webcomponents/issues/252)) ([298a165](https://github.com/SAP/ui5-webcomponents/commit/298a165))
* prevent merging of :host(tag) and tag css rules ([#349](https://github.com/SAP/ui5-webcomponents/issues/349)) ([f23085c](https://github.com/SAP/ui5-webcomponents/commit/f23085c))
* select correctly opens on click ([#235](https://github.com/SAP/ui5-webcomponents/issues/235)) ([a4915df](https://github.com/SAP/ui5-webcomponents/commit/a4915df))
* slots work in Safari ([#230](https://github.com/SAP/ui5-webcomponents/issues/230)) ([79445d0](https://github.com/SAP/ui5-webcomponents/commit/79445d0))
* **ui5-li:** fix typo ([#224](https://github.com/SAP/ui5-webcomponents/issues/224)) ([cb781f1](https://github.com/SAP/ui5-webcomponents/commit/cb781f1))
* **ui5-li-custom:** enable setting height of the custom content ([#311](https://github.com/SAP/ui5-webcomponents/issues/311)) ([76bf9f3](https://github.com/SAP/ui5-webcomponents/commit/76bf9f3))
* **ui5-link:** noreferrer for cross-origin links ([#202](https://github.com/SAP/ui5-webcomponents/issues/202)) ([5902704](https://github.com/SAP/ui5-webcomponents/commit/5902704))
* **ui5-panel:** correct inon size on small screens ([#213](https://github.com/SAP/ui5-webcomponents/issues/213)) ([a98f544](https://github.com/SAP/ui5-webcomponents/commit/a98f544))
* **ui5-radiobutton:** fix focus in ie11 ([#327](https://github.com/SAP/ui5-webcomponents/issues/327)) ([b59abd6](https://github.com/SAP/ui5-webcomponents/commit/b59abd6))
* **ui5-radiobutton:** fix keyboard handling on TAB/SHIFT+TAB ([#231](https://github.com/SAP/ui5-webcomponents/issues/231)) ([f2a18cf](https://github.com/SAP/ui5-webcomponents/commit/f2a18cf))
* **ui5-shellbar:** add missing dependency to ui5-popover ([#234](https://github.com/SAP/ui5-webcomponents/issues/234)) ([912f434](https://github.com/SAP/ui5-webcomponents/commit/912f434))
* **ui5-shellbar:** pass correct values for events details ([#298](https://github.com/SAP/ui5-webcomponents/issues/298)) ([2641ec6](https://github.com/SAP/ui5-webcomponents/commit/2641ec6))
* transform css files to es6 modules ([#306](https://github.com/SAP/ui5-webcomponents/issues/306)) ([dbb98c8](https://github.com/SAP/ui5-webcomponents/commit/dbb98c8))
* **ui5-shellbar:** set correct font-family to primary title ([#228](https://github.com/SAP/ui5-webcomponents/issues/228)) ([839a66e](https://github.com/SAP/ui5-webcomponents/commit/839a66e))
* **ui5-switch:** fix layouting on IE ([#223](https://github.com/SAP/ui5-webcomponents/issues/223)) ([1111dbf](https://github.com/SAP/ui5-webcomponents/commit/1111dbf))
* **ui5-togglebutton:** correct default btn hover and text hover ([#332](https://github.com/SAP/ui5-webcomponents/issues/332)) ([280f85d](https://github.com/SAP/ui5-webcomponents/commit/280f85d))


### Code Refactoring

* remove ui5-toolbar ([#198](https://github.com/SAP/ui5-webcomponents/issues/198)) ([2e14428](https://github.com/SAP/ui5-webcomponents/commit/2e14428))
* **base:** flatten project structure ([#227](https://github.com/SAP/ui5-webcomponents/issues/227)) ([0e8e460](https://github.com/SAP/ui5-webcomponents/commit/0e8e460))
* **ui5-panel:** rename the expand event to toggle ([#216](https://github.com/SAP/ui5-webcomponents/issues/216)) ([2608100](https://github.com/SAP/ui5-webcomponents/commit/2608100))
* **ui5-shellbar:** rename press handlers param ([#300](https://github.com/SAP/ui5-webcomponents/issues/300)) ([5d1c920](https://github.com/SAP/ui5-webcomponents/commit/5d1c920))
* **ui5-tabcontainer:** refactor the component ([#318](https://github.com/SAP/ui5-webcomponents/issues/318)) ([aa516ff](https://github.com/SAP/ui5-webcomponents/commit/aa516ff))
* **ui5-timeline:** change timestamp property to subtitleText ([#321](https://github.com/SAP/ui5-webcomponents/issues/321)) ([287548e](https://github.com/SAP/ui5-webcomponents/commit/287548e))


### Features

* adds static method styles to base class ([#345](https://github.com/SAP/ui5-webcomponents/issues/345)) ([b61860f](https://github.com/SAP/ui5-webcomponents/commit/b61860f))
* **ui5-select:** selection can be changed with arrows while closed ([#254](https://github.com/SAP/ui5-webcomponents/issues/254)) ([bb46034](https://github.com/SAP/ui5-webcomponents/commit/bb46034))
* enable form support and name attribute for inputs ([#337](https://github.com/SAP/ui5-webcomponents/issues/337)) ([188d231](https://github.com/SAP/ui5-webcomponents/commit/188d231))
* framework-level support for CSS Custom Properties ([#196](https://github.com/SAP/ui5-webcomponents/issues/196)) ([291829a](https://github.com/SAP/ui5-webcomponents/commit/291829a))
* make css vars fallback script work with embedded vars ([#251](https://github.com/SAP/ui5-webcomponents/issues/251)) ([f81c117](https://github.com/SAP/ui5-webcomponents/commit/f81c117))
* **ui5-card:** fires headerPress event upon header click ([#250](https://github.com/SAP/ui5-webcomponents/issues/250)) ([59b80be](https://github.com/SAP/ui5-webcomponents/commit/59b80be))
* **ui5-panel:** make the header clickable ([#204](https://github.com/SAP/ui5-webcomponents/issues/204)) ([c5c1786](https://github.com/SAP/ui5-webcomponents/commit/c5c1786))
* **ui5-select:** select opens with space ([#245](https://github.com/SAP/ui5-webcomponents/issues/245)) ([a6c4d29](https://github.com/SAP/ui5-webcomponents/commit/a6c4d29))
* provide named exports for some base modules ([#347](https://github.com/SAP/ui5-webcomponents/issues/347)) ([2e2439a](https://github.com/SAP/ui5-webcomponents/commit/2e2439a))
* **ui5-shellbar:** adds logoPress and coPilotPress events ([#301](https://github.com/SAP/ui5-webcomponents/issues/301)) ([f221123](https://github.com/SAP/ui5-webcomponents/commit/f221123))
* **ui5-shellbar:** menuItems slot and menuItemPress event ([#317](https://github.com/SAP/ui5-webcomponents/issues/317)) ([f24f78b](https://github.com/SAP/ui5-webcomponents/commit/f24f78b))


### BREAKING CHANGES

* **ui5-timeline:** 'timestamp' and 'timeFormat'  properties are removed.
Instead use subtitle-text property and directly format the text as
desired.
* the ui5-toolbar component is removed, we recommend using div or similar HTML tag in combination with flex instead.
* **ui5-panel:** the expand event is removed, use the toggle event instead.
* **ui5-tabcontainer:** 'headerMode' property is removed. All Tabs by Fiori guidelines are rendered in
inline mode
* **ui5-tabcontainer:** 'headerBackgroundDesign' property is removed
* **ui5-tabcontainer:** 'backgroundDesign' property is removed
* **ui5-tabcontainer:** 'content' property is removed. Instead if you want to use the TabContainer as
a filter just use it with 'collapsed' set to true and 'fixed' set to true
* **ui5-tabcontainer:** 'TabContainerDensityMode' is deleted. To set different size modes use ?sap-ui-compactSize=true
* **ui5-tabcontainer:** 'selectedIndex' property is removed. Instead use 'selected' property of the Tab
* **ui5-tabcontainer:** Tab's 'count' property is removed. Instead use the additional-text property
* **ui5-tabcontainer:** Tab's 'design' property is removed
* **ui5-shellbar:** titlePress event is removed and replaced by menuItems slot.
* **base:** All files required from the base now have different
path. sap/ui/webcomponents/base/ is removed.

old: @ui5/webcomponents-base/src/sap/ui/webcomponents/base/WebComponent
new: @ui5/webcomponents-base/src/WebComponent




# [0.9.0](https://github.com/SAP/ui5-webcomponents/compare/v0.8.0...v0.9.0) (2019-03-18)


### Features

* **ui5-messagestrip:** initial implementation ([#80](https://github.com/SAP/ui5-webcomponents/issues/80)) ([cbc9c75](https://github.com/SAP/ui5-webcomponents/commit/cbc9c75))


### Bug Fixes

* correct calling unexisting method ([#157](https://github.com/SAP/ui5-webcomponents/issues/157)) ([0a8c8cd](https://github.com/SAP/ui5-webcomponents/commit/0a8c8cd))
* correct device detection error on mobile ([#143](https://github.com/SAP/ui5-webcomponents/issues/143)) ([857754e](https://github.com/SAP/ui5-webcomponents/commit/857754e))
* fix HCB colours for Icon, TextArea and TableCell content ([#128](https://github.com/SAP/ui5-webcomponents/issues/128)) ([9fb7dc5](https://github.com/SAP/ui5-webcomponents/commit/9fb7dc5))
* **ui5-datepicker:** enable day selection in IE ([#162](https://github.com/SAP/ui5-webcomponents/issues/162)) ([18a3c43](https://github.com/SAP/ui5-webcomponents/commit/18a3c43))
* **ui5-icon:** correct icon graphic vertical alignment in IE ([#142](https://github.com/SAP/ui5-webcomponents/issues/142)) ([98be562](https://github.com/SAP/ui5-webcomponents/commit/98be562))
* **ui5-input:** fire change in sync with the native input ([#168](https://github.com/SAP/ui5-webcomponents/issues/168)) ([55fa533](https://github.com/SAP/ui5-webcomponents/commit/55fa533))
* **ui5-label:** enable text truncation in IE ([#136](https://github.com/SAP/ui5-webcomponents/issues/136)) ([ef00170](https://github.com/SAP/ui5-webcomponents/commit/ef00170))
* fix source maps ([#181](https://github.com/SAP/ui5-webcomponents/issues/181)) ([7084c96](https://github.com/SAP/ui5-webcomponents/commit/7084c96))
* **ui5-list:** correct backward navigation with SHIFT+TAB ([#193](https://github.com/SAP/ui5-webcomponents/issues/193)) ([037409d](https://github.com/SAP/ui5-webcomponents/commit/037409d))


### Code Refactoring

* **ui5-input:** fire input, instead of liveChange ([#159](https://github.com/SAP/ui5-webcomponents/issues/159)) ([b8d978a](https://github.com/SAP/ui5-webcomponents/commit/b8d978a))


### BREAKING CHANGES

* **ui5-input:** liveChange event is no longer fired, listen for the input event instead.


### NOTABLE CHANGES
* The bundle size is reduced by removing unused functionality of core modules and making greater use of tree shaking.




# [0.8.0](https://github.com/SAP/ui5-webcomponents/compare/v0.7.0...v0.8.0) (2019-03-01)


### Features

* **ui5-card:** add avatar property ([#45](https://github.com/SAP/ui5-webcomponents/issues/45)) ([cdaf549](https://github.com/SAP/ui5-webcomponents/commit/cdaf549))
* **ui5-li:** add description property ([#54](https://github.com/SAP/ui5-webcomponents/issues/54)) ([fe79710](https://github.com/SAP/ui5-webcomponents/commit/fe79710))
* **ui5-select:** initial implementation
* **ui5-shellbar:** initial implementation and improvements ([#72](https://github.com/SAP/ui5-webcomponents/issues/72)) ([fdc743d](https://github.com/SAP/ui5-webcomponents/commit/fdc743d))
* **ui5-switch:** initial implementation ([#102](https://github.com/SAP/ui5-webcomponents/issues/102)) ([280d35a](https://github.com/SAP/ui5-webcomponents/commit/280d35a))
* **ui5-timeline:** initial implementation
* load Web Components polyfill on demand ([#96](https://github.com/SAP/ui5-webcomponents/issues/96)) ([98b5174](https://github.com/SAP/ui5-webcomponents/commit/98b5174))


### Bug Fixes

* **eventing:** remove unnecessary tag name check ([#16](https://github.com/SAP/ui5-webcomponents/issues/16)) ([3e39a70](https://github.com/SAP/ui5-webcomponents/commit/3e39a70))
* **ui5-checkbox:** wait for ui5-label definition ([#115](https://github.com/SAP/ui5-webcomponents/issues/115)) ([14067bd](https://github.com/SAP/ui5-webcomponents/commit/14067bd))
* **ui5-checkbox:** show default cursor over text ([#9](https://github.com/SAP/ui5-webcomponents/issues/9)) ([28d5ac0](https://github.com/SAP/ui5-webcomponents/commit/28d5ac0))
* **ui5-checkbox:** fix focus outline appearance in Compact + RTL ([#23](https://github.com/SAP/ui5-webcomponents/issues/23)) ([9b18490](https://github.com/SAP/ui5-webcomponents/commit/9b18490))
* **ui5-datepicker:** display extreme values correctly ([#75](https://github.com/SAP/ui5-webcomponents/issues/75)) ([d1c7259](https://github.com/SAP/ui5-webcomponents/commit/d1c7259))
* **ui5-datepicker:** fix icon color in pressed state ([#63](https://github.com/SAP/ui5-webcomponents/issues/63)) ([a03a51a](https://github.com/SAP/ui5-webcomponents/commit/a03a51a))
* **ui5-input:** fix slotted icon default size ([#105](https://github.com/SAP/ui5-webcomponents/issues/105)) ([0cfe254](https://github.com/SAP/ui5-webcomponents/commit/0cfe254))
* **ui5-li:** fix height with title and description in Compact ([#70](https://github.com/SAP/ui5-webcomponents/issues/70)) ([db17c71](https://github.com/SAP/ui5-webcomponents/commit/db17c71))
* **ui5-popover:** fix appearance on ios within iframe ([#60](https://github.com/SAP/ui5-webcomponents/issues/60)) ([a62c198](https://github.com/SAP/ui5-webcomponents/commit/a62c198))
* **ui5-popover:** fix bottom border radius ([#34](https://github.com/SAP/ui5-webcomponents/issues/34)) ([2daefc1](https://github.com/SAP/ui5-webcomponents/commit/2daefc1))
* **ui5-radiobutton:** fix focus lost upon text click in IE ([#24](https://github.com/SAP/ui5-webcomponents/issues/24)) ([7a00caf](https://github.com/SAP/ui5-webcomponents/commit/7a00caf))
* **ui5-radiobutton:** fix focus outline in Compact & RTL ([#18](https://github.com/SAP/ui5-webcomponents/issues/18)) ([9afa81b](https://github.com/SAP/ui5-webcomponents/commit/9afa81b))
* **ui5-select:** prevent scrolling upon ALt+ArrowDown/Up/F4 ([#7](https://github.com/SAP/ui5-webcomponents/issues/7)) ([c22eae1](https://github.com/SAP/ui5-webcomponents/commit/c22eae1))
* **ui5-select:** fix selection, styling and playground sample ([#4](https://github.com/SAP/ui5-webcomponents/issues/4)) ([f0a90b7](https://github.com/SAP/ui5-webcomponents/commit/f0a90b7))
* **ui5-tabcontainer:** wait for ui5-popover definition ([#46](https://github.com/SAP/ui5-webcomponents/issues/46)) ([a6f5c2b](https://github.com/SAP/ui5-webcomponents/commit/a6f5c2b))
* **ui5-tabcontainer:** click on left arrow correctly scrolls to left in textOnly ([#97](https://github.com/SAP/ui5-webcomponents/issues/97)) ([a89de1a](https://github.com/SAP/ui5-webcomponents/commit/a89de1a))
* **ui5-textarea:** focus outline with character counter ([#32](https://github.com/SAP/ui5-webcomponents/issues/32)) ([0900483](https://github.com/SAP/ui5-webcomponents/commit/0900483))
* fix broken bundle on Edge [#64](https://github.com/SAP/ui5-webcomponents/issues/64) ([73117c7](https://github.com/SAP/ui5-webcomponents/commit/73117c7))
* do not modify the HTML tag ([#49](https://github.com/SAP/ui5-webcomponents/issues/49)) ([17f30b7](https://github.com/SAP/ui5-webcomponents/commit/17f30b7))
* fix playground theme switch ([#62](https://github.com/SAP/ui5-webcomponents/issues/62)) ([5212a87](https://github.com/SAP/ui5-webcomponents/commit/5212a87))
* fix playground home redirect ([#6](https://github.com/SAP/ui5-webcomponents/issues/6)) ([8c87778](https://github.com/SAP/ui5-webcomponents/commit/8c87778))
* prevent throwing exception if slotted child does not have listenFor ([#92](https://github.com/SAP/ui5-webcomponents/issues/92)) ([4ffce64](https://github.com/SAP/ui5-webcomponents/commit/4ffce64))
* unknown slots no longer cause an error ([#90](https://github.com/SAP/ui5-webcomponents/issues/90)) ([a033326](https://github.com/SAP/ui5-webcomponents/commit/a033326))


### BREAKING CHANGES

* any applications that wants to support Edge and/or IE11 should now import the respective browser support module. For details, see the [README.md](/README.md#browser-support)
* **ui5-tabcontainer:** The TabContainer "selected-key" and Tab "key" properties are removed. Use TabContainer "selectedIndex" property (selected-index attribute) to set and get the selected tab.
* addCustomCSS is no longer on the Core object. Use Theming instead. [#58](https://github.com/SAP/ui5-webcomponents/pull/58)


### NOTABLE CHANGES
* The bundle size is reduced by removing unused functionality of core modules and making greater use of tree shaking.