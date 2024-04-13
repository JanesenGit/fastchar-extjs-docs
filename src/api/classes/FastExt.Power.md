[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Power

# Class: Power

[FastExt](../modules/FastExt.md).Power

## Table of contents

### Constructors

- [constructor](FastExt.Power.md#constructor)

### Properties

- [config](FastExt.Power.md#config)
- [defaultPower](FastExt.Power.md#defaultpower)
- [menuShowing](FastExt.Power.md#menushowing)
- [powerVersion](FastExt.Power.md#powerversion)
- [powers](FastExt.Power.md#powers)
- [types](FastExt.Power.md#types)

### Methods

- [checkManagerPower](FastExt.Power.md#checkmanagerpower)
- [checkPower](FastExt.Power.md#checkpower)
- [getPowerCode](FastExt.Power.md#getpowercode)
- [getSavePowerData](FastExt.Power.md#getsavepowerdata)
- [hasPower](FastExt.Power.md#haspower)
- [isPower](FastExt.Power.md#ispower)
- [pushPower](FastExt.Power.md#pushpower)
- [setPower](FastExt.Power.md#setpower)
- [setPowerStyle](FastExt.Power.md#setpowerstyle)
- [showPowerConfig](FastExt.Power.md#showpowerconfig)
- [showPowerExt](FastExt.Power.md#showpowerext)
- [showPowerMenus](FastExt.Power.md#showpowermenus)

## Constructors

### constructor

• **new Power**(): [`Power`](FastExt.Power.md)

#### Returns

[`Power`](FastExt.Power.md)

## Properties

### config

▪ `Static` **config**: `boolean` = `false`

是否正在进行配置权限

___

### defaultPower

▪ `Static` **defaultPower**: [`PowerSet`](FastExt.PowerSet.md)

默认的权限配置

**`See`**

[FastExt.PowerSet](FastExt.PowerSet.md)

___

### menuShowing

▪ `Static` **menuShowing**: `boolean` = `false`

权限菜单是否已打开

___

### powerVersion

▪ `Static` **powerVersion**: `string` = `"2.0"`

系统权限编号版本号

___

### powers

▪ `Static` **powers**: `any` = `[]`

组件权限的集合

___

### types

▪ `Static` **types**: [`PowerType`](../enums/FastEnum.PowerType.md)[]

允许进行权限配置的类型

**`See`**

[FastEnum.PowerType](../enums/FastEnum.PowerType.md)

## Methods

### checkManagerPower

▸ **checkManagerPower**(`target`): `any`

获取管理员的目标组件权限

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |

#### Returns

`any`

___

### checkPower

▸ **checkPower**(`code`): `any`

检查权限

#### Parameters

| Name | Type |
| :------ | :------ |
| `code` | `any` |

#### Returns

`any`

___

### getPowerCode

▸ **getPowerCode**(`obj`): `string`

获取组件的唯一权限编号

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`string`

___

### getSavePowerData

▸ **getSavePowerData**(): `string`

获取保存权限配置的值

#### Returns

`string`

___

### hasPower

▸ **hasPower**(`target`, `type`): `boolean`

判断目标组件是否有指定权限值

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |
| `type` | `any` |

#### Returns

`boolean`

___

### isPower

▸ **isPower**(): `boolean`

是否正在进行权限配置操作

#### Returns

`boolean`

___

### pushPower

▸ **pushPower**(`code`, `config`): `void`

添加权限配置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `code` | `any` | 唯一编号 |
| `config` | `any` | 配置 |

#### Returns

`void`

**`See`**

[FastExt.PowerSet](FastExt.PowerSet.md)

___

### setPower

▸ **setPower**(`code`, `config`): `void`

设置权限配置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `code` | `any` | 唯一编号 |
| `config` | `any` | 配置 |

#### Returns

`void`

**`See`**

[FastExt.PowerSet](FastExt.PowerSet.md)

___

### setPowerStyle

▸ **setPowerStyle**(`target`): `void`

设置权限状态下的样式

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |

#### Returns

`void`

___

### showPowerConfig

▸ **showPowerConfig**(`target`, `e`): `void`

弹出组件的权限配置菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |
| `e` | `any` |

#### Returns

`void`

___

### showPowerExt

▸ **showPowerExt**(`obj`, `menuPower`, `extPower`, `parentExtPower`): `any`

弹出界面权限配置的窗体

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 动画对象 |
| `menuPower` | `any` | 指定菜单权限 |
| `extPower` | `any` | 已配置的界面权限 |
| `parentExtPower` | `any` | 指定上级的界面权限 |

#### Returns

`any`

___

### showPowerMenus

▸ **showPowerMenus**(`obj`, `checked`, `parent`): `any`

弹出菜单权限的配置窗体

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 动画对象 |
| `checked` | `any` | 已选中的菜单Id |
| `parent` | `any` | 指定上级的菜单Id |

#### Returns

`any`

Ext.Promise
