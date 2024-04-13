[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / AMapHelper

# Class: AMapHelper

[FastExt](../modules/FastExt.md).AMapHelper

地图工具类

## Table of contents

### Constructors

- [constructor](FastExt.AMapHelper.md#constructor)

### Methods

- [amapBoundsToStringArray](FastExt.AMapHelper.md#amapboundstostringarray)
- [amapConvertFrom](FastExt.AMapHelper.md#amapconvertfrom)
- [amapLngLatArrayToStringArray](FastExt.AMapHelper.md#amaplnglatarraytostringarray)
- [amapLngLatToString](FastExt.AMapHelper.md#amaplnglattostring)
- [convertDMS](FastExt.AMapHelper.md#convertdms)
- [convertStringDMSToArray](FastExt.AMapHelper.md#convertstringdmstoarray)
- [parseAMapBounds](FastExt.AMapHelper.md#parseamapbounds)
- [parseAMapLngLat](FastExt.AMapHelper.md#parseamaplnglat)
- [parseAMapLngLatArray](FastExt.AMapHelper.md#parseamaplnglatarray)
- [plainStringToAMapLngLat](FastExt.AMapHelper.md#plainstringtoamaplnglat)

## Constructors

### constructor

• **new AMapHelper**(): [`AMapHelper`](FastExt.AMapHelper.md)

#### Returns

[`AMapHelper`](FastExt.AMapHelper.md)

## Methods

### amapBoundsToStringArray

▸ **amapBoundsToStringArray**(`bounds`): `string`[]

将 AMap.Bounds 对象转成字符串数组，长度为2
下标0：southWestLngLat 西南坐标（左下坐标），例如：110.568434,32.377389
下标1：northEastLngLat 东北坐标（右上坐标），例如：110.969035,32.667611

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `bounds` | `any` | AMap.Bounds 对象 |

#### Returns

`string`[]

___

### amapConvertFrom

▸ **amapConvertFrom**(`targetLnglat`, `convertType`): `ExtPromise`

坐标转换

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `targetLnglat` | `any` | 需要转换的坐标或者坐标组 |
| `convertType` | `string` | 坐标类型 可选值有：gps、baidu |

#### Returns

`ExtPromise`

___

### amapLngLatArrayToStringArray

▸ **amapLngLatArrayToStringArray**(`lnglatArray`): `string`[]

将一组 AMap.LngLat 数组对象转成 一组字符串数组

#### Parameters

| Name | Type |
| :------ | :------ |
| `lnglatArray` | `any` |

#### Returns

`string`[]

___

### amapLngLatToString

▸ **amapLngLatToString**(`lnglat`): `string`

将 AMap.LngLat 对象转成字符串  例如：110.568434,32.377389

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `lnglat` | `any` | AMap.LngLat对象 |

#### Returns

`string`

___

### convertDMS

▸ **convertDMS**(`dms`): `number`

将度分秒转换成小数点（十进制）

#### Parameters

| Name | Type |
| :------ | :------ |
| `dms` | `any`[] |

#### Returns

`number`

___

### convertStringDMSToArray

▸ **convertStringDMSToArray**(`plainStringDMS`): `any`[]

将字符串度分秒 转换成功 数组

#### Parameters

| Name | Type |
| :------ | :------ |
| `plainStringDMS` | `string` |

#### Returns

`any`[]

___

### parseAMapBounds

▸ **parseAMapBounds**(`southWestLngLat`, `northEastLngLat`): `any`

将坐标转成 AMap.Bounds 对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `southWestLngLat` | `string` | 西南坐标（左下坐标），例如：110.568434,32.377389 |
| `northEastLngLat` | `string` | 东北坐标（右上坐标），例如：110.969035,32.667611 |

#### Returns

`any`

___

### parseAMapLngLat

▸ **parseAMapLngLat**(`lnglat`): `any`

将坐标转成 AMap.LngLat 对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `lnglat` | `string` | 例如：110.568434,32.377389 |

#### Returns

`any`

___

### parseAMapLngLatArray

▸ **parseAMapLngLatArray**(`path`): `any`[]

将一组坐标转换成 AMap.LngLat 数组对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string`[] |

#### Returns

`any`[]

___

### plainStringToAMapLngLat

▸ **plainStringToAMapLngLat**(`plainStringLongitude`, `plainStringLatitude`): `any`

科学显示的经纬度转换成AMap.LngLat 对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `plainStringLongitude` | `string` | 经度 例如：116°34′52.18″ |
| `plainStringLatitude` | `string` | 纬度 例如：32°39′16.614″ |

#### Returns

`any`
