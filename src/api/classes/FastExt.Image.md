[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Image

# Class: Image

[FastExt](../modules/FastExt.md).Image

图片相关的操作

## Table of contents

### Constructors

- [constructor](FastExt.Image.md#constructor)

### Properties

- [showAllRelationImage](FastExt.Image.md#showallrelationimage)

### Methods

- [getRealUrl](FastExt.Image.md#getrealurl)
- [rotateOSSImgUrl](FastExt.Image.md#rotateossimgurl)
- [showImage](FastExt.Image.md#showimage)
- [smallOSSImgUrl](FastExt.Image.md#smallossimgurl)

## Constructors

### constructor

• **new Image**(): [`Image`](FastExt.Image.md)

#### Returns

[`Image`](FastExt.Image.md)

## Properties

### showAllRelationImage

▪ `Static` **showAllRelationImage**: `boolean` = `true`

当点击当前图片时，是否显示与之相关并且在同一个容器中的其他图片

## Methods

### getRealUrl

▸ **getRealUrl**(`url`): `string`

获取真实的url地址

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |

#### Returns

`string`

___

### rotateOSSImgUrl

▸ **rotateOSSImgUrl**(`imgUrl`, `rotate`): `any`

获取oss旋转后的角度地址

#### Parameters

| Name | Type |
| :------ | :------ |
| `imgUrl` | `any` |
| `rotate` | `any` |

#### Returns

`any`

___

### showImage

▸ **showImage**(`obj`, `url`, `callBack`, `modal?`): `void`

查看图片

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框动画对象 |
| `url` | `any` | 图片地址 String或JsonArray |
| `callBack` | `any` | 回调函数 |
| `modal?` | `boolean` | 是否有背景阴影层 |

#### Returns

`void`

___

### smallOSSImgUrl

▸ **smallOSSImgUrl**(`imgUrl`, `size?`): `string`

获取oss缩略图

#### Parameters

| Name | Type |
| :------ | :------ |
| `imgUrl` | `string` |
| `size?` | `any` |

#### Returns

`string`
