[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExtend](../modules/FastExtend.md) / StringExtend

# Class: StringExtend

[FastExtend](../modules/FastExtend.md).StringExtend

字符串类型的相关扩展

**`Define`**

使用String对象调用以下方法或属性

**`Example`**

```ts
'user.js'.endWidth('.js');
```

## Table of contents

### Constructors

- [constructor](FastExtend.StringExtend.md#constructor)

### Methods

- [endWith](FastExtend.StringExtend.md#endwith)
- [firstUpperCase](FastExtend.StringExtend.md#firstuppercase)
- [replaceAll](FastExtend.StringExtend.md#replaceall)
- [startWith](FastExtend.StringExtend.md#startwith)
- [trimAllSymbol](FastExtend.StringExtend.md#trimallsymbol)
- [truthLength](FastExtend.StringExtend.md#truthlength)
- [\_\_onLoaded](FastExtend.StringExtend.md#__onloaded)

## Constructors

### constructor

• **new StringExtend**(): [`StringExtend`](FastExtend.StringExtend.md)

#### Returns

[`StringExtend`](FastExtend.StringExtend.md)

## Methods

### endWith

▸ **endWith**(`suffix`): `boolean`

判断字符串是否以某个字符结尾

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `suffix` | `any` | 后缀 |

#### Returns

`boolean`

**`Example`**

```ts
'user.js'.endWidth('.js');
```

___

### firstUpperCase

▸ **firstUpperCase**(): `string`

字符串处理，首字母大写

#### Returns

`string`

___

### replaceAll

▸ **replaceAll**(`oldStr`, `newStr`): `string`

替换字符

#### Parameters

| Name | Type |
| :------ | :------ |
| `oldStr` | `any` |
| `newStr` | `any` |

#### Returns

`string`

___

### startWith

▸ **startWith**(`prefix`): `boolean`

判断字符串是否以某个字符开始

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `prefix` | `any` | 前缀 |

#### Returns

`boolean`

**`Example`**

```ts
'test.js'.startWith('test')
```

___

### trimAllSymbol

▸ **trimAllSymbol**(): `string`

去除字符串的所有标点符号

#### Returns

`string`

___

### truthLength

▸ **truthLength**(): `number`

获取字符串实际长度，包含汉字

#### Returns

`number`

___

### \_\_onLoaded

▸ **__onLoaded**(): `void`

#### Returns

`void`
