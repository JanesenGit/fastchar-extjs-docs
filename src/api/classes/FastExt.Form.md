[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Form

# Class: Form

[FastExt](../modules/FastExt.md).Form

网页表单相关操作

## Table of contents

### Constructors

- [constructor](FastExt.Form.md#constructor)

### Methods

- [asyncForm](FastExt.Form.md#asyncform)
- [buildForm](FastExt.Form.md#buildform)
- [getFieldError](FastExt.Form.md#getfielderror)
- [getFieldMinHeight](FastExt.Form.md#getfieldminheight)
- [isComboField](FastExt.Form.md#iscombofield)
- [isContentField](FastExt.Form.md#iscontentfield)
- [isDateField](FastExt.Form.md#isdatefield)
- [isEnumField](FastExt.Form.md#isenumfield)
- [isFileField](FastExt.Form.md#isfilefield)
- [isFilesField](FastExt.Form.md#isfilesfield)
- [isHtmlContentField](FastExt.Form.md#ishtmlcontentfield)
- [isLinkField](FastExt.Form.md#islinkfield)
- [isMapField](FastExt.Form.md#ismapfield)
- [isMonacoEditorField](FastExt.Form.md#ismonacoeditorfield)
- [isNumberField](FastExt.Form.md#isnumberfield)
- [isPCAField](FastExt.Form.md#ispcafield)
- [isTargetField](FastExt.Form.md#istargetfield)
- [isTextField](FastExt.Form.md#istextfield)
- [showJsonForm](FastExt.Form.md#showjsonform)

## Constructors

### constructor

• **new Form**(): [`Form`](FastExt.Form.md)

#### Returns

[`Form`](FastExt.Form.md)

## Methods

### asyncForm

▸ **asyncForm**(`url`, `paramsJson`): `ExtPromise`

异步提交表单

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |
| `paramsJson` | `any` |

#### Returns

`ExtPromise`

___

### buildForm

▸ **buildForm**(`url`, `paramsJson`, `target?`): `any`

动态构建表单form对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` | 提交的路径 |
| `paramsJson` | `object` | 提交的JSON参数 |
| `target?` | [`Target`](../enums/FastEnum.Target.md) | 目标打开窗体 默认：_self |

#### Returns

`any`

html中的form对象

___

### getFieldError

▸ **getFieldError**(`fieldObj`): `string`[]

获取字段输入框的错误消息

#### Parameters

| Name | Type |
| :------ | :------ |
| `fieldObj` | `any` |

#### Returns

`string`[]

string[]

___

### getFieldMinHeight

▸ **getFieldMinHeight**(`showHeight`): `number`

获取输入框最小的高度

#### Parameters

| Name | Type |
| :------ | :------ |
| `showHeight` | `any` |

#### Returns

`number`

___

### isComboField

▸ **isComboField**(`field`): `boolean`

是否是下拉框控件 combobox combo

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isContentField

▸ **isContentField**(`field`): `boolean`

是否是大文本编辑器 contentfield

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isDateField

▸ **isDateField**(`field`): `boolean`

是否是日期控件 datefield

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isEnumField

▸ **isEnumField**(`field`): `boolean`

是否是枚举控件 enumcombo

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isFileField

▸ **isFileField**(`field`): `boolean`

是否是文件控件 fastfile

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isFilesField

▸ **isFilesField**(`field`): `boolean`

是否是多文件控件 fastfiles

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isHtmlContentField

▸ **isHtmlContentField**(`field`): `boolean`

是否是网页编辑器 htmlcontentfield

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isLinkField

▸ **isLinkField**(`field`): `boolean`

是否是关联字段 linkfield

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isMapField

▸ **isMapField**(`field`): `boolean`

是否地图选择控件 mapfield

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isMonacoEditorField

▸ **isMonacoEditorField**(`field`): `boolean`

是否是网页编辑器 htmlcontentfield

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isNumberField

▸ **isNumberField**(`field`): `boolean`

是否是数字控件 numberfield

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isPCAField

▸ **isPCAField**(`field`): `boolean`

是否是省份选择控件 pcafield

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isTargetField

▸ **isTargetField**(`field`): `boolean`

是否关联目标字段 targetfield

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isTextField

▸ **isTextField**(`field`): `boolean`

是否是文本控件 textfield

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### showJsonForm

▸ **showJsonForm**(`obj`, `title`, `jsonFieldConfig`, `jsonFieldDefaultConfig`, `modal`): `any`

将json对象渲染成表单可编辑对话框

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `title` | `any` |
| `jsonFieldConfig` | `any` |
| `jsonFieldDefaultConfig` | `any` |
| `modal` | `any` |

#### Returns

`any`
