[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Renders

# Class: Renders

[FastExt](../modules/FastExt.md).Renders

数据渲染器，支持column或符合格式的数据

## Table of contents

### Constructors

- [constructor](FastExt.Renders.md#constructor)

### Methods

- [bigText](FastExt.Renders.md#bigtext)
- [bigText2](FastExt.Renders.md#bigtext2)
- [code](FastExt.Renders.md#code)
- [color](FastExt.Renders.md#color)
- [dateFormat](FastExt.Renders.md#dateformat)
- [dateFormatTip](FastExt.Renders.md#dateformattip)
- [duration](FastExt.Renders.md#duration)
- [enum](FastExt.Renders.md#enum)
- [exception](FastExt.Renders.md#exception)
- [file](FastExt.Renders.md#file)
- [fileSize](FastExt.Renders.md#filesize)
- [files](FastExt.Renders.md#files)
- [getRenderColumn](FastExt.Renders.md#getrendercolumn)
- [getRenderFunStr](FastExt.Renders.md#getrenderfunstr)
- [getRenderKey](FastExt.Renders.md#getrenderkey)
- [href](FastExt.Renders.md#href)
- [html](FastExt.Renders.md#html)
- [html2](FastExt.Renders.md#html2)
- [image](FastExt.Renders.md#image)
- [image2](FastExt.Renders.md#image2)
- [images](FastExt.Renders.md#images)
- [json](FastExt.Renders.md#json)
- [json2](FastExt.Renders.md#json2)
- [link](FastExt.Renders.md#link)
- [map](FastExt.Renders.md#map)
- [mapImgLayer](FastExt.Renders.md#mapimglayer)
- [money](FastExt.Renders.md#money)
- [mp3](FastExt.Renders.md#mp3)
- [mp4](FastExt.Renders.md#mp4)
- [normal](FastExt.Renders.md#normal)
- [office](FastExt.Renders.md#office)
- [onClickFromDataClick](FastExt.Renders.md#onclickfromdataclick)
- [password](FastExt.Renders.md#password)
- [qrCode](FastExt.Renders.md#qrcode)
- [target](FastExt.Renders.md#target)
- [text](FastExt.Renders.md#text)
- [timestamp](FastExt.Renders.md#timestamp)
- [timestampTip](FastExt.Renders.md#timestamptip)
- [toClickText](FastExt.Renders.md#toclicktext)
- [toEmpty](FastExt.Renders.md#toempty)
- [toEmptyTip](FastExt.Renders.md#toemptytip)
- [toHtmlContent](FastExt.Renders.md#tohtmlcontent)
- [toLinkUrlText](FastExt.Renders.md#tolinkurltext)
- [toSingleLineText](FastExt.Renders.md#tosinglelinetext)

## Constructors

### constructor

• **new Renders**(): [`Renders`](FastExt.Renders.md)

#### Returns

[`Renders`](FastExt.Renders.md)

## Methods

### bigText

▸ **bigText**(): `any`

大文本渲染器

#### Returns

`any`

___

### bigText2

▸ **bigText2**(): `any`

大文本渲染器

#### Returns

`any`

___

### code

▸ **code**(): (`val`: `any`, `m`: `any`, `record`: `any`, `rowIndex`: `any`, `colIndex`: `any`, `store`: `any`, `view`: `any`, `details`: `any`) => `any`

代码渲染器

#### Returns

`fn`

▸ (`val`, `m`, `record`, `rowIndex`, `colIndex`, `store`, `view`, `details`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |
| `m` | `any` |
| `record` | `any` |
| `rowIndex` | `any` |
| `colIndex` | `any` |
| `store` | `any` |
| `view` | `any` |
| `details` | `any` |

##### Returns

`any`

___

### color

▸ **color**(): `any`

颜色值渲染器

#### Returns

`any`

___

### dateFormat

▸ **dateFormat**(`format?`): `any`

将日期数据进行格式化

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `format?` | `string` | 日期格式 默认：Y-m-d H:i:s |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### dateFormatTip

▸ **dateFormatTip**(`format`, `appendWeek?`): `any`

将日期格式化为生活日期提示，例如：1个小时前、1天前、1个月等

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `format` | `string` | 当超出汉字描述的范围后，使用指定的格式格式化日期 默认：Y-m-d H:i:s |
| `appendWeek?` | `boolean` | 是否追加 周几 |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### duration

▸ **duration**(): `any`

将毫秒格式的数据格式渲染，例如：1秒或1分20秒

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### enum

▸ **enum**(`enumName`, `enumValue`, `enumText`): `any`

渲染枚举数据，如果枚举返回的实体中包含color属性，则会使用color值进行颜色渲染

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `enumName` | `string` | 枚举名称 |
| `enumValue` | `string` | 枚举值的属性名 |
| `enumText` | `string` | 枚举值的显示文本属性 |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### exception

▸ **exception**(): `any`

异常内容渲染器

#### Returns

`any`

___

### file

▸ **file**(`fileNameAttr?`): `any`

文件数据渲染

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `fileNameAttr?` | `any` | 文件名称的属性，只对record有效 |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### fileSize

▸ **fileSize**(): `any`

将数据格式为单位大小后渲染，例如10kb

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### files

▸ **files**(): `any`

多文件渲染

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### getRenderColumn

▸ **getRenderColumn**(`obj`, `colIndex`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `colIndex` | `any` |

#### Returns

`any`

___

### getRenderFunStr

▸ **getRenderFunStr**(`column`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`any`

___

### getRenderKey

▸ **getRenderKey**(`colIndex`, `rowIndex`, `store`): `any`

获取当前列渲染的key

#### Parameters

| Name | Type |
| :------ | :------ |
| `colIndex` | `any` |
| `rowIndex` | `any` |
| `store` | `any` |

#### Returns

`any`

___

### href

▸ **href**(`url?`): `any`

将数据以超链接格式渲染

#### Parameters

| Name | Type |
| :------ | :------ |
| `url?` | `string` |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### html

▸ **html**(): `any`

网页内容渲染

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### html2

▸ **html2**(): `any`

网页内容渲染为存文本格式

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### image

▸ **image**(`height?`, `width?`, `justDetails?`, `clickable?`): `any`

图片数据渲染

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `height?` | `number` | 设置渲染图片的高度 |
| `width?` | `number` | 设置渲染图片的宽度 |
| `justDetails?` | `boolean` | 只应用到详情窗体中 |
| `clickable?` | `boolean` | 是否允许点击图片查看 |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### image2

▸ **image2**(): (`val`: `any`, `m`: `any`, `record`: `any`, `rowIndex`: `any`, `colIndex`: `any`, `store`: `any`, `view`: `any`) => `any`

图片渲染2

#### Returns

`fn`

▸ (`val`, `m`, `record`, `rowIndex`, `colIndex`, `store`, `view`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |
| `m` | `any` |
| `record` | `any` |
| `rowIndex` | `any` |
| `colIndex` | `any` |
| `store` | `any` |
| `view` | `any` |

##### Returns

`any`

___

### images

▸ **images**(): `any`

多图片渲染

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### json

▸ **json**(): `any`

JSON内容渲染

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### json2

▸ **json2**(): `any`

JSON内容渲染

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### link

▸ **link**(`name`, `entityCode`, `entityId`): `any`

渲染关联实体格式

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | 关联的属性,多个属性使用@符号分割 |
| `entityCode` | `string` | 实体编号 |
| `entityId` | `string` | 实体ID属性,多个属性使用@符号分割 |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### map

▸ **map**(`lngName`, `latName`, `titleName`): `any`

渲染地图格式的数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `lngName` | `string` | 经度属性名 |
| `latName` | `string` | 纬度属性名 |
| `titleName` | `string` | 链接的标题属性名 |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### mapImgLayer

▸ **mapImgLayer**(`imgUrlName`, `southWestLngLatName`, `northEastLngLatName`, `rotateName`, `zIndexName`, `minZoomName`, `maxZoomName`): `any`

渲染图层格式的数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `imgUrlName` | `string` | 图层图片的地址 数据属性名 |
| `southWestLngLatName` | `string` | 西南角度经纬度（左下角） |
| `northEastLngLatName` | `string` | 东北角度经纬度 （右上角） |
| `rotateName` | `string` | 图片旋转的角度 |
| `zIndexName` | `string` | 图层顺序 |
| `minZoomName` | `string` | 最小显示级别 |
| `maxZoomName` | `string` | 最大显示级别 |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### money

▸ **money**(): `any`

价格或金钱格式渲染

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### mp3

▸ **mp3**(): `any`

MP3渲染器

#### Returns

`any`

___

### mp4

▸ **mp4**(`nickName?`, `download?`): `any`

MP4视频渲染

#### Parameters

| Name | Type |
| :------ | :------ |
| `nickName?` | `boolean` |
| `download?` | `boolean` |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### normal

▸ **normal**(`append?`, `position?`): `any`

常规的渲染

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `append?` | `string` | 追加的单位或其他字符 |
| `position?` | `string` | 字符追加的位置 |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

**`See`**

FastEnum.AppendPosition

___

### office

▸ **office**(): `any`

word、excel、pdf等office办公软件渲染

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### onClickFromDataClick

▸ **onClickFromDataClick**(`obj`): `void`

当点击标签时触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`void`

___

### password

▸ **password**(): `any`

将数据以密码格式渲染

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### qrCode

▸ **qrCode**(): (`val`: `any`, `m`: `any`, `record`: `any`, `rowIndex`: `any`, `colIndex`: `any`) => `any`

查看二维码渲染器

#### Returns

`fn`

▸ (`val`, `m`, `record`, `rowIndex`, `colIndex`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |
| `m` | `any` |
| `record` | `any` |
| `rowIndex` | `any` |
| `colIndex` | `any` |

##### Returns

`any`

___

### target

▸ **target**(`targetId`, `targetType`, `targetFunction?`): `any`

渲染target格式的数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `targetId` | `string` | 目标ID |
| `targetType` | `string` | 目标类型 |
| `targetFunction?` | `string` | 获取目标实体的函数。默认为：getTargetEntity |

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### text

▸ **text**(): `any`

纯文本渲染器

#### Returns

`any`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

___

### timestamp

▸ **timestamp**(`format?`): (`val`: `any`, `m`: `any`, `record`: `any`, `rowIndex`: `any`, `colIndex`: `any`) => `any`

格式化时间戳

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `format?` | `string` | 日期格式 默认：Y-m-d H:i:s |

#### Returns

`fn`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

▸ (`val`, `m`, `record`, `rowIndex`, `colIndex`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |
| `m` | `any` |
| `record` | `any` |
| `rowIndex` | `any` |
| `colIndex` | `any` |

##### Returns

`any`

___

### timestampTip

▸ **timestampTip**(`format?`, `appendWeek?`): (`val`: `any`, `m`: `any`, `record`: `any`, `rowIndex`: `any`, `colIndex`: `any`) => `any`

将时间戳格式化为生活日期提示，例如：1个小时前、1天前、1个月等

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `format?` | `string` | 当超出汉字描述的范围后，使用指定的格式格式化日期 默认：Y-m-d H:i:s |
| `appendWeek?` | `boolean` | 是否追加 周几 |

#### Returns

`fn`

渲染函数 function (val, m, record, rowIndex, colIndex, store, view, details)

▸ (`val`, `m`, `record`, `rowIndex`, `colIndex`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |
| `m` | `any` |
| `record` | `any` |
| `rowIndex` | `any` |
| `colIndex` | `any` |

##### Returns

`any`

___

### toClickText

▸ **toClickText**(`text`, `clickFunctionStr`): `string`

返回可点击的文本样式

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `text` | `string` | 显示的文本 |
| `clickFunctionStr` | `string` | 点击触发的函数字符串 |

#### Returns

`string`

___

### toEmpty

▸ **toEmpty**(`tipValue`): `string`

根据提示内容返回灰色提示

#### Parameters

| Name | Type |
| :------ | :------ |
| `tipValue` | `string` |

#### Returns

`string`

___

### toEmptyTip

▸ **toEmptyTip**(): `string`

返回空数据提示

#### Returns

`string`

___

### toHtmlContent

▸ **toHtmlContent**(`val`): `any`

格式化网页展示的内容

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |

#### Returns

`any`

___

### toLinkUrlText

▸ **toLinkUrlText**(`text`, `url`): `string`

返回点击跳转的样式

#### Parameters

| Name | Type |
| :------ | :------ |
| `text` | `string` |
| `url` | `string` |

#### Returns

`string`

___

### toSingleLineText

▸ **toSingleLineText**(`val`): `any`

格式化为单行的文本，包括网页换行和符号换行等

#### Parameters

| Name | Type |
| :------ | :------ |
| `val` | `any` |

#### Returns

`any`
