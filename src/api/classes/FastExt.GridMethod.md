[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / GridMethod

# Class: GridMethod

[FastExt](../modules/FastExt.md).GridMethod

自定grid相关方法类，注意调用方法的作用域

## Table of contents

### Constructors

- [constructor](FastExt.GridMethod.md#constructor)

### Methods

- [doCheckAdd](FastExt.GridMethod.md#docheckadd)
- [doCheckDelete](FastExt.GridMethod.md#docheckdelete)
- [doCheckEditor](FastExt.GridMethod.md#docheckeditor)
- [doCheckRefreshTimer](FastExt.GridMethod.md#docheckrefreshtimer)
- [doCheckUpdate](FastExt.GridMethod.md#docheckupdate)
- [doClearSelectRecordHistory](FastExt.GridMethod.md#doclearselectrecordhistory)
- [doGetSelectRecordHistory](FastExt.GridMethod.md#dogetselectrecordhistory)
- [doHasRecordHistory](FastExt.GridMethod.md#dohasrecordhistory)
- [doHideEmptyTip](FastExt.GridMethod.md#dohideemptytip)
- [doRecordSelect](FastExt.GridMethod.md#dorecordselect)
- [doRefreshDetailsPanel](FastExt.GridMethod.md#dorefreshdetailspanel)
- [doRefreshPowerEnable](FastExt.GridMethod.md#dorefreshpowerenable)
- [doRefreshSelect](FastExt.GridMethod.md#dorefreshselect)
- [doRefreshSelectHistoryCount](FastExt.GridMethod.md#dorefreshselecthistorycount)
- [doRefreshToolPaging](FastExt.GridMethod.md#dorefreshtoolpaging)
- [doRemoveRecordHistory](FastExt.GridMethod.md#doremoverecordhistory)
- [doRestoreSelect](FastExt.GridMethod.md#dorestoreselect)
- [doSaveUIConfig](FastExt.GridMethod.md#dosaveuiconfig)
- [doShowDataLog](FastExt.GridMethod.md#doshowdatalog)
- [doShowEmptyTip](FastExt.GridMethod.md#doshowemptytip)
- [doStartRefreshTimer](FastExt.GridMethod.md#dostartrefreshtimer)
- [doStopRefreshTimer](FastExt.GridMethod.md#dostoprefreshtimer)

## Constructors

### constructor

• **new GridMethod**(): [`GridMethod`](FastExt.GridMethod.md)

#### Returns

[`GridMethod`](FastExt.GridMethod.md)

## Methods

### doCheckAdd

▸ **doCheckAdd**(): `boolean`

检测grid是否允许添加数据【作用域必须为grid】

#### Returns

`boolean`

___

### doCheckDelete

▸ **doCheckDelete**(): `boolean`

检测grid是否允许删除数据【作用域必须为grid】

#### Returns

`boolean`

___

### doCheckEditor

▸ **doCheckEditor**(): `boolean`

检测grid是否允许编辑【作用域必须为grid】

#### Returns

`boolean`

___

### doCheckRefreshTimer

▸ **doCheckRefreshTimer**(`toast`): `void`

检测grid的定时刷新器是否开启【作用域必须为grid】

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `toast` | `any` | 是否弹出提示 |

#### Returns

`void`

___

### doCheckUpdate

▸ **doCheckUpdate**(): `boolean`

检测grid是否允许修改数据【作用域必须为grid】

#### Returns

`boolean`

___

### doClearSelectRecordHistory

▸ **doClearSelectRecordHistory**(): `void`

清空grid已选中的历史数据【作用域必须为grid】

#### Returns

`void`

___

### doGetSelectRecordHistory

▸ **doGetSelectRecordHistory**(): `any`[]

获取grid已选中的历史数据【作用域必须为grid】

#### Returns

`any`[]

___

### doHasRecordHistory

▸ **doHasRecordHistory**(`record`): `boolean`

检测record是否已存在选中的历史数据中【作用域必须为grid】

#### Parameters

| Name | Type |
| :------ | :------ |
| `record` | `any` |

#### Returns

`boolean`

___

### doHideEmptyTip

▸ **doHideEmptyTip**(): `void`

隐藏空数据提示【作用域必须为grid】

#### Returns

`void`

___

### doRecordSelect

▸ **doRecordSelect**(): `void`

记录grid选择的数据,grid数据选择器使用【作用域必须为grid】

#### Returns

`void`

___

### doRefreshDetailsPanel

▸ **doRefreshDetailsPanel**(): `void`

刷新grid的详情面板数据【作用域必须为grid】

#### Returns

`void`

___

### doRefreshPowerEnable

▸ **doRefreshPowerEnable**(): `void`

刷新grid权限配置【作用域必须为grid】

#### Returns

`void`

___

### doRefreshSelect

▸ **doRefreshSelect**(): `void`

刷新grid的选择数据，并检查绑定的按钮状态【作用域必须为grid】

#### Returns

`void`

___

### doRefreshSelectHistoryCount

▸ **doRefreshSelectHistoryCount**(): `void`

刷新grid选中的历史数据统计【作用域必须为grid】

#### Returns

`void`

___

### doRefreshToolPaging

▸ **doRefreshToolPaging**(): `void`

刷新grid的选择数据，刷新分页栏【作用域必须为grid】

#### Returns

`void`

___

### doRemoveRecordHistory

▸ **doRemoveRecordHistory**(`record`): `void`

移除已选中的record数据【作用域必须为grid】

#### Parameters

| Name | Type |
| :------ | :------ |
| `record` | `any` |

#### Returns

`void`

___

### doRestoreSelect

▸ **doRestoreSelect**(): `void`

恢复grid选中的历史数据【作用域必须为grid】

#### Returns

`void`

___

### doSaveUIConfig

▸ **doSaveUIConfig**(`silence`): `void`

保存grid的UI界面配置【作用域必须为grid】

#### Parameters

| Name | Type |
| :------ | :------ |
| `silence` | `boolean` |

#### Returns

`void`

___

### doShowDataLog

▸ **doShowDataLog**(`obj?`): `void`

显示数据操作日志

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj?` | `any` |

#### Returns

`void`

___

### doShowEmptyTip

▸ **doShowEmptyTip**(): `void`

显示grid的空数据提示【作用域必须为grid】

#### Returns

`void`

___

### doStartRefreshTimer

▸ **doStartRefreshTimer**(): `void`

启动grid定时刷新器【作用域必须为grid】

#### Returns

`void`

___

### doStopRefreshTimer

▸ **doStopRefreshTimer**(): `void`

停止grid的定时刷新器【作用域必须为grid】

#### Returns

`void`
