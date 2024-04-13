[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / GridEvent

# Class: GridEvent

[FastExt](../modules/FastExt.md).GridEvent

grid事件方法类

## Table of contents

### Constructors

- [constructor](FastExt.GridEvent.md#constructor)

### Methods

- [onFastAfterTabActive](FastExt.GridEvent.md#onfastaftertabactive)
- [onFastBeforeDestroy](FastExt.GridEvent.md#onfastbeforedestroy)
- [onFastBeforeEdit](FastExt.GridEvent.md#onfastbeforeedit)
- [onFastCellContextMenu](FastExt.GridEvent.md#onfastcellcontextmenu)
- [onFastCellDblclick](FastExt.GridEvent.md#onfastcelldblclick)
- [onFastColumnMove](FastExt.GridEvent.md#onfastcolumnmove)
- [onFastColumnResize](FastExt.GridEvent.md#onfastcolumnresize)
- [onFastColumnsChanged](FastExt.GridEvent.md#onfastcolumnschanged)
- [onFastHeadMenuBeforeShow](FastExt.GridEvent.md#onfastheadmenubeforeshow)
- [onFastHeaderClick](FastExt.GridEvent.md#onfastheaderclick)
- [onFastHeaderContextMenu](FastExt.GridEvent.md#onfastheadercontextmenu)
- [onFastHeaderMenuCreate](FastExt.GridEvent.md#onfastheadermenucreate)
- [onFastHeaderTriggerClick](FastExt.GridEvent.md#onfastheadertriggerclick)
- [onFastSelectionChange](FastExt.GridEvent.md#onfastselectionchange)
- [onFastSortChange](FastExt.GridEvent.md#onfastsortchange)
- [onFastStoreBeforeLoad](FastExt.GridEvent.md#onfaststorebeforeload)
- [onFastStoreDataChanged](FastExt.GridEvent.md#onfaststoredatachanged)
- [onFastStoreEndUpdate](FastExt.GridEvent.md#onfaststoreendupdate)
- [onFastStoreLoad](FastExt.GridEvent.md#onfaststoreload)
- [onFastViewRead](FastExt.GridEvent.md#onfastviewread)

## Constructors

### constructor

• **new GridEvent**(): [`GridEvent`](FastExt.GridEvent.md)

#### Returns

[`GridEvent`](FastExt.GridEvent.md)

## Methods

### onFastAfterTabActive

▸ **onFastAfterTabActive**(): `void`

自定义事件：aftertabactive,当grid所在的tab页面被激活后

#### Returns

`void`

___

### onFastBeforeDestroy

▸ **onFastBeforeDestroy**(): `void`

事件：beforedestroy

#### Returns

`void`

___

### onFastBeforeEdit

▸ **onFastBeforeEdit**(`editor`, `context`, `eOpts`): `boolean`

事件：beforeedit

#### Parameters

| Name | Type |
| :------ | :------ |
| `editor` | `any` |
| `context` | `any` |
| `eOpts` | `any` |

#### Returns

`boolean`

___

### onFastCellContextMenu

▸ **onFastCellContextMenu**(`obj`, `td`, `cellIndex`, `record`, `tr`, `rowIndex`, `e`, `eOpts`): `void`

事件：cellcontextmenu

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `td` | `any` |
| `cellIndex` | `any` |
| `record` | `any` |
| `tr` | `any` |
| `rowIndex` | `any` |
| `e` | `any` |
| `eOpts` | `any` |

#### Returns

`void`

___

### onFastCellDblclick

▸ **onFastCellDblclick**(): `void`

事件：celldblclick

#### Returns

`void`

___

### onFastColumnMove

▸ **onFastColumnMove**(`ct`, `column`, `fromIdx`, `toIdx`, `eOpts`): `void`

事件：columnmove

#### Parameters

| Name | Type |
| :------ | :------ |
| `ct` | `any` |
| `column` | `any` |
| `fromIdx` | `any` |
| `toIdx` | `any` |
| `eOpts` | `any` |

#### Returns

`void`

___

### onFastColumnResize

▸ **onFastColumnResize**(`ct`, `column`, `width`, `eOpts`): `void`

事件：columnresize

#### Parameters

| Name | Type |
| :------ | :------ |
| `ct` | `any` |
| `column` | `any` |
| `width` | `any` |
| `eOpts` | `any` |

#### Returns

`void`

___

### onFastColumnsChanged

▸ **onFastColumnsChanged**(`ct`, `eOpts`): `void`

事件：columnschanged

#### Parameters

| Name | Type |
| :------ | :------ |
| `ct` | `any` |
| `eOpts` | `any` |

#### Returns

`void`

___

### onFastHeadMenuBeforeShow

▸ **onFastHeadMenuBeforeShow**(`obj`): `void`

事件：headermenu:beforeshow

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`void`

___

### onFastHeaderClick

▸ **onFastHeaderClick**(`ct`, `column`, `e`, `t`, `eOpts`): `void`

事件：headerclick

#### Parameters

| Name | Type |
| :------ | :------ |
| `ct` | `any` |
| `column` | `any` |
| `e` | `any` |
| `t` | `any` |
| `eOpts` | `any` |

#### Returns

`void`

___

### onFastHeaderContextMenu

▸ **onFastHeaderContextMenu**(`ct`, `column`, `e`, `t`, `eOpts`): `void`

事件：headercontextmenu

#### Parameters

| Name | Type |
| :------ | :------ |
| `ct` | `any` |
| `column` | `any` |
| `e` | `any` |
| `t` | `any` |
| `eOpts` | `any` |

#### Returns

`void`

___

### onFastHeaderMenuCreate

▸ **onFastHeaderMenuCreate**(`ct`, `menu`, `headerCt`, `eOpts`): `void`

事件：headermenucreate

#### Parameters

| Name | Type |
| :------ | :------ |
| `ct` | `any` |
| `menu` | `any` |
| `headerCt` | `any` |
| `eOpts` | `any` |

#### Returns

`void`

___

### onFastHeaderTriggerClick

▸ **onFastHeaderTriggerClick**(`ct`, `column`, `e`, `t`, `eOpts`): `void`

事件：headertriggerclick

#### Parameters

| Name | Type |
| :------ | :------ |
| `ct` | `any` |
| `column` | `any` |
| `e` | `any` |
| `t` | `any` |
| `eOpts` | `any` |

#### Returns

`void`

___

### onFastSelectionChange

▸ **onFastSelectionChange**(`obj`, `selected`, `eOpts`): `void`

事件：selectionchange

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `selected` | `any` |
| `eOpts` | `any` |

#### Returns

`void`

___

### onFastSortChange

▸ **onFastSortChange**(`ct`, `column`, `direction`, `eOpts`): `void`

事件：sortchange

#### Parameters

| Name | Type |
| :------ | :------ |
| `ct` | `any` |
| `column` | `any` |
| `direction` | `any` |
| `eOpts` | `any` |

#### Returns

`void`

___

### onFastStoreBeforeLoad

▸ **onFastStoreBeforeLoad**(): `void`

事件：store:beforeload

#### Returns

`void`

___

### onFastStoreDataChanged

▸ **onFastStoreDataChanged**(): `void`

事件：store:datachanged

#### Returns

`void`

___

### onFastStoreEndUpdate

▸ **onFastStoreEndUpdate**(): `boolean`

事件：store:endupdate

#### Returns

`boolean`

___

### onFastStoreLoad

▸ **onFastStoreLoad**(): `void`

事件：store:load

#### Returns

`void`

___

### onFastViewRead

▸ **onFastViewRead**(`view`, `eOpts`): `void`

事件：viewready

#### Parameters

| Name | Type |
| :------ | :------ |
| `view` | `any` |
| `eOpts` | `any` |

#### Returns

`void`
