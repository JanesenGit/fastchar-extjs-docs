[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / AMapRectangleOverlayParam

# Class: AMapRectangleOverlayParam

[FastExt](../modules/FastExt.md).AMapRectangleOverlayParam

地图矩形图层的参数

## Hierarchy

- [`AMapItemBaseParam`](FastExt.AMapItemBaseParam.md)

  ↳ **`AMapRectangleOverlayParam`**

## Table of contents

### Constructors

- [constructor](FastExt.AMapRectangleOverlayParam.md#constructor)

### Properties

- [enabledEditor](FastExt.AMapRectangleOverlayParam.md#enablededitor)
- [fillColor](FastExt.AMapRectangleOverlayParam.md#fillcolor)
- [hideLoading](FastExt.AMapRectangleOverlayParam.md#hideloading)
- [imageLayerParam](FastExt.AMapRectangleOverlayParam.md#imagelayerparam)
- [northEastLngLat](FastExt.AMapRectangleOverlayParam.md#northeastlnglat)
- [onChange](FastExt.AMapRectangleOverlayParam.md#onchange)
- [showLoading](FastExt.AMapRectangleOverlayParam.md#showloading)
- [sizeToContainer](FastExt.AMapRectangleOverlayParam.md#sizetocontainer)
- [southWestLngLat](FastExt.AMapRectangleOverlayParam.md#southwestlnglat)
- [strokeColor](FastExt.AMapRectangleOverlayParam.md#strokecolor)
- [title](FastExt.AMapRectangleOverlayParam.md#title)
- [type](FastExt.AMapRectangleOverlayParam.md#type)
- [zIndex](FastExt.AMapRectangleOverlayParam.md#zindex)

### Methods

- [bindImageLayer](FastExt.AMapRectangleOverlayParam.md#bindimagelayer)
- [notifyChange](FastExt.AMapRectangleOverlayParam.md#notifychange)
- [toResultInfo](FastExt.AMapRectangleOverlayParam.md#toresultinfo)
- [newParam](FastExt.AMapRectangleOverlayParam.md#newparam)

## Constructors

### constructor

• **new AMapRectangleOverlayParam**(): [`AMapRectangleOverlayParam`](FastExt.AMapRectangleOverlayParam.md)

#### Returns

[`AMapRectangleOverlayParam`](FastExt.AMapRectangleOverlayParam.md)

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

### imageLayerParam

• **imageLayerParam**: [`AMapImageLayerParam`](FastExt.AMapImageLayerParam.md)

绑定的图片图层

___

### northEastLngLat

• **northEastLngLat**: `string`

东北坐标，右上坐标，例如：110.969035,32.667611

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

### sizeToContainer

• **sizeToContainer**: `any`

矩形的宽高，相对地图显示的容器

___

### southWestLngLat

• **southWestLngLat**: `string`

西南坐标，左下坐标，例如：110.568434,32.377389

___

### strokeColor

• **strokeColor**: `string` = `'#80d8ff'`

边框色

___

### title

• **title**: `string` = `"矩形区域选择"`

#### Overrides

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[title](FastExt.AMapItemBaseParam.md#title)

___

### type

• **type**: `string` = `FastEnum.MapItemType.rectangle_overlay`

#### Overrides

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[type](FastExt.AMapItemBaseParam.md#type)

___

### zIndex

• **zIndex**: `number`

层级

## Methods

### bindImageLayer

▸ **bindImageLayer**(): [`AMapImageLayerParam`](FastExt.AMapImageLayerParam.md)

#### Returns

[`AMapImageLayerParam`](FastExt.AMapImageLayerParam.md)

___

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

▸ **newParam**(`param?`): [`AMapRectangleOverlayParam`](FastExt.AMapRectangleOverlayParam.md)

实例化一个对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `param?` | `any` | 配置 |

#### Returns

[`AMapRectangleOverlayParam`](FastExt.AMapRectangleOverlayParam.md)
