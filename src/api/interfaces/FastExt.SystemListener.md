[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / SystemListener

# Interface: SystemListener

[FastExt](../modules/FastExt.md).SystemListener

系统事件接口

## Table of contents

### Methods

- [onAfterInitSystem](FastExt.SystemListener.md#onafterinitsystem)
- [onAfterManagerLogin](FastExt.SystemListener.md#onaftermanagerlogin)
- [onBeforeEditorField](FastExt.SystemListener.md#onbeforeeditorfield)
- [onBeforeManagerLogin](FastExt.SystemListener.md#onbeforemanagerlogin)
- [onEntityGetColumnRender](FastExt.SystemListener.md#onentitygetcolumnrender)
- [onEntityGetEditorField](FastExt.SystemListener.md#onentitygeteditorfield)
- [onExtCreateFilter](FastExt.SystemListener.md#onextcreatefilter)
- [onInitLinkFieldDefaultValue](FastExt.SystemListener.md#oninitlinkfielddefaultvalue)
- [onInitLoginPanel](FastExt.SystemListener.md#oninitloginpanel)
- [onInitSystemHeaderItems](FastExt.SystemListener.md#oninitsystemheaderitems)
- [onInitSystemWelcomeItems](FastExt.SystemListener.md#oninitsystemwelcomeitems)
- [onShowManagerDataLayer](FastExt.SystemListener.md#onshowmanagerdatalayer)
- [onShowManagerInfo](FastExt.SystemListener.md#onshowmanagerinfo)
- [onShowRoleDataLayer](FastExt.SystemListener.md#onshowroledatalayer)
- [onSystemNoticeShow](FastExt.SystemListener.md#onsystemnoticeshow)
- [onSystemReady](FastExt.SystemListener.md#onsystemready)

## Methods

### onAfterInitSystem

▸ **onAfterInitSystem**(): `void`

系统初始化系统结束后，注意：此系统初始化并不是系统布局完成

#### Returns

`void`

___

### onAfterManagerLogin

▸ **onAfterManagerLogin**(`callback`): `void`

当后台管理员登录成功后触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | `any` |

#### Returns

`void`

**`Example`**

```ts
function(callback){
    //do anything
    //必须主动调用，然后继续下步执行
    callback();
}
```

___

### onBeforeEditorField

▸ **onBeforeEditorField**(`field`, `record`): `boolean`

修改字段前 触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `field` | `any` |
| `record` | `any` |

#### Returns

`boolean`

true允许修改，false拦截修改

___

### onBeforeManagerLogin

▸ **onBeforeManagerLogin**(`params`, `callback`): `void`

当后台管理员登录前触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `params` | `any` |
| `callback` | `any` |

#### Returns

`void`

**`Example`**

```ts
function(params,callback){
    //do anything
    //必须主动调用，然后继续下步执行
    callback();
}
```

___

### onEntityGetColumnRender

▸ **onEntityGetColumnRender**(`entity`, `attrName`): `any`

当执行entity对象里的getColumnRender方法时触发【注意，此事件仅在调用 FastExt.Entity.getColumnRender】

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | entity对象 |
| `attrName` | `string` | 属性名 |

#### Returns

`any`

函数对象function【返回非null时，拦截entity的方法，反之不拦截】

___

### onEntityGetEditorField

▸ **onEntityGetEditorField**(`entity`, `attrName`): `any`

当执行entity对象里的getEditorField方法时触发【注意，此事件仅在调用 FastExt.Entity.getEditorField】

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `entity` | `any` | entity对象 |
| `attrName` | `string` | 属性名 |

#### Returns

`any`

字段对象【返回非null时，拦截entity的方法，反之不拦截】

___

### onExtCreateFilter

▸ **onExtCreateFilter**(`key`, `info`): `void`

当执行Ext.create方法时触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |
| `info` | [`ComponentInvokeInfo`](../classes/FastExt.ComponentInvokeInfo.md) |

#### Returns

`void`

___

### onInitLinkFieldDefaultValue

▸ **onInitLinkFieldDefaultValue**(`cmb`): `any`

当初始化linkfield组件的值时触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `cmb` | `any` |

#### Returns

`any`

默认值返回配置对象

___

### onInitLoginPanel

▸ **onInitLoginPanel**(`items`, `windowConfig`): `void`

当初始化后台登录面板时触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `items` | `any` |
| `windowConfig` | `any` |

#### Returns

`void`

**`Example`**

```ts
function(items,windowConfig){}
```

___

### onInitSystemHeaderItems

▸ **onInitSystemHeaderItems**(`headHandler`): `void`

当初始化系统头部组件时触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `headHandler` | [`EventHeadHandler`](FastExt.EventHeadHandler.md) |

#### Returns

`void`

___

### onInitSystemWelcomeItems

▸ **onInitSystemWelcomeItems**(`indexHandler`): `void`

当初始化【首页】的欢迎面板的组件时触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `indexHandler` | [`EventWelcomeHandler`](FastExt.EventWelcomeHandler.md) |

#### Returns

`void`

___

### onShowManagerDataLayer

▸ **onShowManagerDataLayer**(`manager`): `void`

当点击管理员数据权限配置时触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `manager` | `any` |

#### Returns

`void`

___

### onShowManagerInfo

▸ **onShowManagerInfo**(`info`): `void`

当点击右上角管理员按钮查看管理员信息时触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `info` | `any` |

#### Returns

`void`

___

### onShowRoleDataLayer

▸ **onShowRoleDataLayer**(`role`): `void`

当点击管理员角色数据权限配置时触发

#### Parameters

| Name | Type |
| :------ | :------ |
| `role` | `any` |

#### Returns

`void`

___

### onSystemNoticeShow

▸ **onSystemNoticeShow**(): `void`

当在左下角弹出系统通知消息框时触发

#### Returns

`void`

___

### onSystemReady

▸ **onSystemReady**(): `void`

系统渲染完毕，准备就绪

#### Returns

`void`
