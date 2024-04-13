[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / IndexLayout

# Class: IndexLayout

[FastExt](../modules/FastExt.md).IndexLayout

首页的布局

## Table of contents

### Constructors

- [constructor](FastExt.IndexLayout.md#constructor)

### Properties

- [\_monitor](FastExt.IndexLayout.md#_monitor)

### Methods

- [getMonitorData](FastExt.IndexLayout.md#getmonitordata)
- [getSystemConfigPanel](FastExt.IndexLayout.md#getsystemconfigpanel)
- [getSystemMonitorPanel](FastExt.IndexLayout.md#getsystemmonitorpanel)
- [getSystemOperatePanel](FastExt.IndexLayout.md#getsystemoperatepanel)
- [getSystemVersionPanel](FastExt.IndexLayout.md#getsystemversionpanel)
- [getSystemWaitNoticePanel](FastExt.IndexLayout.md#getsystemwaitnoticepanel)
- [getWelcomePanel](FastExt.IndexLayout.md#getwelcomepanel)
- [setDoneSystemWait](FastExt.IndexLayout.md#setdonesystemwait)
- [showMonitorChart](FastExt.IndexLayout.md#showmonitorchart)
- [showSearchSysOperate](FastExt.IndexLayout.md#showsearchsysoperate)
- [showSystemLogDetails](FastExt.IndexLayout.md#showsystemlogdetails)
- [startCheckSystemWait](FastExt.IndexLayout.md#startchecksystemwait)
- [uploadSystemConfigData](FastExt.IndexLayout.md#uploadsystemconfigdata)

## Constructors

### constructor

• **new IndexLayout**(): [`IndexLayout`](FastExt.IndexLayout.md)

#### Returns

[`IndexLayout`](FastExt.IndexLayout.md)

## Properties

### \_monitor

▪ `Static` `Private` **\_monitor**: `Object`

系统的监控信息

#### Type declaration

| Name | Type |
| :------ | :------ |
| `data` | `any`[] |
| `desc` | `any`[] |

## Methods

### getMonitorData

▸ **getMonitorData**(`index`): `any`

获取系统监控信息的数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `index` | `any` | 监控信息的索引 |

#### Returns

`any`

___

### getSystemConfigPanel

▸ **getSystemConfigPanel**(`header?`): `any`

获取系统配置的组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `header?` | `boolean` |

#### Returns

`any`

Ext.form.FormPanel

___

### getSystemMonitorPanel

▸ **getSystemMonitorPanel**(`header?`): `any`

获取系统监控信息的组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `header?` | `boolean` |

#### Returns

`any`

Ext.panel.Panel

___

### getSystemOperatePanel

▸ **getSystemOperatePanel**(`header?`): `any`

获取系统操作日志组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `header?` | `boolean` |

#### Returns

`any`

Ext.grid.Panel

___

### getSystemVersionPanel

▸ **getSystemVersionPanel**(`header?`): `any`

获取系统版本信息的组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `header?` | `boolean` |

#### Returns

`any`

Ext.grid.Panel

___

### getSystemWaitNoticePanel

▸ **getSystemWaitNoticePanel**(`header?`): `any`

获取系统待办事项组件

#### Parameters

| Name | Type |
| :------ | :------ |
| `header?` | `boolean` |

#### Returns

`any`

Ext.grid.Panel

___

### getWelcomePanel

▸ **getWelcomePanel**(): `any`

获取首页欢迎页面的组件

#### Returns

`any`

Ext.panel.Panel

___

### setDoneSystemWait

▸ **setDoneSystemWait**(`noticeId`): `void`

标记待办事项已完成

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `noticeId` | `any` | 待办事项ID |

#### Returns

`void`

___

### showMonitorChart

▸ **showMonitorChart**(`title`, `index`): `void`

显示系统监控的图表信息

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `title` | `any` | 标题 |
| `index` | `any` | 监控信息的索引 |

#### Returns

`void`

___

### showSearchSysOperate

▸ **showSearchSysOperate**(`grid`, `obj`): `any`

弹出搜索系统操作日志窗体

#### Parameters

| Name | Type |
| :------ | :------ |
| `grid` | `any` |
| `obj` | `any` |

#### Returns

`any`

Ext.window.Window

___

### showSystemLogDetails

▸ **showSystemLogDetails**(`id`): `void`

弹出系统操作日志的详情

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `id` | `string` | 日志ID |

#### Returns

`void`

Ext.window.Window

___

### startCheckSystemWait

▸ **startCheckSystemWait**(`justRefresh?`): `void`

开启系统待办事项的监听

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `justRefresh?` | `any` | 是否强制刷新所有待办 |

#### Returns

`void`

___

### uploadSystemConfigData

▸ **uploadSystemConfigData**(`obj`): `void`

上传系统配置的数据文件

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`void`
