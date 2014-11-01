jquery.formwiz
==============

a jQuery plugin to make form validation easy as pie

This plugin is based a set of jQuery scripts I wrote about 3-4 years ago to apply form validation across a large web project without having to teach every developer complex means of using it. All of the form validations & actions are applied using a very simple "data-" declarative syntax. The declarations all use very simple & natural language, where the decoration says what the action or validation is. I had originally wanted to open source these scripts so that other, better developers could poke holes in it and help with improvements, but chose not to for various reasons. 

I was recently looking at jquery validator plugins with a coworker and wasnt all that surprised that other people had developed libraries based on the concept as I used, but was surprised at how unnatural or convoluted the data- attributes names were on these libraries. I also noticed certain validation concepts were missing from many of these libraries, which I had included in my scripts. 

Some of the features of my scripts are as follows;
 - limit & restrict what characters can be entered into a given field
 - limit the number of characters that can be entered into a textarea field
 - allow for minimum and maximum values. Allow those min\max values to be numbers, dates or the values of other fields
 - provide a simple way to set a fields default value.
 - parse and validate date\time\datetime values on blur()
 - make fields required and disallow submit if they are not completed
 - make a field required only if data is entered into another, non-required "parent" field
 - provide a way to validate a certain group of fields on a page rather than all fields on the page
 -



NOTE: this is my first jQuery "plugin" and my first time using github. So, so long as this message is in the readme, this file is still being worked on. 
