[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Highlight

# Class: Highlight

[FastExt](../modules/FastExt.md).Highlight

## Table of contents

### Constructors

- [constructor](FastExt.Highlight.md#constructor)

### Properties

- [highlightJsPath](FastExt.Highlight.md#highlightjspath)
- [highlightStylePath](FastExt.Highlight.md#highlightstylepath)

### Methods

- [highlightCode](FastExt.Highlight.md#highlightcode)
- [loadHighlight](FastExt.Highlight.md#loadhighlight)

## Constructors

### constructor

• **new Highlight**(): [`Highlight`](FastExt.Highlight.md)

#### Returns

[`Highlight`](FastExt.Highlight.md)

## Properties

### highlightJsPath

▪ `Static` **highlightJsPath**: `string` = `"base/highlight/highlight.min.js"`

highlight.min.js文件的路径

___

### highlightStylePath

▪ `Static` **highlightStylePath**: `string` = `"base/highlight/idea.min.css"`

highlight.css文件的路径

## Methods

### highlightCode

▸ **highlightCode**(`code`, `lang`, `callback`): `void`

格式化高亮代码

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `code` | `string` | 代码 |
| `lang` | `string` | 代码开发语言 |
| `callback` | `any` | 回调函数function(value) |

#### Returns

`void`

___

### loadHighlight

▸ **loadHighlight**(`callBack`): `void`

加载Markdown组件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callBack` | `any` | 加载成后的回调 |

#### Returns

`void`
