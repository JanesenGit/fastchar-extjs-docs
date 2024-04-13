[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Cache

# Class: Cache

[FastExt](../modules/FastExt.md).Cache

数据缓存相关

## Table of contents

### Constructors

- [constructor](FastExt.Cache.md#constructor)

### Properties

- [memory](FastExt.Cache.md#memory)

### Methods

- [clearEnumCache](FastExt.Cache.md#clearenumcache)
- [clearEnumCacheBySearch](FastExt.Cache.md#clearenumcachebysearch)
- [existEnumCache](FastExt.Cache.md#existenumcache)
- [getCache](FastExt.Cache.md#getcache)
- [getEnumAllCache](FastExt.Cache.md#getenumallcache)
- [getEnumCache](FastExt.Cache.md#getenumcache)
- [removeCache](FastExt.Cache.md#removecache)
- [setCache](FastExt.Cache.md#setcache)
- [setEnumCache](FastExt.Cache.md#setenumcache)

## Constructors

### constructor

• **new Cache**(): [`Cache`](FastExt.Cache.md)

#### Returns

[`Cache`](FastExt.Cache.md)

## Properties

### memory

▪ `Static` **memory**: `object` = `{}`

内存缓存配置对象

## Methods

### clearEnumCache

▸ **clearEnumCache**(`enumName`): `void`

清空枚举的缓存

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `enumName` | `string` | 枚举名称 |

#### Returns

`void`

___

### clearEnumCacheBySearch

▸ **clearEnumCacheBySearch**(`enumName`): `void`

清空枚举的缓存

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `enumName` | `string` | 枚举名称 |

#### Returns

`void`

___

### existEnumCache

▸ **existEnumCache**(`enumName`, `cacheKey`): `boolean`

判断是否存在枚举缓存

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `enumName` | `string` | 枚举名称 |
| `cacheKey` | `string` | 缓存的key |

#### Returns

`boolean`

___

### getCache

▸ **getCache**(`key`): `any`

获取保存在本地浏览器的缓存

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | 缓存的key |

#### Returns

`any`

___

### getEnumAllCache

▸ **getEnumAllCache**(`enumName`): `any`

获取枚举的所有缓存

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `enumName` | `string` | 枚举名称 |

#### Returns

`any`

___

### getEnumCache

▸ **getEnumCache**(`enumName`, `cacheKey`): `any`

获取枚举的缓存

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `enumName` | `string` | 枚举名称 |
| `cacheKey` | `string` | 缓存的key |

#### Returns

`any`

___

### removeCache

▸ **removeCache**(`key`): `any`

删除保存在本地浏览器的缓存

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | 缓存的key |

#### Returns

`any`

___

### setCache

▸ **setCache**(`key`, `data`): `void`

设置缓存，保存在本地浏览器,localStorage

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | 缓存的key |
| `data` | `any` | 缓存的数据 |

#### Returns

`void`

___

### setEnumCache

▸ **setEnumCache**(`enumName`, `cacheKey`, `data`): `void`

设置枚举缓存

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `enumName` | `string` | 枚举名称 |
| `cacheKey` | `string` | 缓存的key |
| `data` | `any` | 缓存的数据 |

#### Returns

`void`
