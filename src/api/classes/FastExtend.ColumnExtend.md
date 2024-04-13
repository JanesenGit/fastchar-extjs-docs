[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExtend](../modules/FastExtend.md) / ColumnExtend

# Class: ColumnExtend

[FastExtend](../modules/FastExtend.md).ColumnExtend

Ext.grid.column.Column的扩展

**`Define`**

使用Ext.grid.column.Column对象调用以下方法或属性

**`Example`**

```ts
column.toSearchKey()
```

## Table of contents

### Constructors

- [constructor](FastExtend.ColumnExtend.md#constructor)

### Properties

- [batchField](FastExtend.ColumnExtend.md#batchfield)
- [code](FastExtend.ColumnExtend.md#code)
- [comment](FastExtend.ColumnExtend.md#comment)
- [configText](FastExtend.ColumnExtend.md#configtext)
- [editMenu](FastExtend.ColumnExtend.md#editmenu)
- [encrypt](FastExtend.ColumnExtend.md#encrypt)
- [excelHeader](FastExtend.ColumnExtend.md#excelheader)
- [excelOutHeader](FastExtend.ColumnExtend.md#exceloutheader)
- [password](FastExtend.ColumnExtend.md#password)
- [rendererFunction](FastExtend.ColumnExtend.md#rendererfunction)
- [search](FastExtend.ColumnExtend.md#search)
- [searchExclude](FastExtend.ColumnExtend.md#searchexclude)
- [searchLink](FastExtend.ColumnExtend.md#searchlink)
- [searchMenu](FastExtend.ColumnExtend.md#searchmenu)
- [sortDirection](FastExtend.ColumnExtend.md#sortdirection)
- [where](FastExtend.ColumnExtend.md#where)

### Methods

- [clearSearch](FastExtend.ColumnExtend.md#clearsearch)
- [doSearch](FastExtend.ColumnExtend.md#dosearch)
- [searchValue](FastExtend.ColumnExtend.md#searchvalue)
- [toSearchKey](FastExtend.ColumnExtend.md#tosearchkey)

## Constructors

### constructor

• **new ColumnExtend**(): [`ColumnExtend`](FastExtend.ColumnExtend.md)

#### Returns

[`ColumnExtend`](FastExtend.ColumnExtend.md)

## Properties

### batchField

• **batchField**: ``"Ext.Form.Field"``

当前列批量编辑的编辑组件

___

### code

• **code**: `string`

组件的唯一标识

___

### comment

• **comment**: `string` = `""`

列的说明信息

___

### configText

• **configText**: `string`

列首次配置的标题

___

### editMenu

• **editMenu**: ``"Ext.menu.Menu"``

当前列弹出的编辑菜单

___

### encrypt

• **encrypt**: `boolean`

列数据是否是加密数据

___

### excelHeader

• **excelHeader**: `boolean` = `true`

是否允许生成模板中包含当前列

___

### excelOutHeader

• **excelOutHeader**: `boolean` = `true`

是否允许导出列

___

### password

• **password**: `boolean`

列是否是密码类型

___

### rendererFunction

• **rendererFunction**: `string`

列的渲染函数名，当渲染函数需要参数的时候，建议使用字符串配置，便于系统记忆和恢复！

___

### search

• **search**: `boolean` = `true`

是否允许搜索，默认true

___

### searchExclude

• **searchExclude**: `string`

配置搜索忽略的字符串

___

### searchLink

• **searchLink**: []

列配置的搜索链信息

___

### searchMenu

• **searchMenu**: ``"Ext.menu.Menu"``

当前列弹出的搜索菜单

___

### sortDirection

• **sortDirection**: `string`

当前列的排序类型 asc或desc

___

### where

• **where**: `any`

列绑定的搜索条件属性名和条件值

## Methods

### clearSearch

▸ **clearSearch**(): `any`

清空列的搜索

#### Returns

`any`

**`See`**

[FastExt.Grid.configColumnProperty](FastExt.Grid.md#configcolumnproperty)

___

### doSearch

▸ **doSearch**(`requestServer`): `any`

触发列的搜索

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `requestServer` | `any` | 是否提交到服务器请求 |

#### Returns

`any`

**`See`**

[FastExt.Grid.configColumnProperty](FastExt.Grid.md#configcolumnproperty)

___

### searchValue

▸ **searchValue**(`value`): `void`

搜索指定值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `value` | `any` | 匹配的值 |

#### Returns

`void`

**`See`**

[FastExt.Grid.configColumnProperty](FastExt.Grid.md#configcolumnproperty)

___

### toSearchKey

▸ **toSearchKey**(): `string`

获取搜索列数据的条件属性名

#### Returns

`string`

**`See`**

[FastExt.Grid.configColumnProperty](FastExt.Grid.md#configcolumnproperty)
