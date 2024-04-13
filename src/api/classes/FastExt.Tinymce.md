[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Tinymce

# Class: Tinymce

[FastExt](../modules/FastExt.md).Tinymce

Tinymce操作类 https://www.tiny.cloud/docs/tinymce/6/

## Table of contents

### Constructors

- [constructor](FastExt.Tinymce.md#constructor)

### Properties

- [initializing](FastExt.Tinymce.md#initializing)
- [stackInitConfig](FastExt.Tinymce.md#stackinitconfig)
- [tinymceJsPath](FastExt.Tinymce.md#tinymcejspath)

### Methods

- [initTinymce](FastExt.Tinymce.md#inittinymce)
- [loadTinymceJs](FastExt.Tinymce.md#loadtinymcejs)

## Constructors

### constructor

• **new Tinymce**(): [`Tinymce`](FastExt.Tinymce.md)

#### Returns

[`Tinymce`](FastExt.Tinymce.md)

## Properties

### initializing

▪ `Static` **initializing**: `boolean` = `false`

是否正在初始化中

___

### stackInitConfig

▪ `Static` **stackInitConfig**: `any`[] = `[]`

初始化队列

___

### tinymceJsPath

▪ `Static` **tinymceJsPath**: `string` = `"base/tinymce/tinymce.min.js"`

tinymce.min.js文件的路径

## Methods

### initTinymce

▸ **initTinymce**(`config`, `callback`): `void`

初始化编辑器

#### Parameters

| Name | Type |
| :------ | :------ |
| `config` | `any` |
| `callback` | `any` |

#### Returns

`void`

___

### loadTinymceJs

▸ **loadTinymceJs**(`callBack`): `void`

加载tinymceJs组件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callBack` | `any` | 加载成后的回调 |

#### Returns

`void`
