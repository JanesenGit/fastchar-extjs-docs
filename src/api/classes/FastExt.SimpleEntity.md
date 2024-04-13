[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / SimpleEntity

# Class: SimpleEntity

[FastExt](../modules/FastExt.md).SimpleEntity

默认常规Entity实体辅助类

## Table of contents

### Constructors

- [constructor](FastExt.SimpleEntity.md#constructor)

### Properties

- [\_entity](FastExt.SimpleEntity.md#_entity)
- [\_shortTitle](FastExt.SimpleEntity.md#_shorttitle)

### Methods

- [getGridConfig](FastExt.SimpleEntity.md#getgridconfig)
- [getRecords](FastExt.SimpleEntity.md#getrecords)
- [showAdd](FastExt.SimpleEntity.md#showadd)
- [showDetails](FastExt.SimpleEntity.md#showdetails)
- [showSelect](FastExt.SimpleEntity.md#showselect)
- [showWinList](FastExt.SimpleEntity.md#showwinlist)

## Constructors

### constructor

• **new SimpleEntity**(`entity`): [`SimpleEntity`](FastExt.SimpleEntity.md)

默认常规Entity实体辅助类

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体对象 |

#### Returns

[`SimpleEntity`](FastExt.SimpleEntity.md)

## Properties

### \_entity

• `Private` `Readonly` **\_entity**: `any`

___

### \_shortTitle

• `Private` `Readonly` **\_shortTitle**: `string`

## Methods

### getGridConfig

▸ **getGridConfig**(`dataStore`, `gridColumns`, `gridButtons`, `config`): `any`

获取Entity显示列表的Grid常规默认配置信息

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `dataStore` | `any` | 数据源 |
| `gridColumns` | [] | 列数组 |
| `gridButtons` | [] | 按钮数组 |
| `config` | `any` | getList方法中的config参数 |

#### Returns

`any`

grid配置对象信息

___

### getRecords

▸ **getRecords**(`where`): `any`

获取数据Record对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `where` | `any` | getList方法中的where配置 |

#### Returns

`any`

___

### showAdd

▸ **showAdd**(`obj`, `addItems`): `ExtPromise`

弹出添加窗口

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 按钮对象 |
| `addItems` | [] | 添加的字段配置对象数组 |

#### Returns

`ExtPromise`

___

### showDetails

▸ **showDetails**(`obj`, `where`): `void`

弹窗显示数据详情

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 按钮对象 |
| `where` | `any` | getList方法中的where配置 |

#### Returns

`void`

___

### showSelect

▸ **showSelect**(`obj`, `title`, `where`, `multi`, `config`, `container`): `any`

弹窗选择数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 按钮对象 |
| `title` | `string` | 弹窗标题 |
| `where` | `any` | getList方法中的where配置 |
| `multi` | `boolean` | 是否允许多选 |
| `config` | `any` | getList方法中的config参数 |
| `container` | `any` | 配置弹窗的父级容器 |

#### Returns

`any`

___

### showWinList

▸ **showWinList**(`obj`, `title`, `where`, `modal`, `config`): `void`

弹窗显示数据列表

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 按钮对象 |
| `title` | `string` | 弹窗标题 |
| `where` | `any` | getList方法中的where配置 |
| `modal` | `boolean` | 是否模式窗口 |
| `config` | `any` | getList方法中的config参数 |

#### Returns

`void`
