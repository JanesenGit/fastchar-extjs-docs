[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Json

# Class: Json

[FastExt](../modules/FastExt.md).Json

JSON相关功能

## Table of contents

### Constructors

- [constructor](FastExt.Json.md#constructor)

### Properties

- [formatterJsPath](FastExt.Json.md#formatterjspath)

### Methods

- [jsonToObject](FastExt.Json.md#jsontoobject)
- [jsonToObjectUnsafe](FastExt.Json.md#jsontoobjectunsafe)
- [loaderFormatter](FastExt.Json.md#loaderformatter)
- [mergeJson](FastExt.Json.md#mergejson)
- [objectToJson](FastExt.Json.md#objecttojson)
- [objectToJsonUnsafe](FastExt.Json.md#objecttojsonunsafe)
- [showFormatJson](FastExt.Json.md#showformatjson)
- [toFormatJsonHtml](FastExt.Json.md#toformatjsonhtml)

## Constructors

### constructor

• **new Json**(): [`Json`](FastExt.Json.md)

#### Returns

[`Json`](FastExt.Json.md)

## Properties

### formatterJsPath

▪ `Static` **formatterJsPath**: `string` = `"base/json-formatter/json-formatter.min.js"`

## Methods

### jsonToObject

▸ **jsonToObject**(`jsonStr`, `printException?`): `any`

将json字符串转成对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `jsonStr` | `string` | json字符串 |
| `printException?` | `boolean` |  |

#### Returns

`any`

___

### jsonToObjectUnsafe

▸ **jsonToObjectUnsafe**(`jsonStr`): `any`

将json字符串转成对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `jsonStr` | `string` | json字符串 |

#### Returns

`any`

___

### loaderFormatter

▸ **loaderFormatter**(`callBack`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callBack` | `any` |

#### Returns

`void`

___

### mergeJson

▸ **mergeJson**(`jsonData1`, `jsonData2`): `any`

合并两个json对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `jsonData1` | `any` | json对象 |
| `jsonData2` | `any` | json对象 |

#### Returns

`any`

合并后的新对象

___

### objectToJson

▸ **objectToJson**(`jsonObj`, `printException?`): `string`

将对象转成json字符串

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `jsonObj` | `any` | 待转换的对象 |
| `printException?` | `boolean` |  |

#### Returns

`string`

___

### objectToJsonUnsafe

▸ **objectToJsonUnsafe**(`jsonObj`): `string`

将对象转成json字符串，注意此方法将转换函数对象，慎用！

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `jsonObj` | `any` | 待转换的对象 |

#### Returns

`string`

___

### showFormatJson

▸ **showFormatJson**(`obj`, `value`, `title?`): `void`

格式化显示json字符串

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 动画对象 |
| `value` | `any` | json值 |
| `title?` | `any` | 窗口标题 |

#### Returns

`void`

___

### toFormatJsonHtml

▸ **toFormatJsonHtml**(`jsonContent`, `keepChar`, `callBack`): `void`

格式化json

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `jsonContent` | `string` |  |
| `keepChar` | `boolean` | 保留转义符 |
| `callBack` | `any` |  |

#### Returns

`void`
