[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Lottie

# Class: Lottie

[FastExt](../modules/FastExt.md).Lottie

Lottie操作类 https://airbnb.design/lottie/

## Table of contents

### Constructors

- [constructor](FastExt.Lottie.md#constructor)

### Properties

- [lottieJsPath](FastExt.Lottie.md#lottiejspath)

### Methods

- [getLottie](FastExt.Lottie.md#getlottie)
- [getLottieByEl](FastExt.Lottie.md#getlottiebyel)
- [getLottieByElId](FastExt.Lottie.md#getlottiebyelid)
- [loadJsonAnim](FastExt.Lottie.md#loadjsonanim)
- [loadJsonAnimByEl](FastExt.Lottie.md#loadjsonanimbyel)
- [showLottie](FastExt.Lottie.md#showlottie)
- [unloadJsonAnim](FastExt.Lottie.md#unloadjsonanim)
- [unloadJsonAnimByEl](FastExt.Lottie.md#unloadjsonanimbyel)
- [unloadJsonAnimById](FastExt.Lottie.md#unloadjsonanimbyid)

## Constructors

### constructor

• **new Lottie**(): [`Lottie`](FastExt.Lottie.md)

#### Returns

[`Lottie`](FastExt.Lottie.md)

## Properties

### lottieJsPath

▪ `Static` **lottieJsPath**: `string` = `"base/lottie/lottie.min.js"`

lottie.min.js文件的路径

## Methods

### getLottie

▸ **getLottie**(`cmb`): `any`

获取cmb已加载渲染的lottie对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `cmb` | `any` |

#### Returns

`any`

___

### getLottieByEl

▸ **getLottieByEl**(`el`): `any`

获取cmb已加载渲染的lottie对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `el` | `any` |

#### Returns

`any`

___

### getLottieByElId

▸ **getLottieByElId**(`elId`): `any`

获取cmb已加载渲染的lottie对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `elId` | `any` |

#### Returns

`any`

___

### loadJsonAnim

▸ **loadJsonAnim**(`cmb`, `jsonPath`, `callBack?`): `void`

渲染lottie json动画到指定的组件中

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cmb` | `any` | 组件 |
| `jsonPath` | `any` | lottie动画的json数据地址 |
| `callBack?` | `any` | 加载成后的回调 |

#### Returns

`void`

___

### loadJsonAnimByEl

▸ **loadJsonAnimByEl**(`el`, `jsonPath`, `callBack?`): `void`

渲染lottie json动画到指定的组件中

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `el` | `any` | HtmlElement |
| `jsonPath` | `string` | lottie动画的json数据地址 |
| `callBack?` | `any` | 加载成后的回调 |

#### Returns

`void`

___

### showLottie

▸ **showLottie**(`obj`, `jsonPath`): `void`

查看lottie动效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框动画对象 |
| `jsonPath` | `any` | lottie的json文件路径 |

#### Returns

`void`

___

### unloadJsonAnim

▸ **unloadJsonAnim**(`cmb`): `void`

卸载lottie动画

#### Parameters

| Name | Type |
| :------ | :------ |
| `cmb` | `any` |

#### Returns

`void`

___

### unloadJsonAnimByEl

▸ **unloadJsonAnimByEl**(`el`): `void`

卸载lottie动画

#### Parameters

| Name | Type |
| :------ | :------ |
| `el` | `any` |

#### Returns

`void`

___

### unloadJsonAnimById

▸ **unloadJsonAnimById**(`elId`): `void`

卸载lottie动画

#### Parameters

| Name | Type |
| :------ | :------ |
| `elId` | `any` |

#### Returns

`void`
