# Button 
 <br />

> **Overview**

 Buttons are created using native `<button>` element enhanced based on the design styling provided in figma. 
 <br />
 
> **Themes**
 
 | Attribute | Description|
 | --------- | ---------- |
 | Primary   | `Primary` is the Default variant for button component. Rectangular contained button with blue color. |
 | Basic     | `Basic` is a rectangular outlined button with white background and blue colored text and border. |
 | Text      | `Text` is a rectangular transparent button without border and a light shade on hover. |
 | Warn      | `Warn` is a rectangular contained button with a striking red color |
 <br />
 
 > **Size**
 
 `Button` component is available in 3 different size.
 
 1. Large.
 2. Medium.
 3. Small.
 <br />
 
 > **Accessibility**
 
 We have used native `<button>` element to ensure an accessible experience by default. A `<button>` element should be used for any interaction that performs an action on the current page. All standard accessibility best practices are applied .
 <br />
 
 > **Disabling Button**
 
 We can disable the button using the `disabled` property on the button. It accepts `boolean` value. The styling for disabled button is as mentioned in the figma.
 <br />
 
 > **Button With Icon**
 
 Button can contain one or two icon either in front of button text or after the button text or both as per the requirement. We can position the icon using `IconPositionedFront` and `IconPositionedEnd` property of the button. To which we can pass the template of the icon.
 <br />
 
> **Inputs**

| Name | Description| Default|
| ---- | ---------- | ------ |
| variant | `"primary"` `"basic"` `"text"` `"warn"` | `"primary"`|
| disabled | `boolean` | `false` |
| aria-label | `string` |     -    |
| IconPositionedEnd | `TemplateRef<any> or null` |  -  |
| IconPositionedFront | `TemplateRef<any> or null` |  -  |
| id | `string` | "" |
| size | `"large"` `"medium"` `"small"` | `"large"` |

> **Properties**

| Name | Description| Default|
| ---- | ---------- | ------ |
| Variant | `""` | `variant` |

> **Outputs**

| Name | Description| Default|
| ---- | ---------- | ------ |
| onClick | `EventEmitter` | `onClick: {}` |

> **Methods**

| Name | Description| Default|
| ---- | ---------- | ------ |
| ngOnInit | `() => void` |  -  |
| OnClick | `() => void` | `OnClick: {}` |

> **View Child**

| Name | Description| Default|
| ---- | ---------- | ------ |
| buttonText | `ElementRef` `null` | - |

