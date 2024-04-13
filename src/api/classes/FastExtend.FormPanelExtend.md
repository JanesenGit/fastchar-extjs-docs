[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExtend](../modules/FastExtend.md) / FormPanelExtend

# Class: FormPanelExtend

[FastExtend](../modules/FastExtend.md).FormPanelExtend

Ext.form.Panel扩展

**`Define`**

使用Ext.form.FormPanel对象调用以下方法或属性

**`Example`**

```ts
formPanel.setFieldValue('loginName','admin')
```

## Table of contents

### Constructors

- [constructor](FastExtend.FormPanelExtend.md#constructor)

### Properties

- [extraParams](FastExtend.FormPanelExtend.md#extraparams)

### Methods

- [deleteCache](FastExtend.FormPanelExtend.md#deletecache)
- [getField](FastExtend.FormPanelExtend.md#getfield)
- [getFieldValue](FastExtend.FormPanelExtend.md#getfieldvalue)
- [restoreCache](FastExtend.FormPanelExtend.md#restorecache)
- [saveCache](FastExtend.FormPanelExtend.md#savecache)
- [setFieldValue](FastExtend.FormPanelExtend.md#setfieldvalue)
- [submitForm](FastExtend.FormPanelExtend.md#submitform)
- [\_\_onLoaded](FastExtend.FormPanelExtend.md#__onloaded)

## Constructors

### constructor

• **new FormPanelExtend**(): [`FormPanelExtend`](FastExtend.FormPanelExtend.md)

#### Returns

[`FormPanelExtend`](FastExtend.FormPanelExtend.md)

## Properties

### extraParams

• **extraParams**: `any` = `{}`

扩展参数

## Methods

### deleteCache

▸ **deleteCache**(`key`): `any`

删除form暂存的数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `any` |

#### Returns

`any`

**`See`**

FastExtend.FormPanel.constructor

___

### getField

▸ **getField**(`fieldName`): `any`

获取field对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `fieldName` | `any` |

#### Returns

`any`

**`See`**

FastExtend.FormPanel.constructor

___

### getFieldValue

▸ **getFieldValue**(`fieldName`): `any`

获取字段值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `fieldName` | `any` | 字段属性名 |

#### Returns

`any`

**`See`**

FastExtend.FormPanel.constructor

___

### restoreCache

▸ **restoreCache**(`key`): `any`

还原form暂存的数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `any` | 暂存的key |

#### Returns

`any`

**`See`**

FastExtend.FormPanel.constructor

___

### saveCache

▸ **saveCache**(`key`): `any`

暂存form表单的数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `any` | 暂存的key |

#### Returns

`any`

**`See`**

FastExtend.FormPanel.constructor

___

### setFieldValue

▸ **setFieldValue**(`fieldName`, `value`): `any`

设置字段值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `fieldName` | `any` | 字段属性名 |
| `value` | `any` | 字段值 |

#### Returns

`any`

**`See`**

FastExtend.FormPanel.constructor

___

### submitForm

▸ **submitForm**(`entity`, `extraParams`, `waitMsg`, `successAlert`, `failAlert`): `any`

快速提交表单

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体的类对象 |
| `extraParams` | `any` | 扩展参数 |
| `waitMsg` | `any` | 提交时等待的消息 |
| `successAlert` | `any` | 弹出成功框 默认：true |
| `failAlert` | `any` | 弹出失败消息 默认：true |

#### Returns

`any`

**`See`**

FastExtend.FormPanel.constructor

___

### \_\_onLoaded

▸ **__onLoaded**(): `void`

#### Returns

`void`
