[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Documents

# Class: Documents

[FastExt](../modules/FastExt.md).Documents

javascript 原生document操作功能相关

## Table of contents

### Constructors

- [constructor](FastExt.Documents.md#constructor)

### Methods

- [addScript](FastExt.Documents.md#addscript)
- [addScripts](FastExt.Documents.md#addscripts)
- [addStyle](FastExt.Documents.md#addstyle)
- [addStylesheet](FastExt.Documents.md#addstylesheet)
- [addStylesheets](FastExt.Documents.md#addstylesheets)
- [loadFunction](FastExt.Documents.md#loadfunction)
- [onClickFromDataClick](FastExt.Documents.md#onclickfromdataclick)
- [onWrapTagMouseOver](FastExt.Documents.md#onwraptagmouseover)
- [removeStyle](FastExt.Documents.md#removestyle)
- [wrapOnClick](FastExt.Documents.md#wraponclick)

## Constructors

### constructor

• **new Documents**(): [`Documents`](FastExt.Documents.md)

#### Returns

[`Documents`](FastExt.Documents.md)

## Methods

### addScript

▸ **addScript**(`script`, `callBack?`): `void`

动态加载js文件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `script` | `any` | js文件对象 {src:""} |
| `callBack?` | `any` |  |

#### Returns

`void`

**`See`**

FastExt.SystemScript

___

### addScripts

▸ **addScripts**(`scriptPaths`, `callBack`): `void`

批量加载js文件

#### Parameters

| Name | Type |
| :------ | :------ |
| `scriptPaths` | `string`[] |
| `callBack` | `any` |

#### Returns

`void`

___

### addStyle

▸ **addStyle**(`style`, `callBack?`): `any`

动态加载css代码

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `style` | `any` | css代码 |
| `callBack?` | `any` | 加载成功后回调 |

#### Returns

`any`

___

### addStylesheet

▸ **addStylesheet**(`link`, `callBack`): `void`

动态加载style文件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `link` | `any` | 文件地址 {href:""} |
| `callBack` | `any` |  |

#### Returns

`void`

___

### addStylesheets

▸ **addStylesheets**(`cssPaths`, `callBack`): `void`

动态加载style文件

#### Parameters

| Name | Type |
| :------ | :------ |
| `cssPaths` | `string`[] |
| `callBack` | `any` |

#### Returns

`void`

___

### loadFunction

▸ **loadFunction**(`functionStr`): `any`

动态加载字符串函数，字符串的函数必须为匿名

#### Parameters

| Name | Type |
| :------ | :------ |
| `functionStr` | `string` |

#### Returns

`any`

函数对象

**`Example`**

```ts
loadFunction("function(val){return val+1;}");
```

___

### onClickFromDataClick

▸ **onClickFromDataClick**(`obj`): `void`

当点击标签时触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`void`

___

### onWrapTagMouseOver

▸ **onWrapTagMouseOver**(`id`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `string` |

#### Returns

`boolean`

___

### removeStyle

▸ **removeStyle**(`code`): `void`

删除样式标签

#### Parameters

| Name | Type |
| :------ | :------ |
| `code` | `any` |

#### Returns

`void`

___

### wrapOnClick

▸ **wrapOnClick**(`html`, `onClickFunction`): `string`

给html的标签绑定onclick事件

#### Parameters

| Name | Type |
| :------ | :------ |
| `html` | `string` |
| `onClickFunction` | `string` |

#### Returns

`string`
