[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExtend](../modules/FastExtend.md) / FieldExtend

# Class: FieldExtend

[FastExtend](../modules/FastExtend.md).FieldExtend

Ext.form.field.Base扩展

**`Define`**

使用Ext.form.field.Base对象调用以下方法或属性

**`Example`**

```ts
input.blur()
```

## Table of contents

### Constructors

- [constructor](FastExtend.FieldExtend.md#constructor)

### Properties

- [extraParams](FastExtend.FieldExtend.md#extraparams)
- [fromHeadSearch](FastExtend.FieldExtend.md#fromheadsearch)
- [multiSplit](FastExtend.FieldExtend.md#multisplit)

### Methods

- [addTriggers](FastExtend.FieldExtend.md#addtriggers)
- [blur](FastExtend.FieldExtend.md#blur)
- [\_\_onLoaded](FastExtend.FieldExtend.md#__onloaded)

## Constructors

### constructor

• **new FieldExtend**(): [`FieldExtend`](FastExtend.FieldExtend.md)

#### Returns

[`FieldExtend`](FastExtend.FieldExtend.md)

## Properties

### extraParams

• **extraParams**: `any` = `{}`

扩展form表单参数

___

### fromHeadSearch

• **fromHeadSearch**: `boolean` = `false`

是否来自Grid的头部列搜索

___

### multiSplit

• **multiSplit**: `string` = `null`

将字段值转成数字格式提交的分隔符，例如值为：1，2，3 那么分隔符为：，则转成数组提交到后台

## Methods

### addTriggers

▸ **addTriggers**(`triggers`): `any`

添加组件的triggers

#### Parameters

| Name | Type |
| :------ | :------ |
| `triggers` | `any` |

#### Returns

`any`

___

### blur

▸ **blur**(): `any`

失去焦点

#### Returns

`any`

**`Example`**

```ts
Ext.form.field对象，例如： textfield.blur()
```

**`See`**

[FastExtend.FieldExtend.constructor](FastExtend.FieldExtend.md#constructor)

___

### \_\_onLoaded

▸ **__onLoaded**(): `void`

#### Returns

`void`
