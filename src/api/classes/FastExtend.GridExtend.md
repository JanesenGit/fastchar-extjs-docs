[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExtend](../modules/FastExtend.md) / GridExtend

# Class: GridExtend

[FastExtend](../modules/FastExtend.md).GridExtend

gridpanel或treepanel相关扩展

**`Define`**

使用Ext.grid.Panel或Ext.tree.Panel对象调用以下所有方法或属性

**`Example`**

```ts
grid.entityList
```

## Table of contents

### Constructors

- [constructor](FastExtend.GridExtend.md#constructor)

### Properties

- [columnMenu](FastExtend.GridExtend.md#columnmenu)
- [defaultToolBar](FastExtend.GridExtend.md#defaulttoolbar)
- [defaultToolBarLink](FastExtend.GridExtend.md#defaulttoolbarlink)
- [defaultToolBarMore](FastExtend.GridExtend.md#defaulttoolbarmore)
- [entityList](FastExtend.GridExtend.md#entitylist)
- [firstLoadedData](FastExtend.GridExtend.md#firstloadeddata)
- [help](FastExtend.GridExtend.md#help)
- [helpTitle](FastExtend.GridExtend.md#helptitle)
- [importExcelItems](FastExtend.GridExtend.md#importexcelitems)
- [menuPanelList](FastExtend.GridExtend.md#menupanellist)
- [selectHistoryConfig](FastExtend.GridExtend.md#selecthistoryconfig)
- [showUpdateButton](FastExtend.GridExtend.md#showupdatebutton)

## Constructors

### constructor

• **new GridExtend**(): [`GridExtend`](FastExtend.GridExtend.md)

#### Returns

[`GridExtend`](FastExtend.GridExtend.md)

## Properties

### columnMenu

• **columnMenu**: `any`

是否启用Grid列的右键菜单，设置true或false或FastExt.GridColumnMenu对象

**`See`**

[FastExt.GridColumnMenu](FastExt.GridColumnMenu.md)

___

### defaultToolBar

• **defaultToolBar**: `boolean` = `true`

是否配置默认的toolbar按钮

___

### defaultToolBarLink

• **defaultToolBarLink**: `boolean` = `true`

当defaultToolBar为true时，是否配置默认的【相关查询】按钮

___

### defaultToolBarMore

• **defaultToolBarMore**: `boolean` = `true`

当defaultToolBar为true时，是否配置默认的【更多操作】按钮

___

### entityList

• **entityList**: `boolean`

标识是否为FastEntity列表
<br/>
如果配置属性值为true，则grid会自动配置fastchar-extjs提供的其他功能或属性！

___

### firstLoadedData

• `Readonly` **firstLoadedData**: `boolean` = `false`

是否已首次加载数据

___

### help

• **help**: `string`

当前grid绑定的相关帮助文档地址

___

### helpTitle

• **helpTitle**: `string`

帮助文档按钮弹出框的标题。

___

### importExcelItems

• **importExcelItems**: `any`

弹出导入窗口时需要配置到formpanel中的组件

___

### menuPanelList

• **menuPanelList**: `boolean` = `false`

标识是否是菜单打开的数据列表，设置true时，保存Grid列信息时会携带EntityCode参数，否则不携带！

___

### selectHistoryConfig

• **selectHistoryConfig**: `Object`

数据选择器记忆

#### Type declaration

| Name | Type |
| :------ | :------ |
| `count` | ``0`` |
| `state` | ``0`` |

___

### showUpdateButton

• **showUpdateButton**: `boolean` = `true`

是否显示修改数据的按钮
