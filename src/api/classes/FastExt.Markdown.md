[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Markdown

# Class: Markdown

[FastExt](../modules/FastExt.md).Markdown

markdown文件解析类

## Table of contents

### Constructors

- [constructor](FastExt.Markdown.md#constructor)

### Properties

- [markdownJsPath](FastExt.Markdown.md#markdownjspath)
- [markdownPluginsPath](FastExt.Markdown.md#markdownpluginspath)
- [markdownStylePath](FastExt.Markdown.md#markdownstylepath)

### Methods

- [loadMarkdown](FastExt.Markdown.md#loadmarkdown)
- [parseMarkdown](FastExt.Markdown.md#parsemarkdown)
- [showChangelog](FastExt.Markdown.md#showchangelog)
- [showMarkdownFile](FastExt.Markdown.md#showmarkdownfile)

## Constructors

### constructor

• **new Markdown**(): [`Markdown`](FastExt.Markdown.md)

#### Returns

[`Markdown`](FastExt.Markdown.md)

## Properties

### markdownJsPath

▪ `Static` **markdownJsPath**: `string` = `"base/markdown-it/markdown-it.min.js"`

markdown-it.min.js文件的路径

___

### markdownPluginsPath

▪ `Static` **markdownPluginsPath**: `string`[]

markdown-it.min.js文件的路径

___

### markdownStylePath

▪ `Static` **markdownStylePath**: `string` = `"base/markdown-it/markdown-style.css"`

markdown-light.css文件的路径

## Methods

### loadMarkdown

▸ **loadMarkdown**(`callBack`): `void`

加载Markdown组件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callBack` | `any` | 加载成后的回调 |

#### Returns

`void`

___

### parseMarkdown

▸ **parseMarkdown**(`content`, `callback`): `void`

转换markdown代码

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `content` | `string` | markdown代码 |
| `callback` | `any` | 回调函数function(htmlValue) |

#### Returns

`void`

___

### showChangelog

▸ **showChangelog**(`obj`): `void`

弹框显示系统更新日志的文件

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`void`

___

### showMarkdownFile

▸ **showMarkdownFile**(`obj`, `title`, `markdownFileUrl`, `windowConfig?`): `void`

弹框显示markdown文件

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `title` | `string` |
| `markdownFileUrl` | `string` |
| `windowConfig?` | `any` |

#### Returns

`void`
