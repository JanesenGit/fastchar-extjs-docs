[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Windows

# Class: Windows

[FastExt](../modules/FastExt.md).Windows

javascript 原生window操作功能相关

## Table of contents

### Constructors

- [constructor](FastExt.Windows.md#constructor)

### Properties

- [\_baseUrl](FastExt.Windows.md#_baseurl)
- [\_fullscreen](FastExt.Windows.md#_fullscreen)

### Methods

- [getAllExt](FastExt.Windows.md#getallext)
- [getBaseUrl](FastExt.Windows.md#getbaseurl)
- [getExt](FastExt.Windows.md#getext)
- [getMenuIdFromLocation](FastExt.Windows.md#getmenuidfromlocation)
- [inFullscreen](FastExt.Windows.md#infullscreen)
- [isFullscreen](FastExt.Windows.md#isfullscreen)
- [openUrl](FastExt.Windows.md#openurl)
- [outFullscreen](FastExt.Windows.md#outfullscreen)
- [pushLocationHistory](FastExt.Windows.md#pushlocationhistory)
- [reload](FastExt.Windows.md#reload)
- [removeLoading](FastExt.Windows.md#removeloading)
- [toggleFullscreen](FastExt.Windows.md#togglefullscreen)

## Constructors

### constructor

• **new Windows**(): [`Windows`](FastExt.Windows.md)

#### Returns

[`Windows`](FastExt.Windows.md)

## Properties

### \_baseUrl

▪ `Static` `Private` **\_baseUrl**: `string`

http://localhost:8080/

___

### \_fullscreen

▪ `Static` `Private` **\_fullscreen**: `boolean` = `false`

## Methods

### getAllExt

▸ **getAllExt**(): `any`

获取所有ext的配置

#### Returns

`any`

___

### getBaseUrl

▸ **getBaseUrl**(): `string`

#### Returns

`string`

___

### getExt

▸ **getExt**(`key`): `any`

获取配置在fast-head.html中 meta scheme="ext" 对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`any`

___

### getMenuIdFromLocation

▸ **getMenuIdFromLocation**(): `string`

解析地址栏中携带的菜单Id

#### Returns

`string`

___

### inFullscreen

▸ **inFullscreen**(): `void`

控制浏览器界面进入全屏

#### Returns

`void`

___

### isFullscreen

▸ **isFullscreen**(): `boolean`

#### Returns

`boolean`

___

### openUrl

▸ **openUrl**(`url`, `target?`): `void`

动态打开URL地址

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` |  |
| `target?` | [`Target`](../enums/FastEnum.Target.md) | 打开方式 |

#### Returns

`void`

**`See`**

[FastEnum.Target](../enums/FastEnum.Target.md)

___

### outFullscreen

▸ **outFullscreen**(): `void`

退出全屏

#### Returns

`void`

___

### pushLocationHistory

▸ **pushLocationHistory**(`menu`): `void`

将菜单配置的历史记录中

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`void`

___

### reload

▸ **reload**(): `void`

#### Returns

`void`

___

### removeLoading

▸ **removeLoading**(): `void`

移除全局加载的等待界面

#### Returns

`void`

___

### toggleFullscreen

▸ **toggleFullscreen**(): `void`

#### Returns

`void`
