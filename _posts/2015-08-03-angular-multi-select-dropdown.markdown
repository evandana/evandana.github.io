---
layout: post
title:  "AngularJS Multi-select Dropdown"
date:   2015-08-03 13:35:58
categories: angularJS ui
---

Design guidelines require a multi-select dropdown that shows all the options as selectable and tallies the selections as a comma-separated, concatenated string in the dropdown's consolidated view.

## The TARGET

![Multi-select dropdown target]({{ site.url }}/assets/uiselect/target.png)

Basic Requirements
 * Multi-select
 * Summarizes selections in collapsed view
 * Shows all items in dropdown and can toggle selection state
 * Cross-browser compatible
 * Skinnable
 * AngularJS

## The CONTENDERS

 * [UI-Select][uiSelect]
 * [Angularjs Dropdown Multiselect][ngDropdown]
 * [angular-multi-select][ngMultiSelect]

___

### UI-Select

Previously [UI-Select2][ngSelect2]
[Documentation][uiSelect]

![UI-Select snapshot]({{ site.url }}/assets/uiselect/uiselect.png)

#### Overview

This 100% AngularJS solution provides a customizable multi-select dropdown angular directive. Once an item has been selected, it is removed from the dropdown list and becomes a "remove this item" button with customizable label.

#### Try it
[Plnkr.co][select2try]

#### Review
Although there are many available skins for download, the CSS is usually intended for [Select2][select2] and therefore the classes and class declarations do not match that of `ui-select`. There is a bit of an aesthetic drawback when the number or size of the selected items forces the dropdown to occupy two lines. The other UI inhibitor is that the dropdown can only be triggered in the space between the selected items and the edge of the dropdown, therefore making it difficult to find a consistent place for enabling dropdowns.

___

### AngularJS Dropdown Multiselect

[Documentation][ngDropdown]

![AngularJS Dropdown Multiselect snapshot]({{ site.url }}/assets/uiselect/ngmultiselect.png)

#### Overview

This 100% AngularJS solution provides a customizable multi-select dropdown angular directive. Select options can be toggled and filtered (with search criteria) while dropdown is shown. Also provides options to select or clear all items. Extensive documentation and examples are provided on their site.

#### Try it
[jsfiddle.net][ngDropdownTry]

#### Review
This full-featured and highly customizable directive addresses all the functionality you could want. Easily change visual themes with Bootstrap skins (e.g. [Bootswatch][bootstrapSkins]).

___


### AngularJS Multi Select

[Documentation][ngMultiSelect]

![AngularJS Multi Select snapshot]({{ site.url }}/assets/uiselect/angularjsmultiselect.png)

#### Overview

This 100% AngularJS solution provides a customizable multi-select dropdown angular directive. Select options can be toggled and filtered (with search criteria) while dropdown is shown. Also provides options to select or clear all items. Icons can be shown next to items in the dropdown and in the button text.

It appears that there is a duplicate repo and it is unclear to me exactly what is going on. Both github users contributed to [this repo][ngMultiAlexandernst], but only one contributed to [this][ngMultiIsteven] one.

#### Try it
[jsfiddle.net][ngMultiSelectTry]

#### Review
This full-featured and highly customizable directive addresses all the functionality you could want. Easily change visual themes with Bootstrap skins (e.g. [Bootswatch][bootstrapSkins]).






[select2]:https://select2.github.io/
[ngSelect2]:https://github.com/angular-ui/ui-select2
[uiSelect]:https://github.com/angular-ui/ui-select
[ngDropdown]:http://dotansimha.github.io/angularjs-dropdown-multiselect/#/
[ngMultiSelect]:https://www.npmjs.com/package/angular-multi-select
[ngMultiIsteven]: http://isteven.github.io/angular-multi-select/
[ngMultiAlexandernst]:http://alexandernst.github.io/angular-multi-select/

[select2try]:http://plnkr.co/edit/juqoNOt1z1Gb349XabQ2?p=preview
[ngDropdownTry]:https://jsfiddle.net/evand/bmvtmzmm/
[ngMultiSelectTry]:https://jsfiddle.net/evand/x6kjc76r/

[bootstrapSkins]:https://bootswatch.com/
