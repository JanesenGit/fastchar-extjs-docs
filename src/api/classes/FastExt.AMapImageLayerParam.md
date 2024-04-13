[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / AMapImageLayerParam

# Class: AMapImageLayerParam

[FastExt](../modules/FastExt.md).AMapImageLayerParam

图片图层的参数

## Hierarchy

- [`AMapItemBaseParam`](FastExt.AMapItemBaseParam.md)

  ↳ **`AMapImageLayerParam`**

## Table of contents

### Constructors

- [constructor](FastExt.AMapImageLayerParam.md#constructor)

### Properties

- [hideLoading](FastExt.AMapImageLayerParam.md#hideloading)
- [northEastLngLat](FastExt.AMapImageLayerParam.md#northeastlnglat)
- [onChange](FastExt.AMapImageLayerParam.md#onchange)
- [showLoading](FastExt.AMapImageLayerParam.md#showloading)
- [southWestLngLat](FastExt.AMapImageLayerParam.md#southwestlnglat)
- [title](FastExt.AMapImageLayerParam.md#title)
- [type](FastExt.AMapImageLayerParam.md#type)
- [url](FastExt.AMapImageLayerParam.md#url)
- [zIndex](FastExt.AMapImageLayerParam.md#zindex)

### Methods

- [notifyChange](FastExt.AMapImageLayerParam.md#notifychange)
- [toResultInfo](FastExt.AMapImageLayerParam.md#toresultinfo)
- [newParam](FastExt.AMapImageLayerParam.md#newparam)

## Constructors

### constructor

• **new AMapImageLayerParam**(): [`AMapImageLayerParam`](FastExt.AMapImageLayerParam.md)

#### Returns

[`AMapImageLayerParam`](FastExt.AMapImageLayerParam.md)

#### Inherited from

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[constructor](FastExt.AMapItemBaseParam.md#constructor)

## Properties

### hideLoading

• **hideLoading**: () => `void`

#### Type declaration

▸ (): `void`

##### Returns

`void`

#### Inherited from

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[hideLoading](FastExt.AMapItemBaseParam.md#hideloading)

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

### southWestLngLat

• **southWestLngLat**: `string`

西南坐标，左下坐标，例如：110.568434,32.377389

___

### title

• **title**: `string` = `"图片图层"`

#### Overrides

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[title](FastExt.AMapItemBaseParam.md#title)

___

### type

• **type**: `string` = `FastEnum.MapItemType.image_layer`

#### Overrides

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[type](FastExt.AMapItemBaseParam.md#type)

___

### url

• **url**: `string`

图片的地址

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

#### Inherited from

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[toResultInfo](FastExt.AMapItemBaseParam.md#toresultinfo)

___

### newParam

▸ **newParam**(`param?`): [`AMapImageLayerParam`](FastExt.AMapImageLayerParam.md)

实例化一个对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `param?` | `any` | 配置 |

#### Returns

[`AMapImageLayerParam`](FastExt.AMapImageLayerParam.md)
