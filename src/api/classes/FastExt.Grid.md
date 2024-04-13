[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Grid

# Class: Grid

[FastExt](../modules/FastExt.md).Grid

Ext.grid.Panel或Ext.tree.Panel相关操作

## Table of contents

### Constructors

- [constructor](FastExt.Grid.md#constructor)

### Properties

- [columnSearchMenuPadding](FastExt.Grid.md#columnsearchmenupadding)
- [detailsGridActionStyle](FastExt.Grid.md#detailsgridactionstyle)
- [detailsGridKeyStyle](FastExt.Grid.md#detailsgridkeystyle)
- [detailsGridValueStyle](FastExt.Grid.md#detailsgridvaluestyle)
- [operateWarnColor](FastExt.Grid.md#operatewarncolor)

### Methods

- [addGridContextMenu](FastExt.Grid.md#addgridcontextmenu)
- [blinkColumn](FastExt.Grid.md#blinkcolumn)
- [buildNullData](FastExt.Grid.md#buildnulldata)
- [buildSearchItem](FastExt.Grid.md#buildsearchitem)
- [buildSearchItem2](FastExt.Grid.md#buildsearchitem2)
- [buildTempData](FastExt.Grid.md#buildtempdata)
- [builderDetailsGrid](FastExt.Grid.md#builderdetailsgrid)
- [canColumnSearch](FastExt.Grid.md#cancolumnsearch)
- [checkColumnSearch](FastExt.Grid.md#checkcolumnsearch)
- [checkColumnSort](FastExt.Grid.md#checkcolumnsort)
- [checkConfigGridNumberColumn](FastExt.Grid.md#checkconfiggridnumbercolumn)
- [checkHistoryConfig](FastExt.Grid.md#checkhistoryconfig)
- [clearColumnSort](FastExt.Grid.md#clearcolumnsort)
- [configColumnListener](FastExt.Grid.md#configcolumnlistener)
- [configColumnProperty](FastExt.Grid.md#configcolumnproperty)
- [configColumnSearchLink](FastExt.Grid.md#configcolumnsearchlink)
- [configDefaultToolBar](FastExt.Grid.md#configdefaulttoolbar)
- [configGridContextMenu](FastExt.Grid.md#configgridcontextmenu)
- [configGridDefault](FastExt.Grid.md#configgriddefault)
- [configGridHeadMenu](FastExt.Grid.md#configgridheadmenu)
- [configGridHistory](FastExt.Grid.md#configgridhistory)
- [configGridLayout](FastExt.Grid.md#configgridlayout)
- [configGridListeners](FastExt.Grid.md#configgridlisteners)
- [configGridMethod](FastExt.Grid.md#configgridmethod)
- [configGridTip](FastExt.Grid.md#configgridtip)
- [configNormalGridListeners](FastExt.Grid.md#confignormalgridlisteners)
- [copyDetailsValue](FastExt.Grid.md#copydetailsvalue)
- [createDetailsGrid](FastExt.Grid.md#createdetailsgrid)
- [deleteGridData](FastExt.Grid.md#deletegriddata)
- [downDataGrid](FastExt.Grid.md#downdatagrid)
- [downExcelModel](FastExt.Grid.md#downexcelmodel)
- [exportGrid](FastExt.Grid.md#exportgrid)
- [getColumn](FastExt.Grid.md#getcolumn)
- [getColumnEnumName](FastExt.Grid.md#getcolumnenumname)
- [getColumnFieldType](FastExt.Grid.md#getcolumnfieldtype)
- [getColumnGrid](FastExt.Grid.md#getcolumngrid)
- [getColumnSimpleEditor](FastExt.Grid.md#getcolumnsimpleeditor)
- [getColumnSimpleEditorJson](FastExt.Grid.md#getcolumnsimpleeditorjson)
- [getDetailsPanel](FastExt.Grid.md#getdetailspanel)
- [getGridInWindowSize](FastExt.Grid.md#getgridinwindowsize)
- [getGridSelModel](FastExt.Grid.md#getgridselmodel)
- [getGridView](FastExt.Grid.md#getgridview)
- [getHeaderContainerGrid](FastExt.Grid.md#getheadercontainergrid)
- [getPageToolBar](FastExt.Grid.md#getpagetoolbar)
- [getRowMinHeight](FastExt.Grid.md#getrowminheight)
- [hasColumnField](FastExt.Grid.md#hascolumnfield)
- [hasSearchColumn](FastExt.Grid.md#hassearchcolumn)
- [importExcel](FastExt.Grid.md#importexcel)
- [isColumnType](FastExt.Grid.md#iscolumntype)
- [isComboColumn](FastExt.Grid.md#iscombocolumn)
- [isContentColumn](FastExt.Grid.md#iscontentcolumn)
- [isDateColumn](FastExt.Grid.md#isdatecolumn)
- [isEnumColumn](FastExt.Grid.md#isenumcolumn)
- [isFileColumn](FastExt.Grid.md#isfilecolumn)
- [isFilesColumn](FastExt.Grid.md#isfilescolumn)
- [isHtmlContentColumn](FastExt.Grid.md#ishtmlcontentcolumn)
- [isIdPropertyColumn](FastExt.Grid.md#isidpropertycolumn)
- [isLinkColumn](FastExt.Grid.md#islinkcolumn)
- [isMapColumn](FastExt.Grid.md#ismapcolumn)
- [isNumberColumn](FastExt.Grid.md#isnumbercolumn)
- [isPCAColumn](FastExt.Grid.md#ispcacolumn)
- [isTargetColumn](FastExt.Grid.md#istargetcolumn)
- [isTreeColumn](FastExt.Grid.md#istreecolumn)
- [loadDataGrid](FastExt.Grid.md#loaddatagrid)
- [onGridAfterRender](FastExt.Grid.md#ongridafterrender)
- [onGridInitComponent](FastExt.Grid.md#ongridinitcomponent)
- [rebackGridData](FastExt.Grid.md#rebackgriddata)
- [refreshColumnStyle](FastExt.Grid.md#refreshcolumnstyle)
- [refreshGridNumberColumn](FastExt.Grid.md#refreshgridnumbercolumn)
- [restoreGridButton](FastExt.Grid.md#restoregridbutton)
- [restoreGridColumn](FastExt.Grid.md#restoregridcolumn)
- [restoreGridOperate](FastExt.Grid.md#restoregridoperate)
- [saveGridButton](FastExt.Grid.md#savegridbutton)
- [saveGridColumn](FastExt.Grid.md#savegridcolumn)
- [scrollToColumn](FastExt.Grid.md#scrolltocolumn)
- [setGrid](FastExt.Grid.md#setgrid)
- [showBatchEditColumnMenu](FastExt.Grid.md#showbatcheditcolumnmenu)
- [showBatchEditColumnRandomWindow](FastExt.Grid.md#showbatcheditcolumnrandomwindow)
- [showBatchReplaceColumnWindow](FastExt.Grid.md#showbatchreplacecolumnwindow)
- [showBatchUpdateColumnWindow](FastExt.Grid.md#showbatchupdatecolumnwindow)
- [showColumnCompute](FastExt.Grid.md#showcolumncompute)
- [showColumnSearchMenu](FastExt.Grid.md#showcolumnsearchmenu)
- [showColumnSearchWin](FastExt.Grid.md#showcolumnsearchwin)
- [showColumnSortWin](FastExt.Grid.md#showcolumnsortwin)
- [showDataEditorWin](FastExt.Grid.md#showdataeditorwin)
- [showDetailsEditMenu](FastExt.Grid.md#showdetailseditmenu)
- [showDetailsWindow](FastExt.Grid.md#showdetailswindow)
- [showEChartConfigWin](FastExt.Grid.md#showechartconfigwin)
- [showGridSelectDetailsWindow](FastExt.Grid.md#showgridselectdetailswindow)
- [showPublicDetailsWindow](FastExt.Grid.md#showpublicdetailswindow)
- [showRecycleGrid](FastExt.Grid.md#showrecyclegrid)
- [showSelectRecordHistory](FastExt.Grid.md#showselectrecordhistory)
- [showTimerRefreshGrid](FastExt.Grid.md#showtimerrefreshgrid)
- [startLoadData](FastExt.Grid.md#startloaddata)
- [updateGridData](FastExt.Grid.md#updategriddata)

## Constructors

### constructor

• **new Grid**(): [`Grid`](FastExt.Grid.md)

#### Returns

[`Grid`](FastExt.Grid.md)

## Properties

### columnSearchMenuPadding

▪ `Static` **columnSearchMenuPadding**: `number` = `8`

弹出列搜索菜单的内边距

___

### detailsGridActionStyle

▪ `Static` **detailsGridActionStyle**: `string` = `"display: flex; align-items: center;justify-content: center;"`

grid格式的详情布局，动作按钮的样式

___

### detailsGridKeyStyle

▪ `Static` **detailsGridKeyStyle**: `string` = `'color:#000000;overflow:auto;text-overflow: ellipsis;white-space:normal !important;word-break:break-word;'`

grid格式的详情布局，属性名的样式

___

### detailsGridValueStyle

▪ `Static` **detailsGridValueStyle**: `string` = `'overflow:auto;text-overflow: ellipsis;white-space:normal !important;word-break:break-word;display:flex;align-items:center;line-height:24px;'`

grid格式的详情布局，属性值的样式

___

### operateWarnColor

▪ `Static` **operateWarnColor**: `string` = `'red'`

搜索、排序醒目提醒的颜色

## Methods

### addGridContextMenu

▸ **addGridContextMenu**(`grid`, `target?`, `index?`): `void`

添加grid的右键菜单选项

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `grid` | `any` | Grid对象 |
| `target?` | `any` | 菜单Ext.menu.Item |
| `index?` | `number` | 插入位置 |

#### Returns

`void`

___

### blinkColumn

▸ **blinkColumn**(`column`): `void`

闪烁列

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `column` | `any` | 列对象 |

#### Returns

`void`

___

### buildNullData

▸ **buildNullData**(`grid`): `any`

构建一条空数据的grid行数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`any`

___

### buildSearchItem

▸ **buildSearchItem**(`column`, `where?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |
| `where?` | `any` |

#### Returns

`any`

___

### buildSearchItem2

▸ **buildSearchItem2**(`column`, `where?`): `any`

获取搜索列的输入组件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `column` | `any` |  |
| `where?` | `any` | 搜索条件，默认 { compare: '=',value: ''} |

#### Returns

`any`

___

### buildTempData

▸ **buildTempData**(`grid`): `any`

构建一条模拟数据的grid行数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`any`

___

### builderDetailsGrid

▸ **builderDetailsGrid**(`fromWindow`): `any`

构建grid列表右侧详细面板中的详细数据grid控件

#### Parameters

| Name | Type |
| :------ | :------ |
| `fromWindow` | `any` |

#### Returns

`any`

___

### canColumnSearch

▸ **canColumnSearch**(`column`): `boolean`

检查column是否可以进行搜索

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### checkColumnSearch

▸ **checkColumnSearch**(`grid`): `boolean`

触发grid检查是否有搜索的列，如果有将修改底部bar的搜索按钮，突出提醒等功能

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`boolean`

___

### checkColumnSort

▸ **checkColumnSort**(`grid`): `void`

检查列的排序，将刷新Grid底部搜索按钮的样式

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### checkConfigGridNumberColumn

▸ **checkConfigGridNumberColumn**(`grid`): `boolean`

检查grid是否代码配置了显示行号的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`boolean`

___

### checkHistoryConfig

▸ **checkHistoryConfig**(`grid`): `void`

检查Grid数据选择器配置，将刷新Grid底部选择器按钮的样式

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### clearColumnSort

▸ **clearColumnSort**(`grid`): `void`

清空排序的column

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### configColumnListener

▸ **configColumnListener**(`column`): `void`

配置列的默认相关的事件功能

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`void`

___

### configColumnProperty

▸ **configColumnProperty**(`column`): `void`

配置列的扩展属性或方法

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`void`

___

### configColumnSearchLink

▸ **configColumnSearchLink**(`column`): `void`

配置指定列的搜索链

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`void`

___

### configDefaultToolBar

▸ **configDefaultToolBar**(`grid`): `void`

配置Grid默认的ToolBar功能

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### configGridContextMenu

▸ **configGridContextMenu**(`grid`): `void`

配置Grid默认的右键菜单功能

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `grid` | `any` | Grid对象 |

#### Returns

`void`

___

### configGridDefault

▸ **configGridDefault**(`grid`): `void`

配置Grid默认的全局配置

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### configGridHeadMenu

▸ **configGridHeadMenu**(`grid`): `void`

配置Grid列的默认的右键菜单功能

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### configGridHistory

▸ **configGridHistory**(`grid`): `void`

配置默认选择记忆的配置

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### configGridLayout

▸ **configGridLayout**(`grid`): `any`

配置Grid的布局

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`any`

___

### configGridListeners

▸ **configGridListeners**(`grid`): `void`

配置Grid默认绑定的事件功能

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### configGridMethod

▸ **configGridMethod**(`grid`): `void`

配置Grid扩展的方法

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### configGridTip

▸ **configGridTip**(`grid`): `void`

配置Grid的ToolTip鼠标悬浮提醒的功能

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### configNormalGridListeners

▸ **configNormalGridListeners**(`grid`): `void`

配置常规的Grid

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### copyDetailsValue

▸ **copyDetailsValue**(`view`, `rowIndex`, `colIndex`, `item`, `e`, `record`): `void`

复制详情界面单行属性值

#### Parameters

| Name | Type |
| :------ | :------ |
| `view` | `any` |
| `rowIndex` | `any` |
| `colIndex` | `any` |
| `item` | `any` |
| `e` | `any` |
| `record` | `any` |

#### Returns

`void`

___

### createDetailsGrid

▸ **createDetailsGrid**(`data`, `configGrid`, `configName`, `configValue`): `any`

创建详情数据的Grid

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `data` | `any` | 数据实体 例如：[ {"name": "账户名称","value": FastExt.System.manager["managerName"]}] |
| `configGrid` | `any` | 扩展配置Grid |
| `configName` | `any` | 扩展配置Grid属性名 |
| `configValue` | `any` | 扩展配置Grid属性值 |

#### Returns

`any`

Ext.grid.Panel

___

### deleteGridData

▸ **deleteGridData**(`grid`): `any`

操作删除Grid里选中的数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`any`

Ext.Promise

___

### downDataGrid

▸ **downDataGrid**(`grid`): `void`

下载实体数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### downExcelModel

▸ **downExcelModel**(`grid`): `void`

下载实体表格导入的数据模板

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### exportGrid

▸ **exportGrid**(`grid`): `void`

导出grid数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### getColumn

▸ **getColumn**(`grid`, `dataIndex`, `text?`): `any`

快速查找grid中的column对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `grid` | `any` |  |
| `dataIndex` | `string` | column的数据索引 |
| `text?` | `string` | column的标题 |

#### Returns

`any`

___

### getColumnEnumName

▸ **getColumnEnumName**(`column`): `any`

获得列绑定的枚举名称

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`any`

___

### getColumnFieldType

▸ **getColumnFieldType**(`column`): `any`

获取列编辑框的type类型

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`any`

___

### getColumnGrid

▸ **getColumnGrid**(`column`): `any`

获取Column所在的Grid对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`any`

___

### getColumnSimpleEditor

▸ **getColumnSimpleEditor**(`column`, `search?`): `any`

获取列的编辑控件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `column` | `any` | 列对象 |
| `search?` | `boolean` | 列的搜索对象json |

#### Returns

`any`

editor {}

___

### getColumnSimpleEditorJson

▸ **getColumnSimpleEditorJson**(`column`, `search?`): `string`

获取列的编辑控件json字符串

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `column` | `any` | 列对象 |
| `search?` | `boolean` | 列的搜索对象json |

#### Returns

`string`

___

### getDetailsPanel

▸ **getDetailsPanel**(`grid`, `fromWindow`): `any`

构建grid列表右侧详细面板

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `grid` | `any` | Grid对象 |
| `fromWindow` | `any` | 是否添加到窗体中 |

#### Returns

`any`

___

### getGridInWindowSize

▸ **getGridInWindowSize**(`grid`, `w?`, `h?`): `Object`

获取在grid内弹出窗体的一般大小尺寸

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |
| `w?` | `number` |
| `h?` | `number` |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `height` | `number` |
| `width` | `number` |

___

### getGridSelModel

▸ **getGridSelModel**(`showRowNumber?`): `any`

获得grid的选择器插件

#### Parameters

| Name | Type |
| :------ | :------ |
| `showRowNumber?` | `boolean` |

#### Returns

`any`

Ext.grid.selection.SpreadsheetModel

___

### getGridView

▸ **getGridView**(`grid`): `any`

获取grid的view

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`any`

___

### getHeaderContainerGrid

▸ **getHeaderContainerGrid**(`ct`): `any`

获取Ext.grid.header.Container所在的Grid对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `ct` | `any` | Ext.grid.header.Container对象 |

#### Returns

`any`

___

### getPageToolBar

▸ **getPageToolBar**(`dataStore`): `any`

获取Grid的分页控件

#### Parameters

| Name | Type |
| :------ | :------ |
| `dataStore` | `any` |

#### Returns

`any`

___

### getRowMinHeight

▸ **getRowMinHeight**(): `number`

获取Grid行高

#### Returns

`number`

___

### hasColumnField

▸ **hasColumnField**(`column`): `boolean`

判断column是否可编辑

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### hasSearchColumn

▸ **hasSearchColumn**(`grid`): `boolean`

判断grid中是否有正在搜索的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`boolean`

___

### importExcel

▸ **importExcel**(`obj`, `params`, `formItems?`, `serverUrl?`): `any`

导入实体的excel数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` |  |
| `params` | `any` | 接口参数 |
| `formItems?` | `any` | 配置扩展表单组件 |
| `serverUrl?` | `string` | 服务器地址 |

#### Returns

`any`

___

### isColumnType

▸ **isColumnType**(`target`): `boolean`

判断目标是否是grid的列组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |

#### Returns

`boolean`

___

### isComboColumn

▸ **isComboColumn**(`column`): `boolean`

是否是下拉框的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isContentColumn

▸ **isContentColumn**(`column`): `boolean`

是否是大文本的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isDateColumn

▸ **isDateColumn**(`column`): `boolean`

是否是日期格式的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isEnumColumn

▸ **isEnumColumn**(`column`): `boolean`

是否是枚举的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isFileColumn

▸ **isFileColumn**(`column`): `boolean`

是否文件类型的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isFilesColumn

▸ **isFilesColumn**(`column`): `boolean`

是否多文件的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isHtmlContentColumn

▸ **isHtmlContentColumn**(`column`): `boolean`

是否是富文本的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isIdPropertyColumn

▸ **isIdPropertyColumn**(`column`): `boolean`

判断列是否是对应实体类的主键

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isLinkColumn

▸ **isLinkColumn**(`column`): `boolean`

是否是关联表格的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isMapColumn

▸ **isMapColumn**(`column`): `boolean`

是否是地图的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isNumberColumn

▸ **isNumberColumn**(`column`): `boolean`

是否是数字编辑的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isPCAColumn

▸ **isPCAColumn**(`column`): `boolean`

是否是省份选择的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isTargetColumn

▸ **isTargetColumn**(`column`): `boolean`

是否目标类的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### isTreeColumn

▸ **isTreeColumn**(`column`): `boolean`

判断目标类型是否是treecolumn

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### loadDataGrid

▸ **loadDataGrid**(`obj`, `params`): `any`

上传实体数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` |  |
| `params` | `any` | 接口参数 |

#### Returns

`any`

___

### onGridAfterRender

▸ **onGridAfterRender**(`grid`): `void`

初始化Grid布局相关功能

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### onGridInitComponent

▸ **onGridInitComponent**(`grid`): `void`

初始化grid组件的自定义功能属性等

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### rebackGridData

▸ **rebackGridData**(`grid`): `any`

操作还原Grid回收站里的数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`any`

___

### refreshColumnStyle

▸ **refreshColumnStyle**(`column`): `void`

刷新列的状态样式，例如：正序、倒序、搜索等

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`void`

___

### refreshGridNumberColumn

▸ **refreshGridNumberColumn**(`grid`): `void`

刷新显示序号的列

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`void`

___

### restoreGridButton

▸ **restoreGridButton**(`entityCode`): `any`

获取grid配置的button

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityCode` | `string` |

#### Returns

`any`

___

### restoreGridColumn

▸ **restoreGridColumn**(`grid`): `any`

还原Grid保存的列配置

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`any`

___

### restoreGridOperate

▸ **restoreGridOperate**(`grid`): `any`

还原Grid保存的Operate配置

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`any`

new Ext.Promise

**`See`**

[FastExt.GridOperate](FastExt.GridOperate.md)

___

### saveGridButton

▸ **saveGridButton**(`grid`, `entity`): `any`

保存Grid中含有 bindDetail:true 属性的可点击的按钮

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |
| `entity` | `any` |

#### Returns

`any`

___

### saveGridColumn

▸ **saveGridColumn**(`grid`): `any`

保存Grid的列表配置

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`any`

Ext.Promise

___

### scrollToColumn

▸ **scrollToColumn**(`grid`, `dataIndex`, `text`): `void`

滚到到指定的列

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `grid` | `any` | grid对象 |
| `dataIndex` | `string` | 列的属性dataIndex |
| `text` | `string` | 列的标题 |

#### Returns

`void`

___

### setGrid

▸ **setGrid**(`obj`, `grid`): `void`

弹出设置grid操作界面

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 动画对象 |
| `grid` | `any` | Grid对象 |

#### Returns

`void`

**`See`**

[FastExt.GridOperate](FastExt.GridOperate.md)

___

### showBatchEditColumnMenu

▸ **showBatchEditColumnMenu**(`column`): `void`

弹出批量编辑列数的菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`void`

___

### showBatchEditColumnRandomWindow

▸ **showBatchEditColumnRandomWindow**(`column`): `void`

弹出批量随机列值窗体

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`void`

___

### showBatchReplaceColumnWindow

▸ **showBatchReplaceColumnWindow**(`column`): `void`

批量替换列的字符数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`void`

___

### showBatchUpdateColumnWindow

▸ **showBatchUpdateColumnWindow**(`column`): `void`

弹出批量更新列数的窗体

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`void`

___

### showColumnCompute

▸ **showColumnCompute**(`grid`, `column`, `type?`): `void`

计算列并显示结果

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `grid` | `any` | gri的对象 |
| `column` | `any` | 列对象 |
| `type?` | [`ComputeType`](../enums/FastEnum.ComputeType.md) | 计算方式 |

#### Returns

`void`

**`See`**

[FastEnum.ComputeType](../enums/FastEnum.ComputeType.md)

___

### showColumnSearchMenu

▸ **showColumnSearchMenu**(`column`): `boolean`

弹出列的搜索菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `column` | `any` |

#### Returns

`boolean`

___

### showColumnSearchWin

▸ **showColumnSearchWin**(`obj`, `grid`): `void`

弹出列的搜索窗体

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `grid` | `any` |

#### Returns

`void`

___

### showColumnSortWin

▸ **showColumnSortWin**(`obj`, `grid`): `void`

配置列排序的窗体

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 动画对象 |
| `grid` | `any` | grid对象 |

#### Returns

`void`

___

### showDataEditorWin

▸ **showDataEditorWin**(`obj`, `grid`): `boolean`

弹出数据编辑框，编辑选项以grid列为准

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `grid` | `any` |

#### Returns

`boolean`

___

### showDetailsEditMenu

▸ **showDetailsEditMenu**(`view`, `rowIndex`, `colIndex`, `item`, `e`, `record`): `void`

详情界面单行属性编辑框菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `view` | `any` |
| `rowIndex` | `any` |
| `colIndex` | `any` |
| `item` | `any` |
| `e` | `any` |
| `record` | `any` |

#### Returns

`void`

___

### showDetailsWindow

▸ **showDetailsWindow**(`obj`, `title`, `entity`, `record`, `buttons?`, `columnConfig?`): `void`

弹出数据的详情窗体，与Grid列表的列属性一致

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 动画对象 |
| `title` | `string` | 详情窗体标题 |
| `entity` | `any` | 实体类对象 |
| `record` | `any` | 单个数据record |
| `buttons?` | `any` | 窗口底部按钮集合 |
| `columnConfig?` | `any` | 获取列信息的配置 |

#### Returns

`void`

___

### showEChartConfigWin

▸ **showEChartConfigWin**(`obj`, `grid`): `void`

配置图表的窗体

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 动画对象 |
| `grid` | `any` | grid对象 |

#### Returns

`void`

___

### showGridSelectDetailsWindow

▸ **showGridSelectDetailsWindow**(`obj`, `grid`): `void`

查看grid选中的详情数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `grid` | `any` |

#### Returns

`void`

___

### showPublicDetailsWindow

▸ **showPublicDetailsWindow**(`obj`, `title`, `entity`, `record`, `buttons?`): `void`

弹出数据的详情窗体，与Grid列表的列属性一致，此方法不做权限限制

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 动画对象 |
| `title` | `any` | 详情窗体标题 |
| `entity` | `any` | 实体类对象 |
| `record` | `any` | 单个数据record |
| `buttons?` | `any` | 窗口底部按钮集合 |

#### Returns

`void`

___

### showRecycleGrid

▸ **showRecycleGrid**(`obj`, `dataStore`): `void`

弹出Grid绑定的实体列表回收站数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 动画对象 |
| `dataStore` | `any` | 数据源 |

#### Returns

`void`

___

### showSelectRecordHistory

▸ **showSelectRecordHistory**(`obj`, `grid`): `void`

显示Grid选择历史的配置

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `grid` | `any` |

#### Returns

`void`

___

### showTimerRefreshGrid

▸ **showTimerRefreshGrid**(`obj`, `grid`): `void`

弹出定时刷新Grid数据的窗体

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 动画对象 |
| `grid` | `any` | grid对象 |

#### Returns

`void`

___

### startLoadData

▸ **startLoadData**(): `void`

开始加载grid数据

#### Returns

`void`

___

### updateGridData

▸ **updateGridData**(`grid`): `any`

操作提交Grid被修改过的数据

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |

#### Returns

`any`

Ext.Promise
