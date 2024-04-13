[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Component

# Class: Component

[FastExt](../modules/FastExt.md).Component

Ext组件相关方法功能

## Table of contents

### Constructors

- [constructor](FastExt.Component.md#constructor)

### Properties

- [maxZIndex](FastExt.Component.md#maxzindex)

### Methods

- [countVisible](FastExt.Component.md#countvisible)
- [futureQuery](FastExt.Component.md#futurequery)
- [getMaxZIndex](FastExt.Component.md#getmaxzindex)
- [getTargetBodyElement](FastExt.Component.md#gettargetbodyelement)
- [getTargetElement](FastExt.Component.md#gettargetelement)
- [holdEditorMenu](FastExt.Component.md#holdeditormenu)
- [isCenterByContainer](FastExt.Component.md#iscenterbycontainer)
- [isRealReadOnly](FastExt.Component.md#isrealreadonly)
- [isSameByContainer](FastExt.Component.md#issamebycontainer)
- [resumeEditorMenu](FastExt.Component.md#resumeeditormenu)
- [shakeComment](FastExt.Component.md#shakecomment)
- [simpleReadOnly](FastExt.Component.md#simplereadonly)

## Constructors

### constructor

• **new Component**(): [`Component`](FastExt.Component.md)

#### Returns

[`Component`](FastExt.Component.md)

## Properties

### maxZIndex

▪ `Static` **maxZIndex**: `number` = `2147483647`

## Methods

### countVisible

▸ **countVisible**(`cmpArray`): `number`

统计显示的数量

#### Parameters

| Name | Type |
| :------ | :------ |
| `cmpArray` | [] |

#### Returns

`number`

___

### futureQuery

▸ **futureQuery**(`selector`, `callback`, `timeout?`, `queryOwner?`): `void`

预测将要获得组件对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `selector` | `string` | 组件选择器 |
| `callback` | `any` | 获得组件后的回调 |
| `timeout?` | `number` | 超时时间，单位：毫秒 |
| `queryOwner?` | `any` | 查找组件的父类，默认全局 |

#### Returns

`void`

___

### getMaxZIndex

▸ **getMaxZIndex**(`defaultIndex`): `number`

获取body下最大的z-index，排除 FastExt.Component.pageMaxZIndex

#### Parameters

| Name | Type |
| :------ | :------ |
| `defaultIndex` | `number` |

#### Returns

`number`

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

### holdEditorMenu

▸ **holdEditorMenu**(`target`): `void`

保持目标组件的编辑菜单不会自动关闭

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |

#### Returns

`void`

___

### isCenterByContainer

▸ **isCenterByContainer**(`cmb`): `boolean`

判断组件是否处于父级容器的中间位置

#### Parameters

| Name | Type |
| :------ | :------ |
| `cmb` | `any` |

#### Returns

`boolean`

___

### isRealReadOnly

▸ **isRealReadOnly**(`field`): `boolean`

判断目标组件是否readOnly,深入判断了html标签的readOnly属性

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |

#### Returns

`boolean`

___

### isSameByContainer

▸ **isSameByContainer**(`cmb1`, `cmb2`): `boolean`

判断组件是否处于同一个容器中

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cmb1` | `any` | 组件1 |
| `cmb2` | `any` | 组件2 |

#### Returns

`boolean`

___

### resumeEditorMenu

▸ **resumeEditorMenu**(`target`): `void`

恢复目标组件的编辑菜单会自动关闭

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |

#### Returns

`void`

___

### shakeComment

▸ **shakeComment**(`cmb`, `callBack?`, `shakeCount?`): `void`

抖动控件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cmb` | `any` | 待抖动的控件[Ext.Component] |
| `callBack?` | `any` | 抖动结束的回调函数function(){} |
| `shakeCount?` | `number` | 抖动次数 |

#### Returns

`void`

___

### simpleReadOnly

▸ **simpleReadOnly**(`field`, `readOnly`): `void`

将使用 setReadOnlyAttr 方法执行设置readOnly 避免将trigger的按钮禁用了

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |
| `readOnly` | `boolean` |

#### Returns

`void`
