[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Dates

# Class: Dates

[FastExt](../modules/FastExt.md).Dates

日期相关操作工具类

## Table of contents

### Constructors

- [constructor](FastExt.Dates.md#constructor)

### Properties

- [dateFormatStore](FastExt.Dates.md#dateformatstore)

### Methods

- [\_\_onLoaded](FastExt.Dates.md#__onloaded)
- [formatDateStr](FastExt.Dates.md#formatdatestr)
- [formatDateTip](FastExt.Dates.md#formatdatetip)
- [formatMillisecond](FastExt.Dates.md#formatmillisecond)
- [getNowDateString](FastExt.Dates.md#getnowdatestring)
- [guessDateFormat](FastExt.Dates.md#guessdateformat)
- [initDateFormatStore](FastExt.Dates.md#initdateformatstore)
- [parseDate](FastExt.Dates.md#parsedate)
- [showDatePicker](FastExt.Dates.md#showdatepicker)

## Constructors

### constructor

• **new Dates**(): [`Dates`](FastExt.Dates.md)

#### Returns

[`Dates`](FastExt.Dates.md)

## Properties

### dateFormatStore

▪ `Static` **dateFormatStore**: `Object` = `{}`

## Methods

### \_\_onLoaded

▸ **__onLoaded**(): `void`

#### Returns

`void`

___

### formatDateStr

▸ **formatDateStr**(`dateStr`, `formatStr`): `any`

格式化日期

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `dateStr` | `string` | 日期字符串 |
| `formatStr` | `string` | 格式化的样式，"Y-m-d H:i:s" |

#### Returns

`any`

___

### formatDateTip

▸ **formatDateTip**(`sourceDate`, `dateFormat?`, `appendWeek?`): `string`

将日期格式化为生活日期提示，例如：1个小时前、1天前、1个月等

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `sourceDate` | `Date` | 日期 |
| `dateFormat?` | `string` | 当超出汉字描述的范围后，使用指定的格式格式化日期 默认：Y-m-d H:i:s |
| `appendWeek?` | `boolean` | 是否追加 周几 |

#### Returns

`string`

___

### formatMillisecond

▸ **formatMillisecond**(`millisecond`, `formatStr`): `string`

将毫秒格式化

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `millisecond` | `number` | 时间戳（毫秒） |
| `formatStr` | `string` | 格式化的样式，"Y-m-d H:i:s" |

#### Returns

`string`

___

### getNowDateString

▸ **getNowDateString**(`format`, `diffDay?`): `string`

获取当期日期

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `format` | `string` | 格式化日期 |
| `diffDay?` | `number` | 针对日期 加减 |

#### Returns

`string`

___

### guessDateFormat

▸ **guessDateFormat**(`value`): `string`

根据日期值猜测日期类型

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`string`

___

### initDateFormatStore

▸ **initDateFormatStore**(): `void`

初始化所有日期格式

#### Returns

`void`

___

### parseDate

▸ **parseDate**(`dateValue`): `Date`

将字符串格式化日期

#### Parameters

| Name | Type |
| :------ | :------ |
| `dateValue` | `string` |

#### Returns

`Date`

___

### showDatePicker

▸ **showDatePicker**(`obj`, `defaultValue`, `dateFormat`): `any`

弹出日期时间选择控件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 需要弹出的目标控件 |
| `defaultValue` | `any` | 默认日期时间 |
| `dateFormat` | `any` | 日期时间的格式 |

#### Returns

`any`

Ext.Promise
