[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Listeners

# Class: Listeners

[FastExt](../modules/FastExt.md).Listeners

系统部分功能全局事件监听

## Table of contents

### Constructors

- [constructor](FastExt.Listeners.md#constructor)

### Properties

- [\_listeners](FastExt.Listeners.md#_listeners)

### Methods

- [addListener](FastExt.Listeners.md#addlistener)
- [getFire](FastExt.Listeners.md#getfire)
- [getListeners](FastExt.Listeners.md#getlisteners)

## Constructors

### constructor

• **new Listeners**(): [`Listeners`](FastExt.Listeners.md)

#### Returns

[`Listeners`](FastExt.Listeners.md)

## Properties

### \_listeners

▪ `Static` `Private` **\_listeners**: [`SystemListener`](../interfaces/FastExt.SystemListener.md)[] = `[]`

## Methods

### addListener

▸ **addListener**(`listener`): `void`

添加系统事件监听

#### Parameters

| Name | Type |
| :------ | :------ |
| `listener` | [`SystemListener`](../interfaces/FastExt.SystemListener.md) |

#### Returns

`void`

___

### getFire

▸ **getFire**(): `ListenerFirer`

获取系统事件触发句柄

#### Returns

`ListenerFirer`

___

### getListeners

▸ **getListeners**(): [`SystemListener`](../interfaces/FastExt.SystemListener.md)[]

#### Returns

[`SystemListener`](../interfaces/FastExt.SystemListener.md)[]
