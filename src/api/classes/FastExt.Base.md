[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Base

# Class: Base

[FastExt](../modules/FastExt.md).Base

常规功能方法

## Table of contents

### Constructors

- [constructor](FastExt.Base.md#constructor)

### Properties

- [onlyIterator](FastExt.Base.md#onlyiterator)

### Methods

- [buildOnlyCode](FastExt.Base.md#buildonlycode)
- [buildOnlyNumber](FastExt.Base.md#buildonlynumber)
- [buildUUID12](FastExt.Base.md#builduuid12)
- [buildUUID16](FastExt.Base.md#builduuid16)
- [buildUUID4](FastExt.Base.md#builduuid4)
- [buildUUID8](FastExt.Base.md#builduuid8)
- [computeMaxDivisor](FastExt.Base.md#computemaxdivisor)
- [copy](FastExt.Base.md#copy)
- [copyToBoard](FastExt.Base.md#copytoboard)
- [deleteObjectAttr](FastExt.Base.md#deleteobjectattr)
- [dispatchTargetEvent](FastExt.Base.md#dispatchtargetevent)
- [download](FastExt.Base.md#download)
- [formatUrl](FastExt.Base.md#formaturl)
- [formatUrlVersion](FastExt.Base.md#formaturlversion)
- [getEmptyPromise](FastExt.Base.md#getemptypromise)
- [getNumberValue](FastExt.Base.md#getnumbervalue)
- [getOS](FastExt.Base.md#getos)
- [getSVGClassName](FastExt.Base.md#getsvgclassname)
- [getSVGIcon](FastExt.Base.md#getsvgicon)
- [getTargetBodyElement](FastExt.Base.md#gettargetbodyelement)
- [getTargetElement](FastExt.Base.md#gettargetelement)
- [getUrlContentType](FastExt.Base.md#geturlcontenttype)
- [getUrlParams](FastExt.Base.md#geturlparams)
- [guessDateFormat](FastExt.Base.md#guessdateformat)
- [inputFocusEnd](FastExt.Base.md#inputfocusend)
- [isElementInViewport](FastExt.Base.md#iselementinviewport)
- [loadCssCode](FastExt.Base.md#loadcsscode)
- [openUrl](FastExt.Base.md#openurl)
- [parseDate](FastExt.Base.md#parsedate)
- [prefixInteger](FastExt.Base.md#prefixinteger)
- [randomInt](FastExt.Base.md#randomint)
- [replacePlaceholder](FastExt.Base.md#replaceplaceholder)
- [runCallBack](FastExt.Base.md#runcallback)
- [toBool](FastExt.Base.md#tobool)
- [toByteUnit](FastExt.Base.md#tobyteunit)
- [toInt](FastExt.Base.md#toint)
- [toMaxString](FastExt.Base.md#tomaxstring)
- [toPlanParams](FastExt.Base.md#toplanparams)
- [toString](FastExt.Base.md#tostring)

## Constructors

### constructor

• **new Base**(): [`Base`](FastExt.Base.md)

#### Returns

[`Base`](FastExt.Base.md)

## Properties

### onlyIterator

▪ `Static` **onlyIterator**: `number` = `1`

## Methods

### buildOnlyCode

▸ **buildOnlyCode**(`prefix`): `string`

构建唯一标识符号

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `prefix` | `any` | 唯一标识的前缀 |

#### Returns

`string`

___

### buildOnlyNumber

▸ **buildOnlyNumber**(`prefix`): `string`

构建唯一标识符号

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `prefix` | `any` | 唯一标识的前缀 |

#### Returns

`string`

___

### buildUUID12

▸ **buildUUID12**(): `string`

构建uuid12的唯一编号

#### Returns

`string`

___

### buildUUID16

▸ **buildUUID16**(): `string`

构建uuid16的唯一编号

#### Returns

`string`

___

### buildUUID4

▸ **buildUUID4**(): `string`

构建uuid4的唯一编号

#### Returns

`string`

___

### buildUUID8

▸ **buildUUID8**(): `string`

构建uuid8的唯一编号

#### Returns

`string`

___

### computeMaxDivisor

▸ **computeMaxDivisor**(`num1`, `num2`): `number`

计算两个数之间的最大公约数

#### Parameters

| Name | Type |
| :------ | :------ |
| `num1` | `number` |
| `num2` | `number` |

#### Returns

`number`

___

### copy

▸ **copy**(`obj`): `any`

浅复制对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 待复制的对象 |

#### Returns

`any`

___

### copyToBoard

▸ **copyToBoard**(`content`): `void`

复制文本到剪贴板里

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `content` | `string` | 内容 |

#### Returns

`void`

___

### deleteObjectAttr

▸ **deleteObjectAttr**(`attr`, `...objects`): `void`

删除对象数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `attr` | `any` |
| `...objects` | `any` |

#### Returns

`void`

___

### dispatchTargetEvent

▸ **dispatchTargetEvent**(`targetDocument`, `targetElement`, `eventName`): `void`

模拟触发鼠标事件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `targetDocument` | `any` |  |
| `targetElement` | `any` |  |
| `eventName` | `any` | 事件名称 |

#### Returns

`void`

___

### download

▸ **download**(`url`, `fileName?`): `any`

动态触发浏览器下载文件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` | 文件的下载路径 |
| `fileName?` | `string` | 提示下载文件名 |

#### Returns

`any`

___

### formatUrl

▸ **formatUrl**(`url`, `params?`): `string`

格式化url地址，如果没有http开头，则自动拼接当前系统的http地址

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `any` |
| `params?` | `any` |

#### Returns

`string`

___

### formatUrlVersion

▸ **formatUrlVersion**(`url`, `params?`): `string`

格式化url地址，返回带上系统版本号参数

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |
| `params?` | `any` |

#### Returns

`string`

___

### getEmptyPromise

▸ **getEmptyPromise**(): `any`

获取空的Promise

#### Returns

`any`

___

### getNumberValue

▸ **getNumberValue**(`value`): `number`

提取纯数字

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`number`

___

### getOS

▸ **getOS**(): `string`

获取浏览器的操作系统

#### Returns

`string`

___

### getSVGClassName

▸ **getSVGClassName**(`...types`): `string`

获取svg标签的class名

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `...types` | `any`[] | 文件类型名 |

#### Returns

`string`

___

### getSVGIcon

▸ **getSVGIcon**(`className`): `string`

获取svg的标签格式

#### Parameters

| Name | Type |
| :------ | :------ |
| `className` | `any` |

#### Returns

`string`

___

### getTargetBodyElement

▸ **getTargetBodyElement**(`target`): `Element`

获取目标控件的body html节点对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |

#### Returns

`Element`

___

### getTargetElement

▸ **getTargetElement**(`target`): `Element`

获取目标控件的html节点对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |

#### Returns

`Element`

___

### getUrlContentType

▸ **getUrlContentType**(`url`, `callback`): `void`

请求url的并获得headers消息

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `any` | 地址 |
| `callback` | `any` | 回调函数 callback("un-know"); |

#### Returns

`void`

___

### getUrlParams

▸ **getUrlParams**(`url`, `paramName`): `string`

获取url地址中的参数值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` | 地址 |
| `paramName` | `string` | 参数名称 |

#### Returns

`string`

___

### guessDateFormat

▸ **guessDateFormat**(`value`): `string`

根据日期值猜测日期类型

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `any` | [FastExt.Dates.guessDateFormat](FastExt.Dates.md#guessdateformat) |

#### Returns

`string`

___

### inputFocusEnd

▸ **inputFocusEnd**(`obj`): `void`

将input的光标移动到末尾

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`void`

___

### isElementInViewport

▸ **isElementInViewport**(`element`): `boolean`

判断节点元素是否在可视区域

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `Element` |

#### Returns

`boolean`

___

### loadCssCode

▸ **loadCssCode**(`style`, `callBack`): `void`

动态加载css代码

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `style` | `any` | css代码 |
| `callBack` | `any` | 加载成功后回调 |

#### Returns

`void`

___

### openUrl

▸ **openUrl**(`url`, `target?`): `void`

动态打开URL地址

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` |  |
| `target?` | [`Target`](../enums/FastEnum.Target.md) | 打开方式 |

#### Returns

`void`

**`See`**

[FastEnum.Target](../enums/FastEnum.Target.md)

___

### parseDate

▸ **parseDate**(`dateValue`): `Date`

将字符串格式化日期

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `dateValue` | `string` | [FastExt.Dates.guessDateFormat](FastExt.Dates.md#guessdateformat) |

#### Returns

`Date`

___

### prefixInteger

▸ **prefixInteger**(`num`, `length`): `string`

数字补0

#### Parameters

| Name | Type |
| :------ | :------ |
| `num` | `any` |
| `length` | `any` |

#### Returns

`string`

___

### randomInt

▸ **randomInt**(`min`, `max`): `number`

随机范围整数

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `min` | `any` | 最小值 |
| `max` | `any` | 最大值 |

#### Returns

`number`

___

### replacePlaceholder

▸ **replacePlaceholder**(`mapValue`, `content`): `string`

替换占位符 ${key}或$[key]

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `mapValue` | `object` | key-value对象值 |
| `content` | `string` | 替换的内容 |

#### Returns

`string`

替换后的内容

___

### runCallBack

▸ **runCallBack**(`fun`, `param?`): `void`

动态执行回调函数，限制了重复执行

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `fun` | `any` | 函数对象 |
| `param?` | `object` | 函数参数 |

#### Returns

`void`

___

### toBool

▸ **toBool**(`obj`, `defaultValue?`): `boolean`

转换bool值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 带转换的对象 |
| `defaultValue?` | `any` | 默认值 |

#### Returns

`boolean`

___

### toByteUnit

▸ **toByteUnit**(`value`, `digits?`): `string`

将数字转成字节单位表示

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |
| `digits?` | `any` |

#### Returns

`string`

___

### toInt

▸ **toInt**(`value`, `defaultValue`): `number`

将对象转换为int类型

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `any` | 对象 |
| `defaultValue` | `any` | 默认值，当对象数据为空时返回 |

#### Returns

`number`

___

### toMaxString

▸ **toMaxString**(`value`, `maxLength`): `string`

转换为最大的字符串长度，超出长度将截取以省略号代替

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |
| `maxLength` | `any` |

#### Returns

`string`

___

### toPlanParams

▸ **toPlanParams**(`params`): `string`

将参数数组转成字符串拼接格式

#### Parameters

| Name | Type |
| :------ | :------ |
| `params` | `any`[] |

#### Returns

`string`

___

### toString

▸ **toString**(`value`, `defaultValue`): `string`

将对象转换为字符类型

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `any` | 对象 |
| `defaultValue` | `any` | 默认值，当对象数据为空时返回 |

#### Returns

`string`
