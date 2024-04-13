[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / LoginLayout

# Class: LoginLayout

[FastExt](../modules/FastExt.md).LoginLayout

登录的布局

## Table of contents

### Constructors

- [constructor](FastExt.LoginLayout.md#constructor)

### Properties

- [\_sessionOutAlert](FastExt.LoginLayout.md#_sessionoutalert)

### Methods

- [isShownSessionOutAlert](FastExt.LoginLayout.md#isshownsessionoutalert)
- [showLoginPanel](FastExt.LoginLayout.md#showloginpanel)
- [showLogout](FastExt.LoginLayout.md#showlogout)
- [showSessionOut](FastExt.LoginLayout.md#showsessionout)
- [validOperate](FastExt.LoginLayout.md#validoperate)

## Constructors

### constructor

• **new LoginLayout**(): [`LoginLayout`](FastExt.LoginLayout.md)

#### Returns

[`LoginLayout`](FastExt.LoginLayout.md)

## Properties

### \_sessionOutAlert

▪ `Static` `Private` **\_sessionOutAlert**: `boolean`

## Methods

### isShownSessionOutAlert

▸ **isShownSessionOutAlert**(): `boolean`

#### Returns

`boolean`

___

### showLoginPanel

▸ **showLoginPanel**(): `void`

显示登录系统的窗口

#### Returns

`void`

___

### showLogout

▸ **showLogout**(): `void`

退出登录

#### Returns

`void`

___

### showSessionOut

▸ **showSessionOut**(`message?`): `void`

会话失效弹框

#### Parameters

| Name | Type |
| :------ | :------ |
| `message?` | `any` |

#### Returns

`void`

___

### validOperate

▸ **validOperate**(`operate`, `callBack?`, `timeout?`): `void`

弹出安全验证功能操作

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `operate` | `any` | 操作功能的描述 |
| `callBack?` | `any` | 验证成功后回执函数 |
| `timeout?` | `any` | 验证后的失效时间，单位 秒 |

#### Returns

`void`
