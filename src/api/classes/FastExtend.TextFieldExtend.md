[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExtend](../modules/FastExtend.md) / TextFieldExtend

# Class: TextFieldExtend

[FastExtend](../modules/FastExtend.md).TextFieldExtend

Ext.form.field.Text扩展

**`Define`**

使用Ext.form.field.Text对象调用以下方法或属性

**`Example`**

```ts
input.blur()
```

## Table of contents

### Constructors

- [constructor](FastExtend.TextFieldExtend.md#constructor)

### Properties

- [comment](FastExtend.TextFieldExtend.md#comment)
- [useHistory](FastExtend.TextFieldExtend.md#usehistory)

### Methods

- [checkHistory](FastExtend.TextFieldExtend.md#checkhistory)
- [clearHistory](FastExtend.TextFieldExtend.md#clearhistory)
- [hideHistory](FastExtend.TextFieldExtend.md#hidehistory)
- [showHistory](FastExtend.TextFieldExtend.md#showhistory)

## Constructors

### constructor

• **new TextFieldExtend**(): [`TextFieldExtend`](FastExtend.TextFieldExtend.md)

#### Returns

[`TextFieldExtend`](FastExtend.TextFieldExtend.md)

## Properties

### comment

• **comment**: `string` = `""`

输入框的说明信息

___

### useHistory

• **useHistory**: `boolean` = `false`

是否开启输入历史记录的功能，当调用validate方法是会触发记录，将数据保存到历史记录中
注意：当开启历史记录功能时，需要配置组件的code值，避免系统自动生成照成不一致

## Methods

### checkHistory

▸ **checkHistory**(): `boolean`

检测输入框是否有历史记录，当useHistory为true时有效

#### Returns

`boolean`

___

### clearHistory

▸ **clearHistory**(): `any`

清空输入框的历史记录，当useHistory为true时有效

#### Returns

`any`

___

### hideHistory

▸ **hideHistory**(): `any`

隐藏输入框的历史记录菜单，当useHistory为true时有效

#### Returns

`any`

___

### showHistory

▸ **showHistory**(): `any`

显示输入框的历史记录菜单，当useHistory为true时有效

#### Returns

`any`
