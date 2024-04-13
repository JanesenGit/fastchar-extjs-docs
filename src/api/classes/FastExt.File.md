[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / File

# Class: File

[FastExt](../modules/FastExt.md).File

## Table of contents

### Constructors

- [constructor](FastExt.File.md#constructor)

### Methods

- [formatLength](FastExt.File.md#formatlength)
- [isSuffixFile](FastExt.File.md#issuffixfile)
- [officeViewer](FastExt.File.md#officeviewer)
- [showFiles](FastExt.File.md#showfiles)
- [uploadFile](FastExt.File.md#uploadfile)

## Constructors

### constructor

• **new File**(): [`File`](FastExt.File.md)

#### Returns

[`File`](FastExt.File.md)

## Methods

### formatLength

▸ **formatLength**(`length`): `string`

格式化文件的大小长度

#### Parameters

| Name | Type |
| :------ | :------ |
| `length` | `any` |

#### Returns

`string`

**`Example`**

```ts
10KB 或 10M
```

___

### isSuffixFile

▸ **isSuffixFile**(`fileName`, `...suffix`): `boolean`

判断文件名是否以后缀名，包含了fastchar文件格式的判断

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `fileName` | `string` | 文件名 |
| `...suffix` | `any`[] | 后缀名，可传多个 |

#### Returns

`boolean`

___

### officeViewer

▸ **officeViewer**(`url`, `newWindow?`): `void`

打开新窗口在线预览office办公文件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` | 文件地址 |
| `newWindow?` | `any` | 是否在新的浏览器窗口打开 |

#### Returns

`void`

___

### showFiles

▸ **showFiles**(`obj`, `callBack`, `fileModules`, `defaultFiles`, `title`, `readOnly?`, `showFileName?`, `showFileLength?`): `void`

弹出管理多个文件的窗口

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 控件对象 |
| `callBack` | `any` | 回调函数 |
| `fileModules` | `any` | 文件类型 |
| `defaultFiles` | `any` | 默认文件数据 |
| `title` | `any` | 标题 |
| `readOnly?` | `any` | 是否为只读模式 |
| `showFileName?` | `any` | 显示附件名称 |
| `showFileLength?` | `any` | 显示附件大小 |

#### Returns

`void`

**`Example`**

```ts
showFiles(this,function(val){

},[file.image(),file.excel()])
```

___

### uploadFile

▸ **uploadFile**(`obj`, `fileModules`, `multiple?`, `useEditUrl?`): `any`

弹出上传文件的对话框

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 控件对象 |
| `fileModules` | `any` | 文件类型 |
| `multiple?` | `boolean` | 是否允许多选文件 |
| `useEditUrl?` | `boolean` | 是否允许手动编写文件url |

#### Returns

`any`

Ext.Promise

**`Example`**

```ts
uploadFile(this,[file.image(),file.excel()])
```
