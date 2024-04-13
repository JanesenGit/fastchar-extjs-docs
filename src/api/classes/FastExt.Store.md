[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Store

# Class: Store

[FastExt](../modules/FastExt.md).Store

Ext.data.Store数据源相关操作

## Table of contents

### Constructors

- [constructor](FastExt.Store.md#constructor)

### Properties

- [maxPageSize](FastExt.Store.md#maxpagesize)

### Methods

- [commitStoreCopy](FastExt.Store.md#commitstorecopy)
- [commitStoreDelete](FastExt.Store.md#commitstoredelete)
- [commitStoreReback](FastExt.Store.md#commitstorereback)
- [commitStoreUpdate](FastExt.Store.md#commitstoreupdate)
- [getChartGridColumnStore](FastExt.Store.md#getchartgridcolumnstore)
- [getCompareDataStore](FastExt.Store.md#getcomparedatastore)
- [getCompareLinkDataStore](FastExt.Store.md#getcomparelinkdatastore)
- [getEntityDataStore](FastExt.Store.md#getentitydatastore)
- [getEnumData](FastExt.Store.md#getenumdata)
- [getEnumDataArray](FastExt.Store.md#getenumdataarray)
- [getEnumDataByRender](FastExt.Store.md#getenumdatabyrender)
- [getEnumDataStore](FastExt.Store.md#getenumdatastore)
- [getFontSizeDataStore](FastExt.Store.md#getfontsizedatastore)
- [getFrontRadiusDataStore](FastExt.Store.md#getfrontradiusdatastore)
- [getGridColumnStore](FastExt.Store.md#getgridcolumnstore)
- [getPageDataStore](FastExt.Store.md#getpagedatastore)
- [getStoreMenuText](FastExt.Store.md#getstoremenutext)
- [getSystemLayoutDataStore](FastExt.Store.md#getsystemlayoutdatastore)
- [getThemeDataStore](FastExt.Store.md#getthemedatastore)
- [getYesOrNoDataStore](FastExt.Store.md#getyesornodatastore)
- [isModified](FastExt.Store.md#ismodified)
- [isSameRecord](FastExt.Store.md#issamerecord)
- [isSameRecordByEntity](FastExt.Store.md#issamerecordbyentity)
- [mergeStoreParamBySelect](FastExt.Store.md#mergestoreparambyselect)
- [setRecordValue](FastExt.Store.md#setrecordvalue)

## Constructors

### constructor

• **new Store**(): [`Store`](FastExt.Store.md)

#### Returns

[`Store`](FastExt.Store.md)

## Properties

### maxPageSize

▪ `Static` **maxPageSize**: `number` = `50`

每页最大页数

## Methods

### commitStoreCopy

▸ **commitStoreCopy**(`store`, `data`): `any`

提交复制entity store选择的数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `store` | `any` |
| `data` | `any` |

#### Returns

`any`

Ext.Promise

___

### commitStoreDelete

▸ **commitStoreDelete**(`store`, `data`, `extend_params?`): `any`

提交Store里被选中删除的数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `store` | `any` |  |
| `data` | `any` |  |
| `extend_params?` | `any` | 扩展参数 |

#### Returns

`any`

Ext.Promise

___

### commitStoreReback

▸ **commitStoreReback**(`store`, `data`): `any`

提交Store回收站里还原选中的数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `store` | `any` |
| `data` | `any` |

#### Returns

`any`

Ext.Promise

___

### commitStoreUpdate

▸ **commitStoreUpdate**(`store`, `successMsg?`, `extend_params?`): `any`

提交Store被修改过的数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `store` | `any` |  |
| `successMsg?` | `string` | 修改成功的消息提示 |
| `extend_params?` | `any` | 其他参数 |

#### Returns

`any`

Ext.Promise

___

### getChartGridColumnStore

▸ **getChartGridColumnStore**(`grid`): `any`

获取支持图表功能的grid列的数据源

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`any`

Ext.data.Store

___

### getCompareDataStore

▸ **getCompareDataStore**(`dataType`): `any`

获取比较符数据源

#### Parameters

| Name | Type |
| :------ | :------ |
| `dataType` | `any` |

#### Returns

`any`

Ext.data.Store

___

### getCompareLinkDataStore

▸ **getCompareLinkDataStore**(): `any`

获取比较运算式的连接符

#### Returns

`any`

Ext.data.Store

___

### getEntityDataStore

▸ **getEntityDataStore**(`entity`, `where?`, `tree?`): `any`

获取用作FastEntity通用的数据源，接口：entity/list

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体对象 |
| `where?` | `any` | 请求实体数据列表的接口参数 json对象 |
| `tree?` | `any` | 是否用作Ext.tree.Panel |

#### Returns

`any`

___

### getEnumData

▸ **getEnumData**(`enumName`, `id`, `attr?`): `any`

从枚举Store中查找枚举对应的Record

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `enumName` | `string` | 枚举名称 |
| `id` | `string` | 枚举匹配的值 |
| `attr?` | `string` | 查找的匹配的属性名，默认属性名：id |

#### Returns

`any`

Ext.data.Record

___

### getEnumDataArray

▸ **getEnumDataArray**(`enumName`, `firstData?`, `lastData?`, `params?`, `useCache?`, `reload?`): `any`

获取枚举的数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `enumName` | `string` |
| `firstData?` | `any` |
| `lastData?` | `any` |
| `params?` | `any` |
| `useCache?` | `boolean` |
| `reload?` | `boolean` |

#### Returns

`any`

___

### getEnumDataByRender

▸ **getEnumDataByRender**(`enumName`): `void`

Grid列渲染枚举接口

#### Parameters

| Name | Type |
| :------ | :------ |
| `enumName` | `string` |

#### Returns

`void`

___

### getEnumDataStore

▸ **getEnumDataStore**(`enumName`, `firstData?`, `lastData?`, `params?`, `useCache?`, `reload?`, `justData?`): `any`

获取枚举数据源，接口showEnums?enumName=

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `enumName` | `string` | 枚举名称 |
| `firstData?` | `any` | 插入头部的数据 |
| `lastData?` | `any` | 插入尾部的数据 |
| `params?` | `any` | 获取枚举接口的参数 |
| `useCache?` | `boolean` | 使用本地浏览器缓存数据 |
| `reload?` | `boolean` | 重新加载数据并更新缓存 |
| `justData?` | `boolean` | 只获取数据 |

#### Returns

`any`

Ext.data.Store

___

### getFontSizeDataStore

▸ **getFontSizeDataStore**(): `any`

获取字体大小的数据源

#### Returns

`any`

Ext.data.Store

___

### getFrontRadiusDataStore

▸ **getFrontRadiusDataStore**(): `any`

获取边角圆润度

#### Returns

`any`

Ext.data.Store

___

### getGridColumnStore

▸ **getGridColumnStore**(`grid`, `search?`): `any`

获取grid列的数据源

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |
| `search?` | `any` |

#### Returns

`any`

Ext.data.Store

___

### getPageDataStore

▸ **getPageDataStore**(`maxSize?`, `iteration?`): `any`

获取页数的数据源Store

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `maxSize?` | `any` | 最大页数 默认 100 |
| `iteration?` | `any` | 每页迭代的增长因素 默认 10 |

#### Returns

`any`

Ext.data.Store

___

### getStoreMenuText

▸ **getStoreMenuText**(`store`, `menu?`, `splitChar?`): `string`

获取store相关的功能菜单文字，包含了父类

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `store` | `any` | 数据源 |
| `menu?` | `any` | 数据源的菜单对象 |
| `splitChar?` | `string` | 菜单拼接的分隔符 |

#### Returns

`string`

___

### getSystemLayoutDataStore

▸ **getSystemLayoutDataStore**(): `any`

获取系统排版的数据源

#### Returns

`any`

Ext.data.Store

___

### getThemeDataStore

▸ **getThemeDataStore**(): `any`

获取主题的数据源

#### Returns

`any`

Ext.data.Store

___

### getYesOrNoDataStore

▸ **getYesOrNoDataStore**(): `any`

获取yes或no的数据源

#### Returns

`any`

Ext.data.Store

___

### isModified

▸ **isModified**(`record`): `boolean`

判断record是否被修改过

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `record` | `any` | [Ext.data.Model] |

#### Returns

`boolean`

___

### isSameRecord

▸ **isSameRecord**(`firstRecord`, `secondRecord`): `boolean`

判断两条record数据的id属性值是否一直

#### Parameters

| Name | Type |
| :------ | :------ |
| `firstRecord` | `any` |
| `secondRecord` | `any` |

#### Returns

`boolean`

___

### isSameRecordByEntity

▸ **isSameRecordByEntity**(`entity`, `firstRecord`, `secondRecord`): `boolean`

判断两条record数据的id属性值是否一直

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | 实体对象 |
| `firstRecord` | `any` |  |
| `secondRecord` | `any` |  |

#### Returns

`boolean`

___

### mergeStoreParamBySelect

▸ **mergeStoreParamBySelect**(`store`, `selectParams`): `any`

合并选中数据的参数，将自动移除tree节点的参数

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `store` | `any` | 数据源 |
| `selectParams` | `object` | 选中的数据形成的参数 |

#### Returns

`any`

___

### setRecordValue

▸ **setRecordValue**(`record`, `dataIndex`, `field`): `void`

将field组件的值设置到record里

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `record` | `any` | record对象 |
| `dataIndex` | `any` | 属性值 |
| `field` | `any` | field对象 |

#### Returns

`void`
