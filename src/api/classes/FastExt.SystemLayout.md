[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / SystemLayout

# Class: SystemLayout

[FastExt](../modules/FastExt.md).SystemLayout

基础布局功能

## Table of contents

### Constructors

- [constructor](FastExt.SystemLayout.md#constructor)

### Properties

- [\_currClickTarget](FastExt.SystemLayout.md#_currclicktarget)
- [\_mouseClickX](FastExt.SystemLayout.md#_mouseclickx)
- [\_mouseClickY](FastExt.SystemLayout.md#_mouseclicky)
- [\_systemBodyContainer](FastExt.SystemLayout.md#_systembodycontainer)

### Methods

- [changeMenuTheme](FastExt.SystemLayout.md#changemenutheme)
- [clearAllMenuTheme](FastExt.SystemLayout.md#clearallmenutheme)
- [closeAllTab](FastExt.SystemLayout.md#closealltab)
- [getBodyContainer](FastExt.SystemLayout.md#getbodycontainer)
- [getCurrClickTarget](FastExt.SystemLayout.md#getcurrclicktarget)
- [getMouseClickXY](FastExt.SystemLayout.md#getmouseclickxy)
- [selectMenu](FastExt.SystemLayout.md#selectmenu)
- [setCurrClickTarget](FastExt.SystemLayout.md#setcurrclicktarget)
- [setMouseClickXY](FastExt.SystemLayout.md#setmouseclickxy)
- [showByCmp](FastExt.SystemLayout.md#showbycmp)
- [showByLevel](FastExt.SystemLayout.md#showbylevel)
- [showByMenu](FastExt.SystemLayout.md#showbymenu)
- [showByMenuId](FastExt.SystemLayout.md#showbymenuid)
- [showByMethod](FastExt.SystemLayout.md#showbymethod)
- [showGlobalSearch](FastExt.SystemLayout.md#showglobalsearch)
- [showMenuColumns](FastExt.SystemLayout.md#showmenucolumns)

## Constructors

### constructor

• **new SystemLayout**(): [`SystemLayout`](FastExt.SystemLayout.md)

#### Returns

[`SystemLayout`](FastExt.SystemLayout.md)

## Properties

### \_currClickTarget

▪ `Static` `Private` **\_currClickTarget**: `any` = `null`

当前触发点击事件的目标组件，一般用于弹窗动画

___

### \_mouseClickX

▪ `Static` `Private` **\_mouseClickX**: `number`

___

### \_mouseClickY

▪ `Static` `Private` **\_mouseClickY**: `number`

___

### \_systemBodyContainer

▪ `Static` `Private` **\_systemBodyContainer**: `any`

系统显示的容器

## Methods

### changeMenuTheme

▸ **changeMenuTheme**(`menuId`, `callBack?`): `void`

切换Tab的主题

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `menuId` | `any` | 菜单ID |
| `callBack?` | `any` | 回调函数 |

#### Returns

`void`

___

### clearAllMenuTheme

▸ **clearAllMenuTheme**(): `void`

清除所有Tab的主题

#### Returns

`void`

___

### closeAllTab

▸ **closeAllTab**(): `void`

#### Returns

`void`

___

### getBodyContainer

▸ **getBodyContainer**(): `any`

获取整个系统框架容器

#### Returns

`any`

Ext.container.Viewport

___

### getCurrClickTarget

▸ **getCurrClickTarget**(): `any`

#### Returns

`any`

___

### getMouseClickXY

▸ **getMouseClickXY**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

___

### selectMenu

▸ **selectMenu**(`menuId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `menuId` | `string` |

#### Returns

`void`

___

### setCurrClickTarget

▸ **setCurrClickTarget**(`target`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |

#### Returns

`void`

___

### setMouseClickXY

▸ **setMouseClickXY**(`x`, `y`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`void`

___

### showByCmp

▸ **showByCmp**(`component`, `id`, `title`, `icon`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `component` | `any` |
| `id` | `any` |
| `title` | `any` |
| `icon` | `any` |

#### Returns

`void`

___

### showByLevel

▸ **showByLevel**(`menuLevelPath`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `menuLevelPath` | `string` |

#### Returns

`void`

___

### showByMenu

▸ **showByMenu**(`menu`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`void`

___

### showByMenuId

▸ **showByMenuId**(`menuId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `menuId` | `string` |

#### Returns

`void`

___

### showByMethod

▸ **showByMethod**(`method`, `tabId`, `title`, `icon`, `where?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `tabId` | `string` |
| `title` | `string` |
| `icon` | `string` |
| `where?` | `any` |

#### Returns

`void`

___

### showGlobalSearch

▸ **showGlobalSearch**(`obj`, `entityCodes?`, `parentContainerCmp?`, `extraParams?`): `void`

显示全局搜索弹框

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` |  |
| `entityCodes?` | `any` | 指定entityCode |
| `parentContainerCmp?` | `any` | 父容器 |
| `extraParams?` | `any` | 扩展参数 |

#### Returns

`void`

___

### showMenuColumns

▸ **showMenuColumns**(`obj`, `checked`): `any`

显示功能菜单和功能列

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `checked` | `any` |

#### Returns

`any`
