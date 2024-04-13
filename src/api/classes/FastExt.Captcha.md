[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Captcha

# Class: Captcha

[FastExt](../modules/FastExt.md).Captcha

验证码相关操作

## Table of contents

### Constructors

- [constructor](FastExt.Captcha.md#constructor)

### Methods

- [getClickCaptchaCmp](FastExt.Captcha.md#getclickcaptchacmp)
- [getClickVerifyCmp](FastExt.Captcha.md#getclickverifycmp)
- [getLoginCaptchaCmp](FastExt.Captcha.md#getlogincaptchacmp)
- [getNormalCaptchaCmp](FastExt.Captcha.md#getnormalcaptchacmp)
- [showGoogleAuthentication](FastExt.Captcha.md#showgoogleauthentication)

## Constructors

### constructor

• **new Captcha**(): [`Captcha`](FastExt.Captcha.md)

#### Returns

[`Captcha`](FastExt.Captcha.md)

## Methods

### getClickCaptchaCmp

▸ **getClickCaptchaCmp**(): `Object`

获取看图点击验证码

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `anchor` | `string` |
| `itemId` | `string` |
| `items` | (\{ `allowBlank?`: `undefined` = false; `blankText?`: `undefined` = '请您先完成安全验证'; `emptyText?`: `undefined` = '请您完成安全验证'; `fieldLabel?`: `undefined` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex?`: `undefined` = 1; `itemId?`: `undefined` = "validateCodeTip"; `labelAlign?`: `undefined` = "right"; `labelSeparator?`: `undefined` = ''; `labelStyle?`: `undefined` = "font-size: 22px !important;color: #666666;"; `labelWidth?`: `undefined` = labelWidth; `letterKeyboard?`: `undefined` = true; `listeners?`: `undefined` ; `margin?`: `undefined` = '10 10 0 0'; `name`: `string` = "captchaKey"; `triggers?`: `undefined` ; `value`: `string` = captchaKey; `xtype`: `string` = "hiddenfield" } \| \{ `allowBlank`: `boolean` = false; `blankText`: `string` = '请您先完成安全验证'; `emptyText`: `string` = '请您完成安全验证'; `fieldLabel`: `string` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex`: `number` = 1; `itemId`: `string` = "validateCodeTip"; `labelAlign`: `string` = "right"; `labelSeparator`: `string` = ''; `labelStyle`: `string` = "font-size: 22px !important;color: #666666;"; `labelWidth`: `number` = labelWidth; `letterKeyboard`: `boolean` = true; `listeners`: \{ `render`: () => `void`  } ; `margin`: `string` = '10 10 0 0'; `name`: `string` = '@'; `triggers`: \{ `openValide`: \{ `cls`: `string` = 'extIcon extMouseClick'; `handler`: () => `void` ; `hideOnReadOnly`: `boolean` = false }  } ; `value?`: `undefined` = captchaKey; `xtype`: `string` = 'textfield' })[] |
| `labelWidth` | `number` |
| `layout` | \{ `align`: `string` = 'stretch'; `type`: `string` = 'hbox' } |
| `layout.align` | `string` |
| `layout.type` | `string` |
| `refreshCode` | () => `void` |
| `showValid` | () => `void` |
| `xtype` | `string` |

___

### getClickVerifyCmp

▸ **getClickVerifyCmp**(): `Object`

获取点击完成验证

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `anchor` | `string` |
| `itemId` | `string` |
| `items` | (\{ `allowBlank?`: `undefined` = false; `blankText?`: `undefined` = '请您先完成安全验证'; `emptyText?`: `undefined` = '请您完成安全验证'; `fieldLabel?`: `undefined` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex?`: `undefined` = 1; `itemId?`: `undefined` = "validateCodeTip"; `labelAlign?`: `undefined` = "right"; `labelSeparator?`: `undefined` = ''; `labelStyle?`: `undefined` = "font-size: 22px !important;color: #666666;"; `labelWidth?`: `undefined` = labelWidth; `letterKeyboard?`: `undefined` = true; `listeners?`: `undefined` ; `margin?`: `undefined` = '10 10 0 0'; `name`: `string` = "captchaKey"; `triggers?`: `undefined` ; `value`: `string` = captchaKey; `xtype`: `string` = "hiddenfield" } \| \{ `allowBlank`: `boolean` = false; `blankText`: `string` = '请您先完成安全验证！'; `emptyText`: `string` = '请点击右侧按钮，完成安全验证'; `fieldLabel`: `string` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex`: `number` = 1; `itemId`: `string` = "validateCodeTip"; `labelAlign`: `string` = "right"; `labelSeparator`: `string` = ''; `labelStyle`: `string` = "font-size: 22px !important;color: #666666;"; `labelWidth`: `number` = labelWidth; `letterKeyboard`: `boolean` = true; `listeners`: \{ `afterrender`: () => `void` ; `render`: () => `void`  } ; `margin`: `string` = '10 10 0 0'; `name`: `string` = '@'; `triggers`: \{ `openVerify`: \{ `cls`: `string` = 'extIcon extMouseClick'; `handler`: () => `void` ; `hideOnReadOnly`: `boolean` = false }  } ; `value?`: `undefined` = captchaKey; `xtype`: `string` = 'textfield' })[] |
| `labelWidth` | `number` |
| `layout` | \{ `align`: `string` = 'stretch'; `type`: `string` = 'hbox' } |
| `layout.align` | `string` |
| `layout.type` | `string` |
| `refreshCode` | () => `void` |
| `showValid` | () => `void` |
| `xtype` | `string` |

___

### getLoginCaptchaCmp

▸ **getLoginCaptchaCmp**(): \{ `anchor`: `string` = "100%"; `itemId`: `string` = "captcha"; `items`: (\{ `allowBlank?`: `undefined` = false; `blankText?`: `undefined` = '请您先完成安全验证'; `emptyText?`: `undefined` = '请您完成安全验证'; `fieldLabel?`: `undefined` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex?`: `undefined` = 1; `itemId?`: `undefined` = "validateCodeTip"; `labelAlign?`: `undefined` = "right"; `labelSeparator?`: `undefined` = ''; `labelStyle?`: `undefined` = "font-size: 22px !important;color: #666666;"; `labelWidth?`: `undefined` = labelWidth; `letterKeyboard?`: `undefined` = true; `listeners?`: `undefined` ; `margin?`: `undefined` = '10 10 0 0'; `name`: `string` = "captchaKey"; `triggers?`: `undefined` ; `value`: `string` = captchaKey; `xtype`: `string` = "hiddenfield" } \| \{ `allowBlank`: `boolean` = false; `blankText`: `string` = '请您先完成安全验证'; `emptyText`: `string` = '请您完成安全验证'; `fieldLabel`: `string` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex`: `number` = 1; `itemId`: `string` = "validateCodeTip"; `labelAlign`: `string` = "right"; `labelSeparator`: `string` = ''; `labelStyle`: `string` = "font-size: 22px !important;color: #666666;"; `labelWidth`: `number` = labelWidth; `letterKeyboard`: `boolean` = true; `listeners`: \{ `render`: () => `void`  } ; `margin`: `string` = '10 10 0 0'; `name`: `string` = '@'; `triggers`: \{ `openValide`: \{ `cls`: `string` = 'extIcon extMouseClick'; `handler`: () => `void` ; `hideOnReadOnly`: `boolean` = false }  } ; `value?`: `undefined` = captchaKey; `xtype`: `string` = 'textfield' })[] ; `labelWidth`: `number` = 0; `layout`: \{ `align`: `string` = 'stretch'; `type`: `string` = 'hbox' } ; `refreshCode`: () => `void` ; `showValid`: () => `void` ; `xtype`: `string` = 'fieldcontainer' } \| \{ `anchor`: `string` = "100%"; `itemId`: `string` = "captcha"; `items`: (\{ `allowBlank?`: `undefined` = false; `blankText?`: `undefined` = '请您先完成安全验证'; `emptyText?`: `undefined` = '请您完成安全验证'; `fieldLabel?`: `undefined` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex?`: `undefined` = 1; `itemId?`: `undefined` = "validateCodeTip"; `labelAlign?`: `undefined` = "right"; `labelSeparator?`: `undefined` = ''; `labelStyle?`: `undefined` = "font-size: 22px !important;color: #666666;"; `labelWidth?`: `undefined` = labelWidth; `letterKeyboard?`: `undefined` = true; `listeners?`: `undefined` ; `margin?`: `undefined` = '10 10 0 0'; `name`: `string` = "captchaKey"; `triggers?`: `undefined` ; `value`: `string` = captchaKey; `xtype`: `string` = "hiddenfield" } \| \{ `allowBlank`: `boolean` = false; `blankText`: `string` = '请您先完成安全验证！'; `emptyText`: `string` = '请点击右侧按钮，完成安全验证'; `fieldLabel`: `string` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex`: `number` = 1; `itemId`: `string` = "validateCodeTip"; `labelAlign`: `string` = "right"; `labelSeparator`: `string` = ''; `labelStyle`: `string` = "font-size: 22px !important;color: #666666;"; `labelWidth`: `number` = labelWidth; `letterKeyboard`: `boolean` = true; `listeners`: \{ `afterrender`: () => `void` ; `render`: () => `void`  } ; `margin`: `string` = '10 10 0 0'; `name`: `string` = '@'; `triggers`: \{ `openVerify`: \{ `cls`: `string` = 'extIcon extMouseClick'; `handler`: () => `void` ; `hideOnReadOnly`: `boolean` = false }  } ; `value?`: `undefined` = captchaKey; `xtype`: `string` = 'textfield' })[] ; `labelWidth`: `number` = 0; `layout`: \{ `align`: `string` = 'stretch'; `type`: `string` = 'hbox' } ; `refreshCode`: () => `void` ; `showValid`: () => `void` ; `xtype`: `string` = 'fieldcontainer' } \| \{ `hidden`: `boolean` = true; `xtype`: `string` = "label" }

获取登录界面的验证码组件

#### Returns

\{ `anchor`: `string` = "100%"; `itemId`: `string` = "captcha"; `items`: (\{ `allowBlank?`: `undefined` = false; `blankText?`: `undefined` = '请您先完成安全验证'; `emptyText?`: `undefined` = '请您完成安全验证'; `fieldLabel?`: `undefined` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex?`: `undefined` = 1; `itemId?`: `undefined` = "validateCodeTip"; `labelAlign?`: `undefined` = "right"; `labelSeparator?`: `undefined` = ''; `labelStyle?`: `undefined` = "font-size: 22px !important;color: #666666;"; `labelWidth?`: `undefined` = labelWidth; `letterKeyboard?`: `undefined` = true; `listeners?`: `undefined` ; `margin?`: `undefined` = '10 10 0 0'; `name`: `string` = "captchaKey"; `triggers?`: `undefined` ; `value`: `string` = captchaKey; `xtype`: `string` = "hiddenfield" } \| \{ `allowBlank`: `boolean` = false; `blankText`: `string` = '请您先完成安全验证'; `emptyText`: `string` = '请您完成安全验证'; `fieldLabel`: `string` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex`: `number` = 1; `itemId`: `string` = "validateCodeTip"; `labelAlign`: `string` = "right"; `labelSeparator`: `string` = ''; `labelStyle`: `string` = "font-size: 22px !important;color: #666666;"; `labelWidth`: `number` = labelWidth; `letterKeyboard`: `boolean` = true; `listeners`: \{ `render`: () => `void`  } ; `margin`: `string` = '10 10 0 0'; `name`: `string` = '@'; `triggers`: \{ `openValide`: \{ `cls`: `string` = 'extIcon extMouseClick'; `handler`: () => `void` ; `hideOnReadOnly`: `boolean` = false }  } ; `value?`: `undefined` = captchaKey; `xtype`: `string` = 'textfield' })[] ; `labelWidth`: `number` = 0; `layout`: \{ `align`: `string` = 'stretch'; `type`: `string` = 'hbox' } ; `refreshCode`: () => `void` ; `showValid`: () => `void` ; `xtype`: `string` = 'fieldcontainer' } \| \{ `anchor`: `string` = "100%"; `itemId`: `string` = "captcha"; `items`: (\{ `allowBlank?`: `undefined` = false; `blankText?`: `undefined` = '请您先完成安全验证'; `emptyText?`: `undefined` = '请您完成安全验证'; `fieldLabel?`: `undefined` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex?`: `undefined` = 1; `itemId?`: `undefined` = "validateCodeTip"; `labelAlign?`: `undefined` = "right"; `labelSeparator?`: `undefined` = ''; `labelStyle?`: `undefined` = "font-size: 22px !important;color: #666666;"; `labelWidth?`: `undefined` = labelWidth; `letterKeyboard?`: `undefined` = true; `listeners?`: `undefined` ; `margin?`: `undefined` = '10 10 0 0'; `name`: `string` = "captchaKey"; `triggers?`: `undefined` ; `value`: `string` = captchaKey; `xtype`: `string` = "hiddenfield" } \| \{ `allowBlank`: `boolean` = false; `blankText`: `string` = '请您先完成安全验证！'; `emptyText`: `string` = '请点击右侧按钮，完成安全验证'; `fieldLabel`: `string` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex`: `number` = 1; `itemId`: `string` = "validateCodeTip"; `labelAlign`: `string` = "right"; `labelSeparator`: `string` = ''; `labelStyle`: `string` = "font-size: 22px !important;color: #666666;"; `labelWidth`: `number` = labelWidth; `letterKeyboard`: `boolean` = true; `listeners`: \{ `afterrender`: () => `void` ; `render`: () => `void`  } ; `margin`: `string` = '10 10 0 0'; `name`: `string` = '@'; `triggers`: \{ `openVerify`: \{ `cls`: `string` = 'extIcon extMouseClick'; `handler`: () => `void` ; `hideOnReadOnly`: `boolean` = false }  } ; `value?`: `undefined` = captchaKey; `xtype`: `string` = 'textfield' })[] ; `labelWidth`: `number` = 0; `layout`: \{ `align`: `string` = 'stretch'; `type`: `string` = 'hbox' } ; `refreshCode`: () => `void` ; `showValid`: () => `void` ; `xtype`: `string` = 'fieldcontainer' } \| \{ `hidden`: `boolean` = true; `xtype`: `string` = "label" }

___

### getNormalCaptchaCmp

▸ **getNormalCaptchaCmp**(): `Object`

获取验证码的组件

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `anchor` | `string` |
| `itemId` | `string` |
| `items` | (\{ `allowBlank`: `boolean` = false; `blankText`: `string` = '请输入验证码'; `cls?`: `undefined` = 'fast-system-valid-code-img'; `emptyText`: `string` = '请输入验证码'; `fieldLabel`: `string` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extLoginCode"\>\</use\>\</svg\>'; `flex`: `number` = 1; `height?`: `undefined` = 34; `itemId`: `string` = "validateCode"; `labelAlign`: `string` = "right"; `labelSeparator`: `string` = ''; `labelStyle`: `string` = "font-size: 22px !important;color: #666666;"; `labelWidth`: `number` = labelWidth; `letterKeyboard`: `boolean` = true; `listeners?`: `undefined` ; `margin`: `string` = '10 10 0 0'; `name`: `string` = 'validateCode'; `width?`: `undefined` = 74; `xtype`: `string` = 'textfield' } \| \{ `allowBlank?`: `undefined` = false; `blankText?`: `undefined` = '请您先完成安全验证'; `cls`: `string` = 'fast-system-valid-code-img'; `emptyText?`: `undefined` = '请您完成安全验证'; `fieldLabel?`: `undefined` = '\<svg class="svgIcon" aria-hidden="true"\>\<use xlink:href="#extPower"\>\</use\>\</svg\>'; `flex?`: `undefined` = 1; `height`: `number` = 34; `itemId`: `string` = 'imgCode'; `labelAlign?`: `undefined` = "right"; `labelSeparator?`: `undefined` = ''; `labelStyle?`: `undefined` = "font-size: 22px !important;color: #666666;"; `labelWidth?`: `undefined` = labelWidth; `letterKeyboard?`: `undefined` = true; `listeners`: \{ `click`: \{ `element`: `string` = 'el'; `fn`: () => `void`  }  } ; `margin`: `string` = '10 10 0 0'; `name?`: `undefined` = 'validateCode'; `width`: `number` = 74; `xtype`: `string` = 'image' })[] |
| `labelWidth` | `number` |
| `layout` | \{ `align`: `string` = 'stretch'; `type`: `string` = 'hbox' } |
| `layout.align` | `string` |
| `layout.type` | `string` |
| `refreshCode` | () => `void` |
| `xtype` | `string` |

___

### showGoogleAuthentication

▸ **showGoogleAuthentication**(`step`, `callBack`): `void`

弹出google验证

#### Parameters

| Name | Type |
| :------ | :------ |
| `step` | `number` |
| `callBack` | `any` |

#### Returns

`void`
