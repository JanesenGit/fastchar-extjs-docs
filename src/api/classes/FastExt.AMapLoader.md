[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / AMapLoader

# Class: AMapLoader

[FastExt](../modules/FastExt.md).AMapLoader

地图map对象加载器

## Table of contents

### Constructors

- [constructor](FastExt.AMapLoader.md#constructor)

### Methods

- [\_\_onLoaded](FastExt.AMapLoader.md#__onloaded)
- [getMap](FastExt.AMapLoader.md#getmap)
- [getMapByEl](FastExt.AMapLoader.md#getmapbyel)
- [getMapByElId](FastExt.AMapLoader.md#getmapbyelid)
- [getMapJsUrl](FastExt.AMapLoader.md#getmapjsurl)
- [loadMap](FastExt.AMapLoader.md#loadmap)
- [loadMapByEl](FastExt.AMapLoader.md#loadmapbyel)

## Constructors

### constructor

• **new AMapLoader**(): [`AMapLoader`](FastExt.AMapLoader.md)

#### Returns

[`AMapLoader`](FastExt.AMapLoader.md)

## Methods

### \_\_onLoaded

▸ **__onLoaded**(): `void`

#### Returns

`void`

___

### getMap

▸ **getMap**(`cmb`): `any`

获取cmb已加载渲染的map对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `cmb` | `any` |

#### Returns

`any`

___

### getMapByEl

▸ **getMapByEl**(`el`): `any`

获取cmb已加载渲染的map对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `el` | `Element` |

#### Returns

`any`

___

### getMapByElId

▸ **getMapByElId**(`elId`): `any`

获取cmb已加载渲染的map对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `elId` | `string` |

#### Returns

`any`

___

### getMapJsUrl

▸ **getMapJsUrl**(): `string`

#### Returns

`string`

___

### loadMap

▸ **loadMap**(`cmb`, `callBack?`): `void`

加载地图map对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cmb` | `any` | 组件对象 |
| `callBack?` | `any` | 地图加载成功的回调 |

#### Returns

`void`

___

### loadMapByEl

▸ **loadMapByEl**(`el`, `callBack?`): `void`

加载地图map对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `el` | `Element` | 地图渲染的目标节点 |
| `callBack?` | `any` | 地图加载成功的回调 |

#### Returns

`void`
