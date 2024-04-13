[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / AMapDistrictLayerParam

# Class: AMapDistrictLayerParam

[FastExt](../modules/FastExt.md).AMapDistrictLayerParam

中国行政区域的图层边界显示

## Hierarchy

- [`AMapItemBaseParam`](FastExt.AMapItemBaseParam.md)

  ↳ **`AMapDistrictLayerParam`**

## Table of contents

### Constructors

- [constructor](FastExt.AMapDistrictLayerParam.md#constructor)

### Properties

- [adcode](FastExt.AMapDistrictLayerParam.md#adcode)
- [city\_stroke](FastExt.AMapDistrictLayerParam.md#city_stroke)
- [county\_stroke](FastExt.AMapDistrictLayerParam.md#county_stroke)
- [depth](FastExt.AMapDistrictLayerParam.md#depth)
- [fill](FastExt.AMapDistrictLayerParam.md#fill)
- [hideLoading](FastExt.AMapDistrictLayerParam.md#hideloading)
- [onChange](FastExt.AMapDistrictLayerParam.md#onchange)
- [province\_stroke](FastExt.AMapDistrictLayerParam.md#province_stroke)
- [showLoading](FastExt.AMapDistrictLayerParam.md#showloading)
- [title](FastExt.AMapDistrictLayerParam.md#title)
- [type](FastExt.AMapDistrictLayerParam.md#type)
- [zIndex](FastExt.AMapDistrictLayerParam.md#zindex)

### Methods

- [notifyChange](FastExt.AMapDistrictLayerParam.md#notifychange)
- [toResultInfo](FastExt.AMapDistrictLayerParam.md#toresultinfo)
- [newParam](FastExt.AMapDistrictLayerParam.md#newparam)

## Constructors

### constructor

• **new AMapDistrictLayerParam**(): [`AMapDistrictLayerParam`](FastExt.AMapDistrictLayerParam.md)

#### Returns

[`AMapDistrictLayerParam`](FastExt.AMapDistrictLayerParam.md)

#### Inherited from

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[constructor](FastExt.AMapItemBaseParam.md#constructor)

## Properties

### adcode

• **adcode**: `string`[]

需要显示的地区编码，可以：省、市、区同时存在

___

### city\_stroke

• **city\_stroke**: `string` = `"red"`

城市界的边框颜色

___

### county\_stroke

• **county\_stroke**: `string` = `"red"`

区/县界的边框颜色

___

### depth

• **depth**: `number` = `2`

设定数据的层级深度，depth为0的时候只显示国家面，depth为1的时候显示省级， 当国家为中国时设置depth为2的可以显示市一级

___

### fill

• **fill**: `string` = `"red"`

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

### province\_stroke

• **province\_stroke**: `string` = `"red"`

省边界的边框颜色

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

### title

• **title**: `string` = `"中国城市边界图层"`

#### Overrides

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[title](FastExt.AMapItemBaseParam.md#title)

___

### type

• **type**: `string` = `FastEnum.MapItemType.district_layer`

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

#### Inherited from

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[toResultInfo](FastExt.AMapItemBaseParam.md#toresultinfo)

___

### newParam

▸ **newParam**(`param?`): [`AMapDistrictLayerParam`](FastExt.AMapDistrictLayerParam.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `param?` | `any` |

#### Returns

[`AMapDistrictLayerParam`](FastExt.AMapDistrictLayerParam.md)
