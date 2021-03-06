# ion-tab-button

A tab button is a UI component that is placed inside of a [tab bar](../tab-bar). The tab button can specify the layout of the icon and label and connect to a [tab view](../tab).

See the [tabs documentation](../tabs) for more details on configuring tabs.


<!-- Auto Generated Below -->


## Properties

| Property   | Attribute  | Description                                                                                                                                                                                                                                                            | Type                                                                                                    | Default     |
| ---------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ----------- |
| `color`    | `color`    | The color to use from your application's color palette. Default options are: `"primary"`, `"secondary"`, `"tertiary"`, `"success"`, `"warning"`, `"danger"`, `"light"`, `"medium"`, and `"dark"`. For more information on colors, see [theming](/docs/theming/basics). | `string \| undefined`                                                                                   | `undefined` |
| `disabled` | `disabled` | The selected tab component                                                                                                                                                                                                                                             | `boolean`                                                                                               | `false`     |
| `href`     | `href`     | The URL which will be used as the `href` within this tab's button anchor.                                                                                                                                                                                              | `string \| undefined`                                                                                   | `undefined` |
| `layout`   | `layout`   | Set the layout of the text and icon in the tab bar. It defaults to `'icon-top'`.                                                                                                                                                                                       | `"icon-bottom" \| "icon-end" \| "icon-hide" \| "icon-start" \| "icon-top" \| "label-hide" \| undefined` | `undefined` |
| `mode`     | `mode`     | The mode determines which platform styles to use.                                                                                                                                                                                                                      | `"ios" \| "md"`                                                                                         | `undefined` |
| `tab`      | `tab`      | A tab id must be provided for each `ion-tab`. It's used internally to reference the selected tab or by the router to switch between them.                                                                                                                              | `string`                                                                                                | `undefined` |


## CSS Custom Properties

| Name                    | Description                           |
| ----------------------- | ------------------------------------- |
| `--background`          | Background of the tab button          |
| `--background-selected` | Background of the selected tab button |
| `--color`               | Color of the tab button               |
| `--color-selected`      | Color of the selected tab button      |
| `--padding-bottom`      | Bottom padding of the tab button      |
| `--padding-end`         | End padding of the tab button         |
| `--padding-start`       | Start padding of the tab button       |
| `--padding-top`         | Top padding of the tab button         |
| `--ripple-color`        | Color of the button ripple effect     |


----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
