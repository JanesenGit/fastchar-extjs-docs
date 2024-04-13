[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / DesktopEvent

# Class: DesktopEvent

[FastExt](../modules/FastExt.md).DesktopEvent

桌面相关的事件

## Table of contents

### Constructors

- [constructor](FastExt.DesktopEvent.md#constructor)

### Methods

- [onFastDesktopContextMenu](FastExt.DesktopEvent.md#onfastdesktopcontextmenu)
- [onFastDesktopFolderContextMenu](FastExt.DesktopEvent.md#onfastdesktopfoldercontextmenu)
- [onFastDesktopImageClick](FastExt.DesktopEvent.md#onfastdesktopimageclick)
- [onFastDesktopItemClick](FastExt.DesktopEvent.md#onfastdesktopitemclick)
- [onFastDesktopItemContextMenu](FastExt.DesktopEvent.md#onfastdesktopitemcontextmenu)
- [onFastMenuItemContextMenu](FastExt.DesktopEvent.md#onfastmenuitemcontextmenu)
- [onFastMuuriGridChange](FastExt.DesktopEvent.md#onfastmuurigridchange)
- [onFastMuuriGridDragEnd](FastExt.DesktopEvent.md#onfastmuurigriddragend)
- [onFastMuuriGridDragInit](FastExt.DesktopEvent.md#onfastmuurigriddraginit)
- [onFastMuuriGridDragSort](FastExt.DesktopEvent.md#onfastmuurigriddragsort)
- [onFastMuuriGridDragSortPredicate](FastExt.DesktopEvent.md#onfastmuurigriddragsortpredicate)
- [onFastMuuriGridDragStartPredicate](FastExt.DesktopEvent.md#onfastmuurigriddragstartpredicate)
- [onFastMuuriGridSend](FastExt.DesktopEvent.md#onfastmuurigridsend)
- [onFastToolBarMenuButtonClick](FastExt.DesktopEvent.md#onfasttoolbarmenubuttonclick)
- [onFastToolbarDrop](FastExt.DesktopEvent.md#onfasttoolbardrop)
- [onFastToolbarMenuButtonContextMenu](FastExt.DesktopEvent.md#onfasttoolbarmenubuttoncontextmenu)
- [onFastToolbarStartDrag](FastExt.DesktopEvent.md#onfasttoolbarstartdrag)
- [onFastWindowMenuClick](FastExt.DesktopEvent.md#onfastwindowmenuclick)
- [onFastWindowMenuDestroy](FastExt.DesktopEvent.md#onfastwindowmenudestroy)

## Constructors

### constructor

• **new DesktopEvent**(): [`DesktopEvent`](FastExt.DesktopEvent.md)

#### Returns

[`DesktopEvent`](FastExt.DesktopEvent.md)

## Methods

### onFastDesktopContextMenu

▸ **onFastDesktopContextMenu**(`event`): `void`

系统桌面右键菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `any` |

#### Returns

`void`

___

### onFastDesktopFolderContextMenu

▸ **onFastDesktopFolderContextMenu**(`event`): `void`

在桌面文件夹内的右键菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `any` |

#### Returns

`void`

___

### onFastDesktopImageClick

▸ **onFastDesktopImageClick**(): `void`

桌面背景图片选择时点击

#### Returns

`void`

___

### onFastDesktopItemClick

▸ **onFastDesktopItemClick**(`e`): `void`

桌面图标点击事件，jquery触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `any` |

#### Returns

`void`

___

### onFastDesktopItemContextMenu

▸ **onFastDesktopItemContextMenu**(`event`): `boolean`

系统桌面选项菜单,jquery触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `any` |

#### Returns

`boolean`

___

### onFastMenuItemContextMenu

▸ **onFastMenuItemContextMenu**(`treeView`, `menuData`, `event`): `void`

系统菜单 右键菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `treeView` | `any` |
| `menuData` | `any` |
| `event` | `any` |

#### Returns

`void`

___

### onFastMuuriGridChange

▸ **onFastMuuriGridChange**(`items`): `void`

监听muurigrid添加或删除选项

#### Parameters

| Name | Type |
| :------ | :------ |
| `items` | `any` |

#### Returns

`void`

___

### onFastMuuriGridDragEnd

▸ **onFastMuuriGridDragEnd**(`items`): `void`

监听muurigrid拖拽结束

#### Parameters

| Name | Type |
| :------ | :------ |
| `items` | `any` |

#### Returns

`void`

___

### onFastMuuriGridDragInit

▸ **onFastMuuriGridDragInit**(): `void`

当muuri拖拽开始时

#### Returns

`void`

___

### onFastMuuriGridDragSort

▸ **onFastMuuriGridDragSort**(): `any`[]

获取桌面所有可拖拽的muuri-grid

#### Returns

`any`[]

___

### onFastMuuriGridDragSortPredicate

▸ **onFastMuuriGridDragSortPredicate**(`item`, `event`): `any`

监听拖拽并切换muuriGrid

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |
| `event` | `any` |

#### Returns

`any`

___

### onFastMuuriGridDragStartPredicate

▸ **onFastMuuriGridDragStartPredicate**(`item`, `event`): `any`

监听muuriGrid开始拖拽选项控制

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |
| `event` | `any` |

#### Returns

`any`

___

### onFastMuuriGridSend

▸ **onFastMuuriGridSend**(`data`): `void`

当从muuriGrid发送到另一个muuriGrid的时候

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

`void`

___

### onFastToolBarMenuButtonClick

▸ **onFastToolBarMenuButtonClick**(): `void`

工具栏的菜单按钮点击

#### Returns

`void`

___

### onFastToolbarDrop

▸ **onFastToolbarDrop**(): `void`

当工具栏拖拽结束时

#### Returns

`void`

___

### onFastToolbarMenuButtonContextMenu

▸ **onFastToolbarMenuButtonContextMenu**(`event`): `void`

工具栏的菜单按钮的右键菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `any` |

#### Returns

`void`

___

### onFastToolbarStartDrag

▸ **onFastToolbarStartDrag**(`obj`, `container`, `dragCmp`, `idx`, `eOpts`): `void`

当拖拽工具栏上的按钮时

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `container` | `any` |
| `dragCmp` | `any` |
| `idx` | `any` |
| `eOpts` | `any` |

#### Returns

`void`

___

### onFastWindowMenuClick

▸ **onFastWindowMenuClick**(`obj`): `void`

菜单窗体的路径点击事件

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`void`

___

### onFastWindowMenuDestroy

▸ **onFastWindowMenuDestroy**(): `void`

menu所在的window对象销毁时

#### Returns

`void`
