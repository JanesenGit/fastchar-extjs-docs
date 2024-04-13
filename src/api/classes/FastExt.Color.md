[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Color

# Class: Color

[FastExt](../modules/FastExt.md).Color

颜色处理的功能

## Table of contents

### Constructors

- [constructor](FastExt.Color.md#constructor)

### Properties

- [pickrJsPath](FastExt.Color.md#pickrjspath)
- [pickrStylePath](FastExt.Color.md#pickrstylepath)

### Methods

- [showColorPicker](FastExt.Color.md#showcolorpicker)
- [toColor](FastExt.Color.md#tocolor)

## Constructors

### constructor

• **new Color**(): [`Color`](FastExt.Color.md)

#### Returns

[`Color`](FastExt.Color.md)

## Properties

### pickrJsPath

▪ `Static` **pickrJsPath**: `string` = `"base/colorpicker/pickr.es5.min.js"`

pickr.es5.min.js文件的路径 https://github.com/Simonwep/pickr

___

### pickrStylePath

▪ `Static` **pickrStylePath**: `string` = `"base/colorpicker/monolith.min.css"`

pickr主题文件的路径 https://github.com/Simonwep/pickr

## Methods

### showColorPicker

▸ **showColorPicker**(`obj`, `defaultValue`, `onColorChange`): `any`

弹出颜色选择控件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 需要弹出的目标控件 |
| `defaultValue` | `any` | 默认颜色 |
| `onColorChange` | `any` | 颜色变化的监听 |

#### Returns

`any`

Ext.Promise

___

### toColor

▸ **toColor**(`obj`, `defaultValue?`): `string`

转换颜色格式值，符合：#ffffff 格式

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 待转换的颜色 |
| `defaultValue?` | `any` | 默认颜色 |

#### Returns

`string`
