[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Animate

# Class: Animate

[FastExt](../modules/FastExt.md).Animate

## Table of contents

### Constructors

- [constructor](FastExt.Animate.md#constructor)

### Properties

- [animateJsPath](FastExt.Animate.md#animatejspath)
- [animateMap](FastExt.Animate.md#animatemap)

### Methods

- [clearAnimate](FastExt.Animate.md#clearanimate)
- [isAnimating](FastExt.Animate.md#isanimating)
- [loader](FastExt.Animate.md#loader)
- [startCloseAnimateByHeight](FastExt.Animate.md#startcloseanimatebyheight)
- [startCloseAnimateByWidth](FastExt.Animate.md#startcloseanimatebywidth)
- [startHideAnimateByWidth](FastExt.Animate.md#starthideanimatebywidth)
- [startMaxButtonAnimateByWidth](FastExt.Animate.md#startmaxbuttonanimatebywidth)
- [startMinButtonAnimateByWidth](FastExt.Animate.md#startminbuttonanimatebywidth)
- [startValueAnimate](FastExt.Animate.md#startvalueanimate)

## Constructors

### constructor

• **new Animate**(): [`Animate`](FastExt.Animate.md)

#### Returns

[`Animate`](FastExt.Animate.md)

## Properties

### animateJsPath

▪ `Static` **animateJsPath**: `string` = `"base/animejs/anime.min.js"`

___

### animateMap

▪ `Static` **animateMap**: `Object` = `{}`

## Methods

### clearAnimate

▸ **clearAnimate**(`animateCode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `animateCode` | `string` |

#### Returns

`void`

___

### isAnimating

▸ **isAnimating**(`cmb`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `cmb` | `any` |

#### Returns

`boolean`

___

### loader

▸ **loader**(`callBack`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callBack` | `any` |

#### Returns

`void`

___

### startCloseAnimateByHeight

▸ **startCloseAnimateByHeight**(`cmb`): `void`

根据组件高度，动画释放组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `cmb` | `any` |

#### Returns

`void`

___

### startCloseAnimateByWidth

▸ **startCloseAnimateByWidth**(`cmb`): `void`

根据组件宽度，动画释放组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `cmb` | `any` |

#### Returns

`void`

___

### startHideAnimateByWidth

▸ **startHideAnimateByWidth**(`cmb`): `void`

根据组件宽度，动画隐藏组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `cmb` | `any` |

#### Returns

`void`

___

### startMaxButtonAnimateByWidth

▸ **startMaxButtonAnimateByWidth**(`button`, `delay?`): `void`

根据组件宽度，动画隐藏组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `button` | `any` |
| `delay?` | `number` |

#### Returns

`void`

___

### startMinButtonAnimateByWidth

▸ **startMinButtonAnimateByWidth**(`button`, `delay`): `void`

根据组件宽度，动画隐藏组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `button` | `any` |
| `delay` | `number` |

#### Returns

`void`

___

### startValueAnimate

▸ **startValueAnimate**(`animateCode`, `animateConfig`): `any`

开启一段zhi动画

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `animateCode` | `string` | 动画标识 |
| `animateConfig` | `any` | 动画配置 |

#### Returns

`any`
