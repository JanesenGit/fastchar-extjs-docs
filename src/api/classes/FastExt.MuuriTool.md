[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / MuuriTool

# Class: MuuriTool

[FastExt](../modules/FastExt.md).MuuriTool

muuri 相关操作类  https://muuri.dev/

## Table of contents

### Constructors

- [constructor](FastExt.MuuriTool.md#constructor)

### Properties

- [muuriJsPath](FastExt.MuuriTool.md#muurijspath)
- [webAnimasJsPath](FastExt.MuuriTool.md#webanimasjspath)

### Methods

- [bindToContainer](FastExt.MuuriTool.md#bindtocontainer)
- [getMuuriGrid](FastExt.MuuriTool.md#getmuurigrid)
- [justBindToContainer](FastExt.MuuriTool.md#justbindtocontainer)
- [releaseMuuriGrid](FastExt.MuuriTool.md#releasemuurigrid)

## Constructors

### constructor

• **new MuuriTool**(): [`MuuriTool`](FastExt.MuuriTool.md)

#### Returns

[`MuuriTool`](FastExt.MuuriTool.md)

## Properties

### muuriJsPath

▪ `Static` **muuriJsPath**: `string` = `"base/muuri/muuri.min.js"`

muuri.min.js文件的路径

___

### webAnimasJsPath

▪ `Static` **webAnimasJsPath**: `string` = `"base/muuri/web-animations.min.js"`

web-animations.min.js文件的路径

## Methods

### bindToContainer

▸ **bindToContainer**(`container`, `muuriConfig`, `callback`): `void`

绑定到指定的容器布局中，建议该容器布局为：absolute

#### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `any` |
| `muuriConfig` | `any` |
| `callback` | `any` |

#### Returns

`void`

___

### getMuuriGrid

▸ **getMuuriGrid**(`container`): `any`

获取container绑定的muuri的grid对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `any` |

#### Returns

`any`

___

### justBindToContainer

▸ **justBindToContainer**(`container`, `muuriConfig`, `callback`): `void`

绑定container，如果已绑定则移除释放并重新绑定

#### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `any` |
| `muuriConfig` | `any` |
| `callback` | `any` |

#### Returns

`void`

___

### releaseMuuriGrid

▸ **releaseMuuriGrid**(`container`): `void`

释放container绑定的muuriGrid

#### Parameters

| Name | Type |
| :------ | :------ |
| `container` | `any` |

#### Returns

`void`
