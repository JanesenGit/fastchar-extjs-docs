[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Entity

# Class: Entity

[FastExt](../modules/FastExt.md).Entity

实体类的相关方法

## Table of contents

### Constructors

- [constructor](FastExt.Entity.md#constructor)

### Methods

- [getColumnRender](FastExt.Entity.md#getcolumnrender)
- [getEditorField](FastExt.Entity.md#geteditorfield)
- [getEditorFieldByColumn](FastExt.Entity.md#geteditorfieldbycolumn)
- [getEditorFieldObject](FastExt.Entity.md#geteditorfieldobject)
- [getEditorFieldObjectByColumn](FastExt.Entity.md#geteditorfieldobjectbycolumn)
- [getEntity](FastExt.Entity.md#getentity)
- [getRealAttr](FastExt.Entity.md#getrealattr)
- [initEntity](FastExt.Entity.md#initentity)
- [isFulltextColumn](FastExt.Entity.md#isfulltextcolumn)
- [wrapConfig](FastExt.Entity.md#wrapconfig)
- [wrapConfigs](FastExt.Entity.md#wrapconfigs)

## Constructors

### constructor

• **new Entity**(): [`Entity`](FastExt.Entity.md)

#### Returns

[`Entity`](FastExt.Entity.md)

## Methods

### getColumnRender

▸ **getColumnRender**(`entity`, `attrName`): `any`

获取实体类对象属性的渲染器

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体对象 |
| `attrName` | `string` | 属性名 |

#### Returns

`any`

___

### getEditorField

▸ **getEditorField**(`entity`, `attrName`, `column?`): `any`

获取实体类对象属性的编辑器

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体对象 |
| `attrName` | `string` | 属性名 |
| `column?` | `any` | 列对象，兼容老版本 |

#### Returns

`any`

___

### getEditorFieldByColumn

▸ **getEditorFieldByColumn**(`entity`, `column`): `any`

获取实体类Grid列的的编辑器

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体对象 |
| `column` | `any` | grid列 |

#### Returns

`any`

___

### getEditorFieldObject

▸ **getEditorFieldObject**(`entity`, `attrName`, `column?`): `any`

获取实体类对象属性的编辑器，将返回Ext.create创建的对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体对象 |
| `attrName` | `string` | 属性名 |
| `column?` | `any` | Grid里的列对象 |

#### Returns

`any`

___

### getEditorFieldObjectByColumn

▸ **getEditorFieldObjectByColumn**(`entity`, `column`): `any`

获取实体类Grid列的的编辑器,将返回Ext.create创建的对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体对象 |
| `column` | `any` | grid列 |

#### Returns

`any`

___

### getEntity

▸ **getEntity**(`entityCode`): `any`

根据entityCode获取实体对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityCode` | `string` |

#### Returns

`any`

___

### getRealAttr

▸ **getRealAttr**(`target`): `any`

获取column或field实际存入数据库的属性名

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |

#### Returns

`any`

___

### initEntity

▸ **initEntity**(`entity`, `shortTitle`): `void`

初始化Entity对象默认配置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体对象 |
| `shortTitle` | `string` | 实体简要标题【用于部分弹窗标题的构建】例如：用户、部门、商品 |

#### Returns

`void`

___

### isFulltextColumn

▸ **isFulltextColumn**(`entityCode`, `columnName`): `boolean`

判断列是否开启了全文检索的功能

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityCode` | `string` |
| `columnName` | `string` |

#### Returns

`boolean`

___

### wrapConfig

▸ **wrapConfig**(`entity`, `config`): `any`

合并配置，可用于Grid的columns，FormPanel的items

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体对象，将调用实体对象里的 getEditorField 和 getColumnRender 方法获取编辑组件或渲染函数 |
| `config` | `any` | 配置对象 |

#### Returns

`any`

___

### wrapConfigs

▸ **wrapConfigs**(`entity`, `...sourceConfigs`): `any`

合并配置，可用于Grid的columns，FormPanel的items

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体对象，将调用实体对象里的 getEditorField 和 getColumnRender 方法获取编辑组件或渲染函数 |
| `...sourceConfigs` | `any`[] | 配置对象，可变参数 |

#### Returns

`any`
