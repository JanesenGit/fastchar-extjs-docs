[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / AMapMarkerOverlayParam

# Class: AMapMarkerOverlayParam

[FastExt](../modules/FastExt.md).AMapMarkerOverlayParam

点标记覆盖物操作

## Hierarchy

- [`AMapItemBaseParam`](FastExt.AMapItemBaseParam.md)

  ↳ **`AMapMarkerOverlayParam`**

## Table of contents

### Constructors

- [constructor](FastExt.AMapMarkerOverlayParam.md#constructor)

### Properties

- [address](FastExt.AMapMarkerOverlayParam.md#address)
- [city](FastExt.AMapMarkerOverlayParam.md#city)
- [district](FastExt.AMapMarkerOverlayParam.md#district)
- [enabledEditor](FastExt.AMapMarkerOverlayParam.md#enablededitor)
- [enabledLocation](FastExt.AMapMarkerOverlayParam.md#enabledlocation)
- [enabledMapClickLocation](FastExt.AMapMarkerOverlayParam.md#enabledmapclicklocation)
- [enabledMapFlowCenter](FastExt.AMapMarkerOverlayParam.md#enabledmapflowcenter)
- [hideLoading](FastExt.AMapMarkerOverlayParam.md#hideloading)
- [lat](FastExt.AMapMarkerOverlayParam.md#lat)
- [lng](FastExt.AMapMarkerOverlayParam.md#lng)
- [lnglat](FastExt.AMapMarkerOverlayParam.md#lnglat)
- [onChange](FastExt.AMapMarkerOverlayParam.md#onchange)
- [province](FastExt.AMapMarkerOverlayParam.md#province)
- [showLoading](FastExt.AMapMarkerOverlayParam.md#showloading)
- [title](FastExt.AMapMarkerOverlayParam.md#title)
- [type](FastExt.AMapMarkerOverlayParam.md#type)
- [zoom](FastExt.AMapMarkerOverlayParam.md#zoom)

### Methods

- [isEmptyLngLat](FastExt.AMapMarkerOverlayParam.md#isemptylnglat)
- [notifyChange](FastExt.AMapMarkerOverlayParam.md#notifychange)
- [toResultInfo](FastExt.AMapMarkerOverlayParam.md#toresultinfo)
- [newParam](FastExt.AMapMarkerOverlayParam.md#newparam)

## Constructors

### constructor

• **new AMapMarkerOverlayParam**(): [`AMapMarkerOverlayParam`](FastExt.AMapMarkerOverlayParam.md)

#### Returns

[`AMapMarkerOverlayParam`](FastExt.AMapMarkerOverlayParam.md)

#### Inherited from

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[constructor](FastExt.AMapItemBaseParam.md#constructor)

## Properties

### address

• **address**: `string`

地理位置

___

### city

• **city**: `string`

所在城市

___

### district

• **district**: `string`

所在区/县/街道

___

### enabledEditor

• **enabledEditor**: `boolean` = `false`

是否编辑

___

### enabledLocation

• **enabledLocation**: `boolean` = `true`

在 enabledEditor 为 true的条件下 当标记点坐标信息为空时，启用当前定位信息，

___

### enabledMapClickLocation

• **enabledMapClickLocation**: `boolean` = `true`

在 enabledEditor 为 true的条件下 是否启用坐标切换到点击地图的位置

___

### enabledMapFlowCenter

• **enabledMapFlowCenter**: `boolean` = `true`

在 enabledEditor 为 true的条件下 是否启用地图中心视角以当前marker为主

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

### lat

• **lat**: `number`

纬度

___

### lng

• **lng**: `number`

经度

___

### lnglat

• **lnglat**: `string`

标记点的经纬度，例如：110.568434,32.377389

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

### province

• **province**: `string`

所在省份

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

• **title**: `string` = `"地图坐标"`

#### Overrides

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[title](FastExt.AMapItemBaseParam.md#title)

___

### type

• **type**: `string` = `FastEnum.MapItemType.marker_overlay`

#### Overrides

[AMapItemBaseParam](FastExt.AMapItemBaseParam.md).[type](FastExt.AMapItemBaseParam.md#type)

___

### zoom

• **zoom**: `number` = `-1`

地图缩放级别

## Methods

### isEmptyLngLat

▸ **isEmptyLngLat**(): `boolean`

#### Returns

`boolean`

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

▸ **newParam**(`param?`): [`AMapMarkerOverlayParam`](FastExt.AMapMarkerOverlayParam.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `param?` | `any` |

#### Returns

[`AMapMarkerOverlayParam`](FastExt.AMapMarkerOverlayParam.md)
