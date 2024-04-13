[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExtend](../modules/FastExtend.md) / ButtonExtend

# Class: ButtonExtend

[FastExtend](../modules/FastExtend.md).ButtonExtend

Ext.button.Button扩展

**`Define`**

使用Ext.button.Button对象调用以下方法或属性

**`Example`**

```ts
button.contextMenu
```

## Table of contents

### Constructors

- [constructor](FastExtend.ButtonExtend.md#constructor)

### Properties

- [bindDetail](FastExtend.ButtonExtend.md#binddetail)
- [checkSelect](FastExtend.ButtonExtend.md#checkselect)
- [checkUpdate](FastExtend.ButtonExtend.md#checkupdate)
- [contextMenu](FastExtend.ButtonExtend.md#contextmenu)
- [entityAddButton](FastExtend.ButtonExtend.md#entityaddbutton)
- [entityDeleteButton](FastExtend.ButtonExtend.md#entitydeletebutton)
- [entityUpdateButton](FastExtend.ButtonExtend.md#entityupdatebutton)

## Constructors

### constructor

• **new ButtonExtend**(): [`ButtonExtend`](FastExtend.ButtonExtend.md)

#### Returns

[`ButtonExtend`](FastExtend.ButtonExtend.md)

## Properties

### bindDetail

• **bindDetail**: `boolean` = `false`

是否弹出数据详情窗体时绑定此按钮，绑定的函数支持引用外部变量名有：grid : Ext.grid.Panel  me : FastExtEntity

___

### checkSelect

• **checkSelect**: `number`

当grid选中指定行数时按钮可用

___

### checkUpdate

• **checkUpdate**: `number`

当grid修改了数据时按钮可用

___

### contextMenu

• **contextMenu**: `boolean` = `true`

如果button按钮放置在grid中的toolbar中，此属性表示是否自动将按钮添加到grid的右键菜单中，默认为：true

___

### entityAddButton

• **entityAddButton**: `boolean` = `false`

是否用于entity的数据添加按钮

___

### entityDeleteButton

• **entityDeleteButton**: `boolean` = `false`

是否用于entity的数据删除按钮

___

### entityUpdateButton

• **entityUpdateButton**: `boolean` = `false`

是否用于entity的数据修改按钮
