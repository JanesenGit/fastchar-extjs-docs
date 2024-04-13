[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExtend](../modules/FastExtend.md) / ArrayExtend

# Class: ArrayExtend

[FastExtend](../modules/FastExtend.md).ArrayExtend

数组相关扩展

**`Define`**

使用Array对象调用以下方法或属性

**`Example`**

```ts
let userIds=[1,2,3,4];
userIds.exists(1);
```

## Table of contents

### Constructors

- [constructor](FastExtend.ArrayExtend.md#constructor)

### Methods

- [exists](FastExtend.ArrayExtend.md#exists)
- [pushAt](FastExtend.ArrayExtend.md#pushat)
- [remove](FastExtend.ArrayExtend.md#remove)
- [\_\_onLoaded](FastExtend.ArrayExtend.md#__onloaded)

## Constructors

### constructor

• **new ArrayExtend**(): [`ArrayExtend`](FastExtend.ArrayExtend.md)

#### Returns

[`ArrayExtend`](FastExtend.ArrayExtend.md)

## Methods

### exists

▸ **exists**(`val`): `boolean`

判断是否存在于数组中

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |

#### Returns

`boolean`

**`Example`**

```ts
let userIds=[1,2,3,4];
userIds.exists(1);
```

___

### pushAt

▸ **pushAt**(`index`, `val`): `void`

判断是否存在于数组中

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `index` | `any` | 索引位置 |
| `val` | `any` |  |

#### Returns

`void`

**`Example`**

```ts
let userIds=[1,2,3,4];
userIds.pushAt(0,-1);
```

___

### remove

▸ **remove**(`val`): `void`

删除某个元素

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |

#### Returns

`void`

**`Example`**

```ts
let userIds=[1,2,3,4];
userIds.remove(1);
```

___

### \_\_onLoaded

▸ **__onLoaded**(): `void`

#### Returns

`void`
