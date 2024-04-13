[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Eval

# Class: Eval

[FastExt](../modules/FastExt.md).Eval

动态执行功能

## Table of contents

### Constructors

- [constructor](FastExt.Eval.md#constructor)

### Methods

- [asyncMethod](FastExt.Eval.md#asyncmethod)
- [runObject](FastExt.Eval.md#runobject)

## Constructors

### constructor

• **new Eval**(): [`Eval`](FastExt.Eval.md)

#### Returns

[`Eval`](FastExt.Eval.md)

## Methods

### asyncMethod

▸ **asyncMethod**(`method`, `delay?`): `ExtPromise`

异步执行函数

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `delay?` | `number` |

#### Returns

`ExtPromise`

___

### runObject

▸ **runObject**(`object`, `content`): `string`

动态执行解析对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `object` | `any` | 对象 |
| `content` | `string` | 含表达式的内容，例如：当前登录${manage.name} |

#### Returns

`string`
