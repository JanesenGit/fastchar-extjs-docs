[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / AMapObject

# Class: AMapObject

[FastExt](../modules/FastExt.md).AMapObject

地图对象封装

## Hierarchy

- **`AMapObject`**

  ↳ [`AMapComponent`](FastExt.AMapComponent.md)

## Table of contents

### Constructors

- [constructor](FastExt.AMapObject.md#constructor)

### Properties

- [\_map](FastExt.AMapObject.md#_map)

### Accessors

- [map](FastExt.AMapObject.md#map)

### Methods

- [addDistrictLayer](FastExt.AMapObject.md#adddistrictlayer)
- [addImageLayer](FastExt.AMapObject.md#addimagelayer)
- [addMarkerOverlay](FastExt.AMapObject.md#addmarkeroverlay)
- [addPolygonOverlay](FastExt.AMapObject.md#addpolygonoverlay)
- [addRectangleOverlay](FastExt.AMapObject.md#addrectangleoverlay)
- [beginDrawPolygonOverlay](FastExt.AMapObject.md#begindrawpolygonoverlay)
- [beginDrawRectangleOverlay](FastExt.AMapObject.md#begindrawrectangleoverlay)
- [clearEvents](FastExt.AMapObject.md#clearevents)
- [computeAMapBoundsSizeToContainer](FastExt.AMapObject.md#computeamapboundssizetocontainer)
- [destroy](FastExt.AMapObject.md#destroy)
- [fitView](FastExt.AMapObject.md#fitview)
- [getDistrictLayer](FastExt.AMapObject.md#getdistrictlayer)
- [getEnabledEditorOverlay](FastExt.AMapObject.md#getenablededitoroverlay)
- [getImageLayer](FastExt.AMapObject.md#getimagelayer)
- [getLayer](FastExt.AMapObject.md#getlayer)
- [getMarkerOverlay](FastExt.AMapObject.md#getmarkeroverlay)
- [getOverlay](FastExt.AMapObject.md#getoverlay)
- [getPolygonOverlay](FastExt.AMapObject.md#getpolygonoverlay)
- [getRectangleOverlay](FastExt.AMapObject.md#getrectangleoverlay)
- [off](FastExt.AMapObject.md#off)
- [on](FastExt.AMapObject.md#on)
- [removeDistrictLayer](FastExt.AMapObject.md#removedistrictlayer)
- [removeImageLayer](FastExt.AMapObject.md#removeimagelayer)
- [removeLayer](FastExt.AMapObject.md#removelayer)
- [removeMarkerOverlay](FastExt.AMapObject.md#removemarkeroverlay)
- [removeOverlay](FastExt.AMapObject.md#removeoverlay)
- [removePolygonOverlay](FastExt.AMapObject.md#removepolygonoverlay)
- [removeRectangleOverlay](FastExt.AMapObject.md#removerectangleoverlay)
- [safeStartLocation](FastExt.AMapObject.md#safestartlocation)
- [searchAddress](FastExt.AMapObject.md#searchaddress)
- [searchLngLat](FastExt.AMapObject.md#searchlnglat)
- [setZoom](FastExt.AMapObject.md#setzoom)

## Constructors

### constructor

• **new AMapObject**(`map?`): [`AMapObject`](FastExt.AMapObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `map?` | `any` |

#### Returns

[`AMapObject`](FastExt.AMapObject.md)

## Properties

### \_map

• `Protected` **\_map**: `any`

地图对象

## Accessors

### map

• `get` **map**(): `any`

#### Returns

`any`

• `set` **map**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `any` |

#### Returns

`void`

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

___

### destroy

▸ **destroy**(): `void`

#### Returns

`void`

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

___

### safeStartLocation

▸ **safeStartLocation**(): `ExtPromise`

以安全模式获取当前浏览器的定位，如果定位失败，默认返回：new AMap.LngLat(116.410394, 39.934376, true)

#### Returns

`ExtPromise`

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
