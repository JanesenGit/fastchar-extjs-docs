[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / AMapDialog

# Class: AMapDialog

[FastExt](../modules/FastExt.md).AMapDialog

地图对话框操作类

## Table of contents

### Constructors

- [constructor](FastExt.AMapDialog.md#constructor)

### Methods

- [buildMapPanel](FastExt.AMapDialog.md#buildmappanel)
- [plainShow](FastExt.AMapDialog.md#plainshow)
- [select](FastExt.AMapDialog.md#select)
- [show](FastExt.AMapDialog.md#show)

## Constructors

### constructor

• **new AMapDialog**(): [`AMapDialog`](FastExt.AMapDialog.md)

#### Returns

[`AMapDialog`](FastExt.AMapDialog.md)

## Methods

### buildMapPanel

▸ **buildMapPanel**(`params`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `params` | [`AMapMapParams`](FastExt.AMapMapParams.md) |

#### Returns

`any`

___

### plainShow

▸ **plainShow**(`obj`, `lnglat`, `title`, `address`): `void`

在地图上显示指定坐标功能

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` |  |
| `lnglat` | `any` | 经纬度 |
| `title` | `any` | 位置标题 |
| `address` | `any` | 位置信息 |

#### Returns

`void`

___

### select

▸ **select**(`obj`, `params`): `ExtPromise`

在地图上实现选择功能，可以是选择坐标、选择矩形区域、选择多边形区域

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 动画对象 |
| `params` | [`AMapMapParams`](FastExt.AMapMapParams.md) | 参数 [AMapMapParams](FastExt.AMapMapParams.md) |

#### Returns

`ExtPromise`

___

### show

▸ **show**(`obj`, `params`): `void`

在地图上显示功能，可以是选择坐标、选择矩形区域、选择多边形区域

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `params` | [`AMapMapParams`](FastExt.AMapMapParams.md) |

#### Returns

`void`
