[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / AMapPolygonOverlayParam

# Class: AMapPolygonOverlayParam

[FastExt](../modules/FastExt.md).AMapPolygonOverlayParam

地图多边形图层的参数

## Hierarchy

- [`AMapItemBaseParam`](FastExt.AMapItemBaseParam.md)

  ↳ **`AMapPolygonOverlayParam`**

## Table of contents

### Constructors

- [constructor](FastExt.AMapPolygonOverlayParam.md#constructor)

### Properties

- [enabledEditor](FastExt.AMapPolygonOverlayParam.md#enablededitor)
- [fillColor](FastExt.AMapPolygonOverlayParam.md#fillcolor)
- [hideLoading](FastExt.AMapPolygonOverlayParam.md#hideloading)
- [onChange](FastExt.AMapPolygonOverlayParam.md#onchange)
- [path](FastExt.AMapPolygonOverlayParam.md#path)
- [showLoading](FastExt.AMapPolygonOverlayParam.md#showloading)
- [strokeColor](FastExt.AMapPolygonOverlayParam.md#strokecolor)
- [title](FastExt.AMapPolygonOverlayParam.md#title)
- [type](FastExt.AMapPolygonOverlayParam.md#type)
- [zIndex](FastExt.AMapPolygonOverlayParam.md#zindex)

### Methods

- [notifyChange](FastExt.AMapPolygonOverlayParam.md#notifychange)
- [toResultInfo](FastExt.AMapPolygonOverlayParam.md#toresultinfo)
- [newParam](FastExt.AMapPolygonOverlayParam.md#newparam)

## Constructors

### constructor

• **new AMapPolygonOverlayParam**(): [`AMapPolygonOverlayParam`](FastExt.AMapPolygonOverlayParam.md)

#### Returns

[`AMapPolygonOverlayParam`](FastExt.AMapPolygonOverlayParam.md)

#### Inherited from

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[constructor](FastExt.AMapItemBaseParam.md#constructor)

## Properties

### enabledEditor

• **enabledEditor**: `boolean` = `false`

是否编辑

___

### fillColor

• **fillColor**: `string` = `'#00b0ff'`

填充色

___

### hideLoading

• **hideLoading**: () => `void`

#### Type declaration

▸ (): `void`

##### Returns

`void`

#### Inherited from

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[hideLoading](FastExt.AMapItemBaseParam.md#hideloading)

___

### onChange

• **onChange**: () => `void`

#### Type declaration

▸ (): `void`

##### Returns

`void`

#### Inherited from

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[onChange](FastExt.AMapItemBaseParam.md#onchange)

___

### path

• **path**: `string`[]

多边形的坐标数组，例如：["110.605566,32.491494","110.614341,32.492633",……]

___

### showLoading

• **showLoading**: (`message?`: `string`) => `void`

#### Type declaration

▸ (`message?`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `message?` | `string` |

##### Returns

`void`

#### Inherited from

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[showLoading](FastExt.AMapItemBaseParam.md#showloading)

___

### strokeColor

• **strokeColor**: `string` = `'#80d8ff'`

边框色

___

### title

• **title**: `string` = `"多边形区域选择"`

#### Overrides

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[title](FastExt.AMapItemBaseParam.md#title)

___

### type

• **type**: `string` = `FastEnum.MapItemType.polygon_overlay`

#### Overrides

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[type](FastExt.AMapItemBaseParam.md#type)

___

### zIndex

• **zIndex**: `number`

层级

## Methods

### notifyChange

▸ **notifyChange**(): `void`

#### Returns

`void`

#### Inherited from

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[notifyChange](FastExt.AMapItemBaseParam.md#notifychange)

___

### toResultInfo

▸ **toResultInfo**(): `string`

#### Returns

`string`

#### Overrides

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[toResultInfo](FastExt.AMapItemBaseParam.md#toresultinfo)

___

### newParam

▸ **newParam**(`param?`): [`AMapPolygonOverlayParam`](FastExt.AMapPolygonOverlayParam.md)

实例化一个对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `param?` | `any` | 配置 |

#### Returns

[`AMapPolygonOverlayParam`](FastExt.AMapPolygonOverlayParam.md)
