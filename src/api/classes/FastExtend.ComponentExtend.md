[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExtend](../modules/FastExtend.md) / ComponentExtend

# Class: ComponentExtend

[FastExtend](../modules/FastExtend.md).ComponentExtend

Ext.Component扩展

**`Define`**

使用Ext.Component对象调用以下方法或属性

**`Example`**

```ts
button.help
```

## Table of contents

### Constructors

- [constructor](FastExtend.ComponentExtend.md#constructor)

### Properties

- [disabledLoadMask](FastExtend.ComponentExtend.md#disabledloadmask)
- [disabledLoadMaskOnce](FastExtend.ComponentExtend.md#disabledloadmaskonce)
- [help](FastExtend.ComponentExtend.md#help)
- [helpAnchor](FastExtend.ComponentExtend.md#helpanchor)
- [helpAnchorOffset](FastExtend.ComponentExtend.md#helpanchoroffset)
- [helpType](FastExtend.ComponentExtend.md#helptype)
- [iframePanel](FastExtend.ComponentExtend.md#iframepanel)

### Methods

- [getEditorMenu](FastExtend.ComponentExtend.md#geteditormenu)
- [\_\_onLoaded](FastExtend.ComponentExtend.md#__onloaded)

## Constructors

### constructor

• **new ComponentExtend**(): [`ComponentExtend`](FastExtend.ComponentExtend.md)

#### Returns

[`ComponentExtend`](FastExtend.ComponentExtend.md)

## Properties

### disabledLoadMask

• **disabledLoadMask**: `boolean`

是否禁用loadMask

___

### disabledLoadMaskOnce

• **disabledLoadMaskOnce**: `boolean`

是否禁用一次loadMask ，当LoadMask 使用此属性一次 后将被设置为false

___

### help

• **help**: `string`

组件功能的使用介绍，配置后，默认右键鼠标即可查看内容
[FastEnum.HelpEnumType](../enums/FastEnum.HelpEnumType.md)

___

### helpAnchor

• **helpAnchor**: `string`

帮助提示语锚点位置，默认系统自动计算
[FastEnum.TooltipAnchorType](../enums/FastEnum.TooltipAnchorType.md)

___

### helpAnchorOffset

• **helpAnchorOffset**: `number` = `-1`

帮助提示语锚点位置偏移量，默认-1，系统自动计算

___

### helpType

• **helpType**: `number`

组件功能提示操作类型，默认，右键鼠标
[FastEnum.HelpEnumType](../enums/FastEnum.HelpEnumType.md)

___

### iframePanel

• **iframePanel**: `boolean` = `false`

标识是否为嵌入iframe标签的组件
<br/>
如果配置属性值为true，则在拖拽或改变控件大小时会禁用本组件，避免鼠标事件丢失问题

## Methods

### getEditorMenu

▸ **getEditorMenu**(): `any`

获取当前组件弹出编辑状态的菜单对象

#### Returns

`any`

___

### \_\_onLoaded

▸ **__onLoaded**(): `void`

#### Returns

`void`
