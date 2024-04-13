[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Server

# Class: Server

[FastExt](../modules/FastExt.md).Server

请求后台接口

## Table of contents

### Constructors

- [constructor](FastExt.Server.md#constructor)

### Properties

- [silence](FastExt.Server.md#silence)

### Methods

- [\_\_onLoaded](FastExt.Server.md#__onloaded)
- [checkManager](FastExt.Server.md#checkmanager)
- [checkResponseState](FastExt.Server.md#checkresponsestate)
- [checkRestart](FastExt.Server.md#checkrestart)
- [checkVersion](FastExt.Server.md#checkversion)
- [checkWaitNotice](FastExt.Server.md#checkwaitnotice)
- [clearEntity](FastExt.Server.md#clearentity)
- [clearRepeatEntity](FastExt.Server.md#clearrepeatentity)
- [clearWaitNotice](FastExt.Server.md#clearwaitnotice)
- [clickVerify](FastExt.Server.md#clickverify)
- [computeUrl](FastExt.Server.md#computeurl)
- [copyEntity](FastExt.Server.md#copyentity)
- [countReport](FastExt.Server.md#countreport)
- [deleteAttach](FastExt.Server.md#deleteattach)
- [deleteEntity](FastExt.Server.md#deleteentity)
- [deleteExtConfig](FastExt.Server.md#deleteextconfig)
- [deleteExtConfigUrl](FastExt.Server.md#deleteextconfigurl)
- [deleteSystemConfig](FastExt.Server.md#deletesystemconfig)
- [destroyList](FastExt.Server.md#destroylist)
- [doneWaitNotice](FastExt.Server.md#donewaitnotice)
- [downData](FastExt.Server.md#downdata)
- [downSystemConfigUrl](FastExt.Server.md#downsystemconfigurl)
- [entityListUrl](FastExt.Server.md#entitylisturl)
- [excelModule](FastExt.Server.md#excelmodule)
- [exportExcel](FastExt.Server.md#exportexcel)
- [getApiHost](FastExt.Server.md#getapihost)
- [getChangelogUrl](FastExt.Server.md#getchangelogurl)
- [getDataboard](FastExt.Server.md#getdataboard)
- [getGlobalParams](FastExt.Server.md#getglobalparams)
- [getGoogleBindUrl](FastExt.Server.md#getgooglebindurl)
- [getIcon](FastExt.Server.md#geticon)
- [getSessionId](FastExt.Server.md#getsessionid)
- [globalSearchUrl](FastExt.Server.md#globalsearchurl)
- [googleReset](FastExt.Server.md#googlereset)
- [googleVerify](FastExt.Server.md#googleverify)
- [idleUrl](FastExt.Server.md#idleurl)
- [importEntityExcelUrl](FastExt.Server.md#importentityexcelurl)
- [initExtAjaxConfig](FastExt.Server.md#initextajaxconfig)
- [initJQueryConfig](FastExt.Server.md#initjqueryconfig)
- [isSilenceRequest](FastExt.Server.md#issilencerequest)
- [loadEntityDataUrl](FastExt.Server.md#loadentitydataurl)
- [loadMonitor](FastExt.Server.md#loadmonitor)
- [loadSource](FastExt.Server.md#loadsource)
- [loginUrl](FastExt.Server.md#loginurl)
- [logout](FastExt.Server.md#logout)
- [rebackEntity](FastExt.Server.md#rebackentity)
- [replaceDBEntity](FastExt.Server.md#replacedbentity)
- [reportException](FastExt.Server.md#reportexception)
- [safeToObj](FastExt.Server.md#safetoobj)
- [saveCache](FastExt.Server.md#savecache)
- [saveExtConfig](FastExt.Server.md#saveextconfig)
- [saveExtConfigUrl](FastExt.Server.md#saveextconfigurl)
- [saveSource](FastExt.Server.md#savesource)
- [saveSystemConfig](FastExt.Server.md#savesystemconfig)
- [saveSystemConfigUrl](FastExt.Server.md#savesystemconfigurl)
- [setSilence](FastExt.Server.md#setsilence)
- [showCaptchaUrl](FastExt.Server.md#showcaptchaurl)
- [showColumns](FastExt.Server.md#showcolumns)
- [showConfigUrl](FastExt.Server.md#showconfigurl)
- [showEcharts](FastExt.Server.md#showecharts)
- [showEnumsUrl](FastExt.Server.md#showenumsurl)
- [showExtConfig](FastExt.Server.md#showextconfig)
- [showExtConfigUrl](FastExt.Server.md#showextconfigurl)
- [showMenuColumnUrl](FastExt.Server.md#showmenucolumnurl)
- [showPowerMenusUrl](FastExt.Server.md#showpowermenusurl)
- [showSystemConfig](FastExt.Server.md#showsystemconfig)
- [updateAllLayer](FastExt.Server.md#updatealllayer)
- [updateAllSame](FastExt.Server.md#updateallsame)
- [updateDBEntity](FastExt.Server.md#updatedbentity)
- [updateEntity](FastExt.Server.md#updateentity)
- [updateLayer](FastExt.Server.md#updatelayer)
- [updateSame](FastExt.Server.md#updatesame)
- [uploadUrl](FastExt.Server.md#uploadurl)
- [validOperateUrl](FastExt.Server.md#validoperateurl)
- [zipFile](FastExt.Server.md#zipfile)

## Constructors

### constructor

• **new Server**(): [`Server`](FastExt.Server.md)

#### Returns

[`Server`](FastExt.Server.md)

## Properties

### silence

▪ `Static` **silence**: `boolean`

是否静默请求，设置为true时不会触发首页头部进度线条

## Methods

### \_\_onLoaded

▸ **__onLoaded**(): `void`

#### Returns

`void`

___

### checkManager

▸ **checkManager**(`httpRequest`): `void`

检查登录的管理员信息是否已变更

#### Parameters

| Name | Type |
| :------ | :------ |
| `httpRequest` | `any` |

#### Returns

`void`

___

### checkResponseState

▸ **checkResponseState**(`status`, `responseJson`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `status` | `number` |
| `responseJson` | `string` |

#### Returns

`void`

___

### checkRestart

▸ **checkRestart**(`httpRequest`): `void`

检测系统是否正在更新

#### Parameters

| Name | Type |
| :------ | :------ |
| `httpRequest` | `any` |

#### Returns

`void`

___

### checkVersion

▸ **checkVersion**(`httpRequest`): `void`

检查是否有新版本

#### Parameters

| Name | Type |
| :------ | :------ |
| `httpRequest` | `any` |

#### Returns

`void`

___

### checkWaitNotice

▸ **checkWaitNotice**(`params`, `callBack`): `void`

检查系统待办事项

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(result.success, result.data); |

#### Returns

`void`

___

### clearEntity

▸ **clearEntity**(`params`, `callBack`): `void`

清空实体表格中的数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(true, result.message) |

#### Returns

`void`

___

### clearRepeatEntity

▸ **clearRepeatEntity**(`params`, `callBack`): `void`

清空实体表格中重复的数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(true, result.message) |

#### Returns

`void`

___

### clearWaitNotice

▸ **clearWaitNotice**(`callBack`): `void`

清除系统待办事项

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callBack` | `any` | 回调函数 callBack(result.success, result.message, result.data); |

#### Returns

`void`

___

### clickVerify

▸ **clickVerify**(`loginName`, `clickX`, `clickY`, `captchaKey`, `callBack`): `void`

点击验证

#### Parameters

| Name | Type |
| :------ | :------ |
| `loginName` | `string` |
| `clickX` | `number` |
| `clickY` | `number` |
| `captchaKey` | `string` |
| `callBack` | `any` |

#### Returns

`void`

___

### computeUrl

▸ **computeUrl**(): `string`

计算字段属性接口

#### Returns

`string`

___

### copyEntity

▸ **copyEntity**(`params`, `callBack`): `void`

复制实体数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(true, result.message) |

#### Returns

`void`

___

### countReport

▸ **countReport**(`callBack`): `void`

统计上报系统的问题

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callBack` | `any` | 回调函数 callBack(result.success, result.data); |

#### Returns

`void`

___

### deleteAttach

▸ **deleteAttach**(`params`, `callBack`): `void`

删除附件地址

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(true, result.message) |

#### Returns

`void`

___

### deleteEntity

▸ **deleteEntity**(`params`, `callBack`): `void`

删除实体数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(result.success, result.message) |

#### Returns

`void`

___

### deleteExtConfig

▸ **deleteExtConfig**(`key`, `type`, `callBack?`): `void`

删除和ExtJs相关的系统配置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `any` | 配置的key |
| `type` | `any` | 配置类型 |
| `callBack?` | `any` | 回调函数 callBack(true, result.message) |

#### Returns

`void`

___

### deleteExtConfigUrl

▸ **deleteExtConfigUrl**(): `string`

删除ext操作的配置

#### Returns

`string`

___

### deleteSystemConfig

▸ **deleteSystemConfig**(`callBack`): `void`

删除系统配置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callBack` | `any` | 回调函数 callBack(result.success, result.message) |

#### Returns

`void`

___

### destroyList

▸ **destroyList**(`storeId`): `void`

销毁list的sql语句

#### Parameters

| Name | Type |
| :------ | :------ |
| `storeId` | `any` |

#### Returns

`void`

___

### doneWaitNotice

▸ **doneWaitNotice**(`noticeId`, `callBack`): `void`

标记待办事项已完成

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `noticeId` | `any` | 待办事项ID |
| `callBack` | `any` | 回调函数 callBack(result.success, result.message, result.data); |

#### Returns

`void`

___

### downData

▸ **downData**(`params`, `callBack`): `void`

下载实体数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(result.success, result.message, result.data); |

#### Returns

`void`

___

### downSystemConfigUrl

▸ **downSystemConfigUrl**(): `string`

下载系统配置的接口

#### Returns

`string`

___

### entityListUrl

▸ **entityListUrl**(): `string`

获取实体数据列表

#### Returns

`string`

___

### excelModule

▸ **excelModule**(`params`, `callBack`): `void`

获取实体表格数据导入的excel模板

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(true, result.data, result.message) |

#### Returns

`void`

___

### exportExcel

▸ **exportExcel**(`params`, `callBack`): `void`

导出数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(true, result.data, result.message) |

#### Returns

`void`

___

### getApiHost

▸ **getApiHost**(): `string`

#### Returns

`string`

___

### getChangelogUrl

▸ **getChangelogUrl**(): `string`

获取系统更新日志markdown文件的地址

#### Returns

`string`

___

### getDataboard

▸ **getDataboard**(`callBack`): `void`

获取数据看板

#### Parameters

| Name | Type |
| :------ | :------ |
| `callBack` | `any` |

#### Returns

`void`

___

### getGlobalParams

▸ **getGlobalParams**(): `Object`

#### Returns

`Object`

___

### getGoogleBindUrl

▸ **getGoogleBindUrl**(): `string`

获取谷歌绑定的二维码下载地址

#### Returns

`string`

___

### getIcon

▸ **getIcon**(`iconName`, `color?`): `string`

获取服务器web/icons文件下的icon接口路径

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `iconName` | `any` | 图片名称 |
| `color?` | `any` | 图片颜色，针对.svg格式有效 |

#### Returns

`string`

___

### getSessionId

▸ **getSessionId**(): `string`

#### Returns

`string`

___

### globalSearchUrl

▸ **globalSearchUrl**(): `string`

全局搜索地址

#### Returns

`string`

___

### googleReset

▸ **googleReset**(`managerId`, `callBack`): `void`

谷歌验证码重置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `managerId` | `any` |  |
| `callBack` | `any` | 回调函数 |

#### Returns

`void`

___

### googleVerify

▸ **googleVerify**(`code`, `callBack`): `void`

谷歌验证码验证

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `code` | `any` | 验证码 |
| `callBack` | `any` | 回调函数 |

#### Returns

`void`

___

### idleUrl

▸ **idleUrl**(): `string`

后台心跳的接口地址

#### Returns

`string`

___

### importEntityExcelUrl

▸ **importEntityExcelUrl**(): `string`

实体导入数据接口地址

#### Returns

`string`

___

### initExtAjaxConfig

▸ **initExtAjaxConfig**(): `void`

#### Returns

`void`

___

### initJQueryConfig

▸ **initJQueryConfig**(): `void`

#### Returns

`void`

___

### isSilenceRequest

▸ **isSilenceRequest**(): `boolean`

是否是静默请求

#### Returns

`boolean`

**`See`**

FastExt.Server.silence

___

### loadEntityDataUrl

▸ **loadEntityDataUrl**(): `string`

上传实体数据接口

#### Returns

`string`

___

### loadMonitor

▸ **loadMonitor**(`callBack`): `void`

获取系统服务器的监控信息

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callBack` | `any` | 回调函数 callBack(result.success, result.data); |

#### Returns

`void`

___

### loadSource

▸ **loadSource**(`entityCode`, `callBack`): `void`

获取entityCode的源代码

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityCode` | `any` |
| `callBack` | `any` |

#### Returns

`void`

___

### loginUrl

▸ **loginUrl**(): `string`

后台登录的接口地址

#### Returns

`string`

___

### logout

▸ **logout**(`message?`): `void`

退出后台管理登录

#### Parameters

| Name | Type |
| :------ | :------ |
| `message?` | `any` |

#### Returns

`void`

___

### rebackEntity

▸ **rebackEntity**(`params`, `callBack`): `void`

还原实体回收站中的数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(result.success, result.message) |

#### Returns

`void`

___

### replaceDBEntity

▸ **replaceDBEntity**(`params`, `callBack`): `void`

批量更新到数据库中

#### Parameters

| Name | Type |
| :------ | :------ |
| `params` | `any` |
| `callBack` | `any` |

#### Returns

`void`

___

### reportException

▸ **reportException**(`message`): `void`

上报异常

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `any` |

#### Returns

`void`

___

### safeToObj

▸ **safeToObj**(`responseText`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `responseText` | `string` |

#### Returns

`any`

___

### saveCache

▸ **saveCache**(`source`, `callBack`): `void`

保存原数据到缓存中

#### Parameters

| Name | Type |
| :------ | :------ |
| `source` | `any` |
| `callBack` | `any` |

#### Returns

`void`

___

### saveExtConfig

▸ **saveExtConfig**(`key`, `type`, `value`, `callBack?`, `otherParams?`): `void`

保存和ExtJs相关的系统配置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `any` | 配置的key |
| `type` | `any` | 配置的类型 |
| `value` | `any` | 配置的数据 |
| `callBack?` | `any` | 回调函数 |
| `otherParams?` | `any` | 其他附带参数 callBack(true, result.message) |

#### Returns

`void`

___

### saveExtConfigUrl

▸ **saveExtConfigUrl**(): `string`

保存ext的操作配置

#### Returns

`string`

___

### saveSource

▸ **saveSource**(`entityCode`, `content`, `callBack`): `void`

保存entityCode源码

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityCode` | `any` |
| `content` | `any` |
| `callBack` | `any` |

#### Returns

`void`

___

### saveSystemConfig

▸ **saveSystemConfig**(`configKey`, `configValue`): `void`

保存系统配置

#### Parameters

| Name | Type |
| :------ | :------ |
| `configKey` | `any` |
| `configValue` | `any` |

#### Returns

`void`

___

### saveSystemConfigUrl

▸ **saveSystemConfigUrl**(): `string`

#### Returns

`string`

___

### setSilence

▸ **setSilence**(`value`): `void`

设置请求是否为静默请求

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `boolean` |

#### Returns

`void`

**`See`**

FastExt.Server.silence

___

### showCaptchaUrl

▸ **showCaptchaUrl**(): `string`

获取验证码图片的接口地址

#### Returns

`string`

___

### showColumns

▸ **showColumns**(`entityCode`, `callBack`, `params?`): `void`

获取实体类对应grid保存的列记录

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entityCode` | `any` | 实体编号 |
| `callBack` | `any` | 回调函数 callBack(true, result.data.configValue, result.message) |
| `params?` | `any` | 更多参数 |

#### Returns

`void`

___

### showConfigUrl

▸ **showConfigUrl**(): `string`

获取系统配置接口地址

#### Returns

`string`

___

### showEcharts

▸ **showEcharts**(`params`, `callBack`): `void`

获取图表echarts的配置json数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(result.success, result.message); |

#### Returns

`void`

___

### showEnumsUrl

▸ **showEnumsUrl**(): `string`

获取枚举列表

#### Returns

`string`

___

### showExtConfig

▸ **showExtConfig**(`key`, `type`, `callBack`): `void`

获取和ExtJs相关的系统配置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `any` | 配置的key |
| `type` | `any` | 配置类型 |
| `callBack` | `any` | 回调函数 callBack(true, result.data.configValue, result.message) |

#### Returns

`void`

___

### showExtConfigUrl

▸ **showExtConfigUrl**(): `string`

获取ext操作的配置

#### Returns

`string`

___

### showMenuColumnUrl

▸ **showMenuColumnUrl**(): `string`

获取功能菜单和功能列

#### Returns

`string`

___

### showPowerMenusUrl

▸ **showPowerMenusUrl**(): `string`

获取菜单权限列表

#### Returns

`string`

___

### showSystemConfig

▸ **showSystemConfig**(`callBack`): `void`

获取系统配置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callBack` | `any` | 回调函数 callBack(true, result.data, result.message) |

#### Returns

`void`

___

### updateAllLayer

▸ **updateAllLayer**(`callBack`): `void`

更新系统所有表格的数据层级权限值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callBack` | `any` | 回调函数 callBack(result.success, result.message); |

#### Returns

`void`

___

### updateAllSame

▸ **updateAllSame**(`callBack`): `void`

更新系统数据绑定

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callBack` | `any` | 回调函数 callBack(result.success, result.message); |

#### Returns

`void`

___

### updateDBEntity

▸ **updateDBEntity**(`params`, `callBack`): `void`

批量更新到数据库中

#### Parameters

| Name | Type |
| :------ | :------ |
| `params` | `any` |
| `callBack` | `any` |

#### Returns

`void`

___

### updateEntity

▸ **updateEntity**(`params`, `callBack`): `void`

提交更新FastEntity实体数据

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数：callBack(true, result.message) |

#### Returns

`void`

___

### updateLayer

▸ **updateLayer**(`params`, `callBack`): `void`

更新指定实体表格的数据层级权限值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(result.success, result.message); |

#### Returns

`void`

___

### updateSame

▸ **updateSame**(`params`, `callBack`): `void`

更新指定实体表格的关系相同列值

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `params` | `any` | 接口参数 |
| `callBack` | `any` | 回调函数 callBack(result.success, result.message); |

#### Returns

`void`

___

### uploadUrl

▸ **uploadUrl**(): `string`

上传文件

#### Returns

`string`

___

### validOperateUrl

▸ **validOperateUrl**(): `string`

安全验证的接口地址

#### Returns

`string`

___

### zipFile

▸ **zipFile**(`params`, `callBack`): `void`

压缩文件

#### Parameters

| Name | Type |
| :------ | :------ |
| `params` | `any` |
| `callBack` | `any` |

#### Returns

`void`
