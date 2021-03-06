---
filename: /packages/material-ui/src/Menu/Menu.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# Menu API

<p class="description">The API documentation of the Menu React component. Learn more about the properties and the CSS customization points.</p>

```js
import Menu from '@material-ui/core/Menu';
```



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">anchorEl</span> | <span class="prop-type">union:&nbsp;object&nbsp;&#124;<br>&nbsp;func<br></span> |  | The DOM element used to set the position of the menu. |
| <span class="prop-name">children</span> | <span class="prop-type">node</span> |  | Menu contents, normally `MenuItem`s. |
| <span class="prop-name">classes</span> | <span class="prop-type">object</span> |  | Override or extend the styles applied to the component. See [CSS API](#css) below for more details. |
| <span class="prop-name">disableAutoFocusItem</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | If `true`, the selected / first menu item will not be auto focused. |
| <span class="prop-name">MenuListProps</span> | <span class="prop-type">object</span> |  | Properties applied to the [`MenuList`](/api/menu-list/) element. |
| <span class="prop-name">onClose</span> | <span class="prop-type">func</span> |  | Callback fired when the component requests to be closed.<br><br>**Signature:**<br>`function(event: object, reason: string) => void`<br>*event:* The event source of the callback<br>*reason:* Can be:`"escapeKeyDown"`, `"backdropClick"`, `"tabKeyDown"` |
| <span class="prop-name">onEnter</span> | <span class="prop-type">func</span> |  | Callback fired before the Menu enters. |
| <span class="prop-name">onEntered</span> | <span class="prop-type">func</span> |  | Callback fired when the Menu has entered. |
| <span class="prop-name">onEntering</span> | <span class="prop-type">func</span> |  | Callback fired when the Menu is entering. |
| <span class="prop-name">onExit</span> | <span class="prop-type">func</span> |  | Callback fired before the Menu exits. |
| <span class="prop-name">onExited</span> | <span class="prop-type">func</span> |  | Callback fired when the Menu has exited. |
| <span class="prop-name">onExiting</span> | <span class="prop-type">func</span> |  | Callback fired when the Menu is exiting. |
| <span class="prop-name required">open&nbsp;*</span> | <span class="prop-type">bool</span> |  | If `true`, the menu is visible. |
| <span class="prop-name">PopoverClasses</span> | <span class="prop-type">object</span> |  | `classes` property applied to the [`Popover`](/api/popover/) element. |
| <span class="prop-name">transitionDuration</span> | <span class="prop-type">union:&nbsp;number&nbsp;&#124;<br>&nbsp;{ enter?: number, exit?: number }&nbsp;&#124;<br>&nbsp;enum:&nbsp;'auto'<br><br></span> | <span class="prop-default">'auto'</span> | The length of the transition in `ms`, or 'auto' |

The `ref` is forwarded to the root element.

Any other properties supplied will be provided to the root element ([Popover](/api/popover/)).

## CSS

You can override all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:


| Name | Description |
|:-----|:------------|
| <span class="prop-name">paper</span> | Styles applied to the `Paper` component.

Have a look at [overriding with classes](/customization/overrides/#overriding-with-classes) section
and the [implementation of the component](https://github.com/mui-org/material-ui/blob/next/packages/material-ui/src/Menu/Menu.js)
for more detail.

If using the `overrides` [key of the theme](/customization/themes/#css),
you need to use the following style sheet name: `MuiMenu`.

## Inheritance

The properties of the [Popover](/api/popover/) component are also available.
You can take advantage of this behavior to [target nested components](/guides/api/#spread).

## Demos

- [App Bar](/demos/app-bar/)
- [Menus](/demos/menus/)

