# VeamsDOM plugin

The VeamsDOM plugin is simple plugin for which you need to pass a DOM handler like jQuery. For some other plugins VeamsDOM is a requirement.

__How to__

```js
import $ from 'jquery';
import Veams from 'veams';
import VeamsDOM from 'veams/lib/plugins/dom';

// Intialize core of Veams
Veams.initialize();

// Add plugins to the Veams system
Veams.use(VeamsDOM, {
    DOM: $
});
```
_Options_

_DOM_ {`Function`} [`() => {}`] (required) - Add a DOM handler by using this option. It should have the same api like jQuery.
