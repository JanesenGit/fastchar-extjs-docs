[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / PluginLoader

# Class: PluginLoader

[FastExt](../modules/FastExt.md).PluginLoader

## Table of contents

### Constructors

- [constructor](FastExt.PluginLoader.md#constructor)

### Properties

- [loadedPluginMap](FastExt.PluginLoader.md#loadedpluginmap)

### Methods

- [loadPlugins](FastExt.PluginLoader.md#loadplugins)

## Constructors

### constructor

• **new PluginLoader**(): [`PluginLoader`](FastExt.PluginLoader.md)

#### Returns

[`PluginLoader`](FastExt.PluginLoader.md)

## Properties

### loadedPluginMap

▪ `Static` **loadedPluginMap**: `Object` = `{}`

## Methods

### loadPlugins

▸ **loadPlugins**(`pluginCode`, `srcPaths`, `callBack`): `void`

加载插件的文件

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `pluginCode` | `string` | 插件标识 |
| `srcPaths` | `any`[] | js或css文件地址 |
| `callBack` | `any` | 回调函数 |

#### Returns

`void`
