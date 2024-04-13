[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Menu

# Class: Menu

[FastExt](../modules/FastExt.md).Menu

Ext.menu.Menu 相关功能辅助

## Table of contents

### Constructors

- [constructor](FastExt.Menu.md#constructor)

### Methods

- [copyMenu](FastExt.Menu.md#copymenu)
- [fireMenuEvent](FastExt.Menu.md#firemenuevent)
- [isSplitLineLast](FastExt.Menu.md#issplitlinelast)
- [refreshItem](FastExt.Menu.md#refreshitem)

## Constructors

### constructor

• **new Menu**(): [`Menu`](FastExt.Menu.md)

#### Returns

[`Menu`](FastExt.Menu.md)

## Methods

### copyMenu

▸ **copyMenu**(`target`): `any`

复制菜单

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `target` | `any` | 菜单对象 |

#### Returns

`any`

___

### fireMenuEvent

▸ **fireMenuEvent**(`menu`, `event`): `void`

触发所有子菜单的自定义事件

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |
| `event` | `any` |

#### Returns

`void`

___

### isSplitLineLast

▸ **isSplitLineLast**(`menus`): `boolean`

判断菜单集合中，最后一个是不是分割线

#### Parameters

| Name | Type |
| :------ | :------ |
| `menus` | `any` |

#### Returns

`boolean`

___

### refreshItem

▸ **refreshItem**(`menu`, `item?`): `void`

刷新菜单的选项，避免出现分割线连在一起的情况

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |
| `item?` | `any` |

#### Returns

`void`
