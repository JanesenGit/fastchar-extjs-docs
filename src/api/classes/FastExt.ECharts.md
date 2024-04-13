[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / ECharts

# Class: ECharts

[FastExt](../modules/FastExt.md).ECharts

ECharts 5.x 操作类 https://echarts.apache.org/zh/index.html

## Table of contents

### Constructors

- [constructor](FastExt.ECharts.md#constructor)

### Properties

- [echartsJsFile](FastExt.ECharts.md#echartsjsfile)
- [echartsThemeFile](FastExt.ECharts.md#echartsthemefile)

### Methods

- [getECharts](FastExt.ECharts.md#getecharts)
- [hasECharts](FastExt.ECharts.md#hasecharts)
- [loadECharts](FastExt.ECharts.md#loadecharts)
- [loadJs](FastExt.ECharts.md#loadjs)
- [showECharts](FastExt.ECharts.md#showecharts)
- [showEntityECharts](FastExt.ECharts.md#showentityecharts)

## Constructors

### constructor

• **new ECharts**(): [`ECharts`](FastExt.ECharts.md)

#### Returns

[`ECharts`](FastExt.ECharts.md)

## Properties

### echartsJsFile

▪ `Static` **echartsJsFile**: `string` = `"base/echarts/echarts.min.js"`

echarts.min.js文件路径

___

### echartsThemeFile

▪ `Static` **echartsThemeFile**: `string` = `""`

echarts主题文件

## Methods

### getECharts

▸ **getECharts**(`cmb`): `any`

获取cmb已加载渲染的echarts对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cmb` | `any` | 组件 |

#### Returns

`any`

___

### hasECharts

▸ **hasECharts**(`cmb`): `boolean`

判断cmb是否已加载渲染的echarts对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cmb` | `any` | 组件 |

#### Returns

`boolean`

___

### loadECharts

▸ **loadECharts**(`cmb`, `option`): `void`

加载ECharts到目标组件中

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cmb` | `any` | 组件 |
| `option` | `any` | echarts配置数据选项 |

#### Returns

`void`

___

### loadJs

▸ **loadJs**(`callBack`): `void`

加载核心js代码

#### Parameters

| Name | Type |
| :------ | :------ |
| `callBack` | `any` |

#### Returns

`void`

___

### showECharts

▸ **showECharts**(`title`, `options`, `modal?`): `void`

弹窗显示echarts报表组件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `title` | `any` | 弹框标题 |
| `options` | `any` | 报表配置数据 |
| `modal?` | `any` | 模式窗口打开 |

#### Returns

`void`

___

### showEntityECharts

▸ **showEntityECharts**(`obj`, `title`, `params`, `dateTypes?`): `void`

显示实体类的图表窗体

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `title` | `string` |
| `params` | `any` |
| `dateTypes?` | `any`[] |

#### Returns

`void`
