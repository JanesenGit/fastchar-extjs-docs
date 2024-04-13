[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / MonacoEditor

# Class: MonacoEditor

[FastExt](../modules/FastExt.md).MonacoEditor

MonacoEditor 操作类 https://microsoft.github.io/monaco-editor/

## Table of contents

### Constructors

- [constructor](FastExt.MonacoEditor.md#constructor)

### Methods

- [showDiffEditor](FastExt.MonacoEditor.md#showdiffeditor)
- [showEditor](FastExt.MonacoEditor.md#showeditor)

## Constructors

### constructor

• **new MonacoEditor**(): [`MonacoEditor`](FastExt.MonacoEditor.md)

#### Returns

[`MonacoEditor`](FastExt.MonacoEditor.md)

## Methods

### showDiffEditor

▸ **showDiffEditor**(`obj`, `content1`, `content2`, `language`, `subtitle?`): `any`

显示内容对比编辑器

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` |  |
| `content1` | `string` | 编辑的内容1 |
| `content2` | `string` | 编辑的内容2 |
| `language` | [`MonacoEditorLanguage`](../enums/FastExt.MonacoEditorLanguage.md) | 内容的开发语言 |
| `subtitle?` | `string` | 窗口的子标题 |

#### Returns

`any`

___

### showEditor

▸ **showEditor**(`obj`, `content`, `language`): `any`

显示编辑器

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` |  |
| `content` | `string` | 编辑内容 |
| `language` | [`MonacoEditorLanguage`](../enums/FastExt.MonacoEditorLanguage.md) | 内容的开发语言 |

#### Returns

`any`
