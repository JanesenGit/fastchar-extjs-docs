[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / Dialog

# Class: Dialog

[FastExt](../modules/FastExt.md).Dialog

全局弹框相关操作

## Table of contents

### Constructors

- [constructor](FastExt.Dialog.md#constructor)

### Methods

- [hideWait](FastExt.Dialog.md#hidewait)
- [showAlert](FastExt.Dialog.md#showalert)
- [showCode](FastExt.Dialog.md#showcode)
- [showConfirm](FastExt.Dialog.md#showconfirm)
- [showContent](FastExt.Dialog.md#showcontent)
- [showDeleteDataAlert](FastExt.Dialog.md#showdeletedataalert)
- [showEditor](FastExt.Dialog.md#showeditor)
- [showEditorHtml](FastExt.Dialog.md#showeditorhtml)
- [showException](FastExt.Dialog.md#showexception)
- [showFastColorPicker](FastExt.Dialog.md#showfastcolorpicker)
- [showFastDatePicker](FastExt.Dialog.md#showfastdatepicker)
- [showFormatJson](FastExt.Dialog.md#showformatjson)
- [showHtml](FastExt.Dialog.md#showhtml)
- [showImage](FastExt.Dialog.md#showimage)
- [showJson](FastExt.Dialog.md#showjson)
- [showLink](FastExt.Dialog.md#showlink)
- [showLottie](FastExt.Dialog.md#showlottie)
- [showMusic](FastExt.Dialog.md#showmusic)
- [showPrompt](FastExt.Dialog.md#showprompt)
- [showSafeHtml](FastExt.Dialog.md#showsafehtml)
- [showSql](FastExt.Dialog.md#showsql)
- [showText](FastExt.Dialog.md#showtext)
- [showTip](FastExt.Dialog.md#showtip)
- [showVideo](FastExt.Dialog.md#showvideo)
- [showWait](FastExt.Dialog.md#showwait)
- [showWarning](FastExt.Dialog.md#showwarning)
- [toast](FastExt.Dialog.md#toast)

## Constructors

### constructor

• **new Dialog**(): [`Dialog`](FastExt.Dialog.md)

#### Returns

[`Dialog`](FastExt.Dialog.md)

## Methods

### hideWait

▸ **hideWait**(): `void`

关闭等待框

#### Returns

`void`

___

### showAlert

▸ **showAlert**(`title`, `message`, `callback?`, `modal?`, `animateDisable?`): `void`

弹出Alert对话框

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `title` | `string` | 标题 |
| `message` | `string` | 消息 |
| `callback?` | `any` | 点击按钮的回调函数 Ext.MessageBox.fn ,点击按钮对应返回值 确定：ok |
| `modal?` | `boolean` | 是否有背景阴影层 |
| `animateDisable?` | `boolean` | 禁用弹框动画 |

#### Returns

`void`

___

### showCode

▸ **showCode**(`obj`, `value`, `linenumber?`, `lang?`): `void`

显示代码内容

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框动画对象 |
| `value` | `string` | 代码内容 |
| `linenumber?` | `boolean` | 是否显示代码行数 |
| `lang?` | `string` | prettify指定开发语言类型[https://github.com/googlearchive/code-prettify/blob/master/docs/getting_started.md](https://github.com/googlearchive/code-prettify/blob/master/docs/getting_started.md) |

#### Returns

`void`

___

### showConfirm

▸ **showConfirm**(`title`, `message`, `callback`, `config?`): `void`

弹出确认对话框

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `title` | `string` | 标题 |
| `message` | `string` | 消息 |
| `callback` | `any` | 回调函数 ,点击按钮对应返回值 确定：yes 取消：no |
| `config?` | `any` | 更多配置，例如配置按钮文字：{yes: "确定",no: "取消"} |

#### Returns

`void`

___

### showContent

▸ **showContent**(`obj`, `title`, `text`, `modal?`): `void`

显示纯文本内容

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框动画对象 |
| `title` | `string` | 标题 |
| `text` | `string` | 内容 |
| `modal?` | `boolean` | 模式窗口 |

#### Returns

`void`

___

### showDeleteDataAlert

▸ **showDeleteDataAlert**(`title`, `message`, `confirmCallBack`, `confirmButtonText?`): `void`

弹出删除数据等无法撤销的操作确认框

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `title` | `string` | 标题 |
| `message` | `string` | 消息 |
| `confirmCallBack` | `any` | 确认后回调 |
| `confirmButtonText?` | `string` | 确认按钮的文字，默认：删除 |

#### Returns

`void`

___

### showEditor

▸ **showEditor**(`obj`, `title`, `callBack`, `defaultValue?`): `void`

弹出大文本编辑框

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框对象 |
| `title` | `string` | 标题 |
| `callBack` | `any` | 回调函数 callBack(Ext.getCmp(areaId).getValue()); |
| `defaultValue?` | `string` | 默认值 |

#### Returns

`void`

___

### showEditorHtml

▸ **showEditorHtml**(`obj`, `title`, `content`): `void`

显示编辑器生成的网页内容

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框动画对象 |
| `title` | `string` | 标题 |
| `content` | `string` | 内容 |

#### Returns

`void`

___

### showException

▸ **showException**(`e`, `from?`): `void`

弹出异常信息

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `e` | `any` | 异常对象 |
| `from?` | `string` | 来自功能 |

#### Returns

`void`

___

### showFastColorPicker

▸ **showFastColorPicker**(`obj`, `defaultValue`, `onColorChange`): `any`

弹出颜色选择控件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 需要弹出的目标控件 |
| `defaultValue` | `string` | 默认颜色 |
| `onColorChange` | `any` | 颜色变化的监听 |

#### Returns

`any`

Ext.Promise

___

### showFastDatePicker

▸ **showFastDatePicker**(`obj`, `defaultValue`, `dateFormat`): `any`

弹出日期时间选择控件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 需要弹出的目标控件 |
| `defaultValue` | `string` | 默认日期时间 |
| `dateFormat` | `string` | 日期时间的格式 |

#### Returns

`any`

Ext.Promise

___

### showFormatJson

▸ **showFormatJson**(`obj`, `value`): `void`

格式化显示json字符串

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `value` | `string` |

#### Returns

`void`

___

### showHtml

▸ **showHtml**(`obj`, `title`, `content`, `modal?`): `any`

弹窗显示网页内容

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框动画对象 |
| `title` | `string` | 标题 |
| `content` | `string` | 内容 |
| `modal?` | `boolean` | 模式窗口 |

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
| `url` | `string` | 图片地址 String或JsonArray |
| `callBack` | `any` | 回调函数 |
| `modal?` | `boolean` | 是否有背景阴影层 |

#### Returns

`void`

___

### showJson

▸ **showJson**(`obj`, `title`, `value`): `void`

格式化显示json字符串

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框对象 |
| `title` | `string` | 标题 |
| `value` | `string` | 弹框内容 |

#### Returns

`void`

___

### showLink

▸ **showLink**(`obj`, `title`, `url`, `config`, `loadDoneCallBack?`): `void`

弹窗显示url网页内容

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框动画对象 |
| `title` | `string` | 标题 |
| `url` | `string` | 网页地址 |
| `config` | `any` | 扩展Ext.window.Window的配置 json对象 |
| `loadDoneCallBack?` | `any` | 页面加载完成后的回调 |

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
| `jsonPath` | `string` | lottie的json文件路径 |

#### Returns

`void`

___

### showMusic

▸ **showMusic**(`obj`, `musicUrl`): `void`

播放音乐

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹窗动画对象 |
| `musicUrl` | `string` | 音乐路径 |

#### Returns

`void`

___

### showPrompt

▸ **showPrompt**(`title`, `message`, `callback`, `multiline?`, `value?`): `void`

弹出确认对话框

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `title` | `string` | 标题 |
| `message` | `string` | 消息 |
| `callback` | `any` | 回调函数 ,function(btn,val){} btn的值确定：ok 取消：no |
| `multiline?` | `boolean` | 是否多行输入 |
| `value?` | `string` | 默认值 |

#### Returns

`void`

___

### showSafeHtml

▸ **showSafeHtml**(`obj`, `title`, `content`, `modal?`): `any`

弹窗安全的显示网页内容

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框动画对象 |
| `title` | `string` | 标题 |
| `content` | `string` | 内容 |
| `modal?` | `boolean` | 模式窗口 |

#### Returns

`any`

___

### showSql

▸ **showSql**(`obj`, `value`): `void`

格式化显示SQL语句内容

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框动画对象 |
| `value` | `string` | sql代码内容 |

#### Returns

`void`

___

### showText

▸ **showText**(`obj`, `icon`, `title`, `text`, `modal?`): `void`

显示纯文本内容

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框动画对象 |
| `icon` | `string` | 窗体图标 |
| `title` | `string` | 标题 |
| `text` | `string` | 内容 |
| `modal?` | `boolean` | 模式窗口 |

#### Returns

`void`

___

### showTip

▸ **showTip**(`title`, `message`, `callback`): `void`

显示弹框提醒，允许用户勾选下次不在弹出的功能

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `title` | `string` |  |
| `message` | `string` |  |
| `callback` | `any` | 点击确定后的回调 |

#### Returns

`void`

___

### showVideo

▸ **showVideo**(`obj`, `videoUrl`): `void`

播放视频，使用插件：https://dplayer.diygod.dev/zh/guide.html#special-thanks

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | 弹框动画对象 |
| `videoUrl` | `string` | 视频地址 |

#### Returns

`void`

___

### showWait

▸ **showWait**(`message`): `void`

显示等待窗口

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `message` | `string` | 等待的消息 |

#### Returns

`void`

___

### showWarning

▸ **showWarning**(`message`, `callback`): `void`

弹出系统警告窗体

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `callback` | `any` |

#### Returns

`void`

___

### toast

▸ **toast**(`message`): `void`

显示自动消失的消息

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `message` | `string` | 消息内容 |

#### Returns

`void`
