---
layout: post
title:  "AngularJS Multi-select Dropdown"
date:   2015-08-03 13:35:58
categories: angularJS ui
---

Design guidelines require a multi-select dropdown that shows all the options as selectable and tallies the selections as a comma-separated, concatenated string in the dropdown's consolidated view.

##The TARGET

![Multi-select dropdown target]({{ site.url }}/assets/uiselect/target.jpg)

Basic Requirements
 * Multi-select
 * Summarizes selections in collapsed view
 * Shows all items in dropdown and can toggle selection state
 * Cross-browser compatible
 * AngularJS

##The CONTENDERS

 * [Select2][select2]
 * [UI-Select][uiSelect]
 * [Angularjs Dropdown Multiselect][ngDropdown]
 * [angular-multi-select][ngMultiSelect]

- - -

###Select2 (deprecated)

[Github page][select2] states this is obsolete and then links to [UI-Select][uiSelect].

- - -

###UI-Select

![UI-Select snapshot]({{ site.url }}/assets/uiselect/uiselect.jpg)

####Overview

This 100% AngularJS solution provides multi-select options for variations on customizable dropdowns. Once an item has been selected, it is removed from the dropdown list and becomes a "remove this item" button with customizable label.

####Try it
[Plnkr.co][select2try]

####Review
Although there are many available skins for download, the CSS is usually intended for Select2 and therefore the classes and class declarations do not match that of ui-select. There is a bit of an aesthetic drawback when the number or size of the selected items forces the dropdown to occupy two lines. The other UI inhibitor is that the dropdown can only be triggered in the space between the selected items and the edge of the dropdown, therefore making it difficult to find a consistent place for enabling dropdowns.

- - -




{% highlight javascript %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[select2]:https://github.com/angular-ui/ui-select2
[uiSelect]:https://github.com/angular-ui/ui-select
[ngDropdown]:http://dotansimha.github.io/angularjs-dropdown-multiselect/#/
[ngMultiSelect]:https://www.npmjs.com/package/angular-multi-select

[select2try]:http://plnkr.co/edit/juqoNOt1z1Gb349XabQ2?p=preview
