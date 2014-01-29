jquery-plugin-pattern
=====================

A light-weight jQuery plugin patterns for jump starting your plugin development.

Here’s some of the benifits of using this as a template

- You have an option to override default option
- Easily set name of your plugin. All you have to set it once and rest is taken care of.
- You can define _getter_ methods, getting intrinsic values.
- Last but not the least, you can call the plugin function from outside. Something like this,

```
$('div').plugin('destroy');
$('div').plugin('sayThings', 'say this', 'and this');
var value = $('div').plugin('getterMethod');
```