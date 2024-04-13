[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / AMapComponent

# Class: AMapComponent

[FastExt](../modules/FastExt.md).AMapComponent

地图组件绑定extjs组件相关操作

## Hierarchy

- [`AMapObject`](FastExt.AMapObject.md)

  ↳ **`AMapComponent`**

## Table of contents

### Constructors

- [constructor](FastExt.AMapComponent.md#constructor)

### Properties

- [\_map](FastExt.AMapComponent.md#_map)
- [cmb](FastExt.AMapComponent.md#cmb)

### Accessors

- [map](FastExt.AMapComponent.md#map)

### Methods

- [addDistrictLayer](FastExt.AMapComponent.md#adddistrictlayer)
- [addImageLayer](FastExt.AMapComponent.md#addimagelayer)
- [addMarkerOverlay](FastExt.AMapComponent.md#addmarkeroverlay)
- [addPolygonOverlay](FastExt.AMapComponent.md#addpolygonoverlay)
- [addRectangleOverlay](FastExt.AMapComponent.md#addrectangleoverlay)
- [beginDrawPolygonOverlay](FastExt.AMapComponent.md#begindrawpolygonoverlay)
- [beginDrawRectangleOverlay](FastExt.AMapComponent.md#begindrawrectangleoverlay)
- [clearEvents](FastExt.AMapComponent.md#clearevents)
- [computeAMapBoundsSizeToContainer](FastExt.AMapComponent.md#computeamapboundssizetocontainer)
- [destroy](FastExt.AMapComponent.md#destroy)
- [fitView](FastExt.AMapComponent.md#fitview)
- [getDistrictLayer](FastExt.AMapComponent.md#getdistrictlayer)
- [getEnabledEditorOverlay](FastExt.AMapComponent.md#getenablededitoroverlay)
- [getImageLayer](FastExt.AMapComponent.md#getimagelayer)
- [getLayer](FastExt.AMapComponent.md#getlayer)
- [getMarkerOverlay](FastExt.AMapComponent.md#getmarkeroverlay)
- [getOverlay](FastExt.AMapComponent.md#getoverlay)
- [getPolygonOverlay](FastExt.AMapComponent.md#getpolygonoverlay)
- [getRectangleOverlay](FastExt.AMapComponent.md#getrectangleoverlay)
- [off](FastExt.AMapComponent.md#off)
- [on](FastExt.AMapComponent.md#on)
- [removeDistrictLayer](FastExt.AMapComponent.md#removedistrictlayer)
- [removeImageLayer](FastExt.AMapComponent.md#removeimagelayer)
- [removeLayer](FastExt.AMapComponent.md#removelayer)
- [removeMarkerOverlay](FastExt.AMapComponent.md#removemarkeroverlay)
- [removeOverlay](FastExt.AMapComponent.md#removeoverlay)
- [removePolygonOverlay](FastExt.AMapComponent.md#removepolygonoverlay)
- [removeRectangleOverlay](FastExt.AMapComponent.md#removerectangleoverlay)
- [safeStartLocation](FastExt.AMapComponent.md#safestartlocation)
- [searchAddress](FastExt.AMapComponent.md#searchaddress)
- [searchLngLat](FastExt.AMapComponent.md#searchlnglat)
- [setZoom](FastExt.AMapComponent.md#setzoom)

## Constructors

### constructor

• **new AMapComponent**(`cmb`): [`AMapComponent`](FastExt.AMapComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `cmb` | `any` |

#### Returns

[`AMapComponent`](FastExt.AMapComponent.md)

#### Overrides

[AMapObject](FastExt.AMapObject.md).[constructor](FastExt.AMapObject.md#constructor)

## Properties

### \_map

• `Protected` **\_map**: `any`

地图对象

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[_map](FastExt.AMapObject.md#_map)

___

### cmb

• **cmb**: `any`

## Accessors

### map

• `get` **map**(): `any`

#### Returns

`any`

#### Overrides

AMapObject.map

## Methods

### addDistrictLayer

▸ **addDistrictLayer**(`param`): `any`

添加中国城市边界图层

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapDistrictLayerParam`](FastExt.AMapDistrictLayerParam.md) |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[addDistrictLayer](FastExt.AMapObject.md#adddistrictlayer)

___

### addImageLayer

▸ **addImageLayer**(`param`): `any`

在地图上添加图片图层

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapImageLayerParam`](FastExt.AMapImageLayerParam.md) |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[addImageLayer](FastExt.AMapObject.md#addimagelayer)

___

### addMarkerOverlay

▸ **addMarkerOverlay**(`param`): `any`

在地图上添加点标记

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapMarkerOverlayParam`](FastExt.AMapMarkerOverlayParam.md) |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[addMarkerOverlay](FastExt.AMapObject.md#addmarkeroverlay)

___

### addPolygonOverlay

▸ **addPolygonOverlay**(`param`): `any`

在地图上添加多边形覆盖物

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapPolygonOverlayParam`](FastExt.AMapPolygonOverlayParam.md) |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[addPolygonOverlay](FastExt.AMapObject.md#addpolygonoverlay)

___

### addRectangleOverlay

▸ **addRectangleOverlay**(`param`): `any`

在地图上添加矩形覆盖物

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapRectangleOverlayParam`](FastExt.AMapRectangleOverlayParam.md) |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[addRectangleOverlay](FastExt.AMapObject.md#addrectangleoverlay)

___

### beginDrawPolygonOverlay

▸ **beginDrawPolygonOverlay**(`param`): `void`

在组件绑定的map对象上开始画多边形覆盖物

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapPolygonOverlayParam`](FastExt.AMapPolygonOverlayParam.md) |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[beginDrawPolygonOverlay](FastExt.AMapObject.md#begindrawpolygonoverlay)

___

### beginDrawRectangleOverlay

▸ **beginDrawRectangleOverlay**(`param`): `void`

在组件绑定的map对象上开始画矩形覆盖物

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapRectangleOverlayParam`](FastExt.AMapRectangleOverlayParam.md) |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[beginDrawRectangleOverlay](FastExt.AMapObject.md#begindrawrectangleoverlay)

___

### clearEvents

▸ **clearEvents**(`event`): `void`

清除地图的指定所有事件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | `string` | 事件名称 |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[clearEvents](FastExt.AMapObject.md#clearevents)

___

### computeAMapBoundsSizeToContainer

▸ **computeAMapBoundsSizeToContainer**(`bounds`): `Object`

计算 AMapBounds 对象边界的相对Map地图展示的容器宽高

#### Parameters

| Name | Type |
| :------ | :------ |
| `bounds` | `any` |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `height` | `number` |
| `width` | `number` |

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[computeAMapBoundsSizeToContainer](FastExt.AMapObject.md#computeamapboundssizetocontainer)

___

### destroy

▸ **destroy**(): `void`

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[destroy](FastExt.AMapObject.md#destroy)

___

### fitView

▸ **fitView**(`overlayArray?`): `void`

缩放地图，显示出所有覆盖物

#### Parameters

| Name | Type |
| :------ | :------ |
| `overlayArray?` | `any` |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[fitView](FastExt.AMapObject.md#fitview)

___

### getDistrictLayer

▸ **getDistrictLayer**(`param`): `any`

获取中国城市边界图层

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapDistrictLayerParam`](FastExt.AMapDistrictLayerParam.md) |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[getDistrictLayer](FastExt.AMapObject.md#getdistrictlayer)

___

### getEnabledEditorOverlay

▸ **getEnabledEditorOverlay**(`type`): `any`[]

获取启用编辑功能的指定type类型的覆盖物

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `string` |

#### Returns

`any`[]

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[getEnabledEditorOverlay](FastExt.AMapObject.md#getenablededitoroverlay)

___

### getImageLayer

▸ **getImageLayer**(`param`): `any`

获取图片图层的对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapImageLayerParam`](FastExt.AMapImageLayerParam.md) |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[getImageLayer](FastExt.AMapObject.md#getimagelayer)

___

### getLayer

▸ **getLayer**(`selfId`): `any`

获取地图上指定selfId的图层

#### Parameters

| Name | Type |
| :------ | :------ |
| `selfId` | `string` |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[getLayer](FastExt.AMapObject.md#getlayer)

___

### getMarkerOverlay

▸ **getMarkerOverlay**(`param`): `any`

获取地图上的标记，只能获取通过FastExt对象添加的marker对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapMarkerOverlayParam`](FastExt.AMapMarkerOverlayParam.md) |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[getMarkerOverlay](FastExt.AMapObject.md#getmarkeroverlay)

___

### getOverlay

▸ **getOverlay**(`selfId`): `any`

获取地图上指定selfId的覆盖物

#### Parameters

| Name | Type |
| :------ | :------ |
| `selfId` | `string` |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[getOverlay](FastExt.AMapObject.md#getoverlay)

___

### getPolygonOverlay

▸ **getPolygonOverlay**(`param`): `any`

在地图上获取矩形覆盖物对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapPolygonOverlayParam`](FastExt.AMapPolygonOverlayParam.md) |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[getPolygonOverlay](FastExt.AMapObject.md#getpolygonoverlay)

___

### getRectangleOverlay

▸ **getRectangleOverlay**(`param`): `any`

在地图上获取矩形覆盖物对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapRectangleOverlayParam`](FastExt.AMapRectangleOverlayParam.md) |

#### Returns

`any`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[getRectangleOverlay](FastExt.AMapObject.md#getrectangleoverlay)

___

### off

▸ **off**(`event`, `func`): `void`

移除地图事件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | `string` | 事件名称 |
| `func` | `any` | 事件回调函数 |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[off](FastExt.AMapObject.md#off)

___

### on

▸ **on**(`event`, `func`): `void`

添加地图事件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `event` | `string` | 事件名称 |
| `func` | `any` | 事件回调函数 |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[on](FastExt.AMapObject.md#on)

___

### removeDistrictLayer

▸ **removeDistrictLayer**(`param`): `void`

移除中国城市边界图层

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapDistrictLayerParam`](FastExt.AMapDistrictLayerParam.md) |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[removeDistrictLayer](FastExt.AMapObject.md#removedistrictlayer)

___

### removeImageLayer

▸ **removeImageLayer**(`param`): `void`

移除图片图层

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapImageLayerParam`](FastExt.AMapImageLayerParam.md) |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[removeImageLayer](FastExt.AMapObject.md#removeimagelayer)

___

### removeLayer

▸ **removeLayer**(`selfId`): `void`

移除地图上获取指定selfId的图层

#### Parameters

| Name | Type |
| :------ | :------ |
| `selfId` | `string` |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[removeLayer](FastExt.AMapObject.md#removelayer)

___

### removeMarkerOverlay

▸ **removeMarkerOverlay**(`param`): `void`

删除地图上的标记

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapMarkerOverlayParam`](FastExt.AMapMarkerOverlayParam.md) |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[removeMarkerOverlay](FastExt.AMapObject.md#removemarkeroverlay)

___

### removeOverlay

▸ **removeOverlay**(`selfId`): `void`

移除地图上获取指定selfId的覆盖物

#### Parameters

| Name | Type |
| :------ | :------ |
| `selfId` | `string` |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[removeOverlay](FastExt.AMapObject.md#removeoverlay)

___

### removePolygonOverlay

▸ **removePolygonOverlay**(`param`): `void`

移除组件地图上获取矩形覆盖物对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapPolygonOverlayParam`](FastExt.AMapPolygonOverlayParam.md) |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[removePolygonOverlay](FastExt.AMapObject.md#removepolygonoverlay)

___

### removeRectangleOverlay

▸ **removeRectangleOverlay**(`param`): `void`

移除地图上获取矩形覆盖物对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `param` | [`AMapRectangleOverlayParam`](FastExt.AMapRectangleOverlayParam.md) |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[removeRectangleOverlay](FastExt.AMapObject.md#removerectangleoverlay)

___

### safeStartLocation

▸ **safeStartLocation**(): `ExtPromise`

以安全模式获取当前浏览器的定位，如果定位失败，默认返回：new AMap.LngLat(116.410394, 39.934376, true)

#### Returns

`ExtPromise`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[safeStartLocation](FastExt.AMapObject.md#safestartlocation)

___

### searchAddress

▸ **searchAddress**(`address`): `ExtPromise`

地图搜索位置信息

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |

#### Returns

`ExtPromise`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[searchAddress](FastExt.AMapObject.md#searchaddress)

___

### searchLngLat

▸ **searchLngLat**(`lnglat`): `ExtPromise`

搜索坐标位置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `lnglat` | `any` | AMapLngLat对象 |

#### Returns

`ExtPromise`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[searchLngLat](FastExt.AMapObject.md#searchlnglat)

___

### setZoom

▸ **setZoom**(`zoom`): `void`

设置地图显示的缩放级别，参数 zoom 可设范围：[2, 30]

#### Parameters

| Name | Type |
| :------ | :------ |
| `zoom` | `number` |

#### Returns

`void`

#### Inherited from

[AMapObject](FastExt.AMapObject.md).[setZoom](FastExt.AMapObject.md#setzoom)
