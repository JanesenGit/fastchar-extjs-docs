[FastChar-ExtJs文档](../README.md) / [Exports](../modules.md) / [FastExt](../modules/FastExt.md) / DesktopLayout

# Class: DesktopLayout

[FastExt](../modules/FastExt.md).DesktopLayout

桌面布局方式展示

## Table of contents

### Constructors

- [constructor](FastExt.DesktopLayout.md#constructor)

### Properties

- [desktopAllMenusInfo](FastExt.DesktopLayout.md#desktopallmenusinfo)
- [desktopButtonMaxWidth](FastExt.DesktopLayout.md#desktopbuttonmaxwidth)
- [desktopContainer](FastExt.DesktopLayout.md#desktopcontainer)
- [desktopInitFinish](FastExt.DesktopLayout.md#desktopinitfinish)
- [desktopPanel](FastExt.DesktopLayout.md#desktoppanel)
- [disabledMenuPathClick](FastExt.DesktopLayout.md#disabledmenupathclick)
- [disabledRecordMenu](FastExt.DesktopLayout.md#disabledrecordmenu)
- [folderColor](FastExt.DesktopLayout.md#foldercolor)
- [folderIcon](FastExt.DesktopLayout.md#foldericon)
- [lastActiveMenuId](FastExt.DesktopLayout.md#lastactivemenuid)
- [lastSelectDesktopImageId](FastExt.DesktopLayout.md#lastselectdesktopimageid)
- [muuriContainerIdIndex](FastExt.DesktopLayout.md#muuricontaineridindex)
- [muuriDragging](FastExt.DesktopLayout.md#muuridragging)
- [muuriGridContainers](FastExt.DesktopLayout.md#muurigridcontainers)
- [startMenu](FastExt.DesktopLayout.md#startmenu)

### Methods

- [activeToolbarButton](FastExt.DesktopLayout.md#activetoolbarbutton)
- [addDesktopButton](FastExt.DesktopLayout.md#adddesktopbutton)
- [addDesktopToolbarButton](FastExt.DesktopLayout.md#adddesktoptoolbarbutton)
- [addDesktopToolbarFixedButton](FastExt.DesktopLayout.md#adddesktoptoolbarfixedbutton)
- [buildDesktopItem](FastExt.DesktopLayout.md#builddesktopitem)
- [buildDesktopItemPanel](FastExt.DesktopLayout.md#builddesktopitempanel)
- [buildFolderMenu](FastExt.DesktopLayout.md#buildfoldermenu)
- [buildToolbarButton](FastExt.DesktopLayout.md#buildtoolbarbutton)
- [checkDesktopButton](FastExt.DesktopLayout.md#checkdesktopbutton)
- [checkDesktopToolbarFixedButton](FastExt.DesktopLayout.md#checkdesktoptoolbarfixedbutton)
- [checkMenuByUserFolder](FastExt.DesktopLayout.md#checkmenubyuserfolder)
- [checkMenuFolder](FastExt.DesktopLayout.md#checkmenufolder)
- [checkMenuInFolder](FastExt.DesktopLayout.md#checkmenuinfolder)
- [checkMenuLocked](FastExt.DesktopLayout.md#checkmenulocked)
- [checkMuuriGridContainer](FastExt.DesktopLayout.md#checkmuurigridcontainer)
- [checkSystemLockedFolderMenu](FastExt.DesktopLayout.md#checksystemlockedfoldermenu)
- [closeAllDesktopWin](FastExt.DesktopLayout.md#closealldesktopwin)
- [closeAllToolbarMenuButton](FastExt.DesktopLayout.md#closealltoolbarmenubutton)
- [closeOtherToolbarMenuButton](FastExt.DesktopLayout.md#closeothertoolbarmenubutton)
- [closeToolbarMenuButton](FastExt.DesktopLayout.md#closetoolbarmenubutton)
- [deactiveToolbarButton](FastExt.DesktopLayout.md#deactivetoolbarbutton)
- [getAllDesktopMenuInfo](FastExt.DesktopLayout.md#getalldesktopmenuinfo)
- [getDesktopButtonMaxWidth](FastExt.DesktopLayout.md#getdesktopbuttonmaxwidth)
- [getDesktopButtonTitleMaxWidth](FastExt.DesktopLayout.md#getdesktopbuttontitlemaxwidth)
- [getDesktopToolbarButton](FastExt.DesktopLayout.md#getdesktoptoolbarbutton)
- [getDesktopToolbarButtonByGroup](FastExt.DesktopLayout.md#getdesktoptoolbarbuttonbygroup)
- [getFolderChildMenus](FastExt.DesktopLayout.md#getfolderchildmenus)
- [getInsertFixedButtonIndex](FastExt.DesktopLayout.md#getinsertfixedbuttonindex)
- [getInsertMenuButtonIndex](FastExt.DesktopLayout.md#getinsertmenubuttonindex)
- [getMenu](FastExt.DesktopLayout.md#getmenu)
- [getMenuByMuuriGridItem](FastExt.DesktopLayout.md#getmenubymuurigriditem)
- [getMenuPath](FastExt.DesktopLayout.md#getmenupath)
- [getSystemHeaderPanel](FastExt.DesktopLayout.md#getsystemheaderpanel)
- [getTopDesktopWindow](FastExt.DesktopLayout.md#gettopdesktopwindow)
- [getWindowMenu](FastExt.DesktopLayout.md#getwindowmenu)
- [hasWindowMenu](FastExt.DesktopLayout.md#haswindowmenu)
- [hideAllDesktopWin](FastExt.DesktopLayout.md#hidealldesktopwin)
- [hideDeleteFolder](FastExt.DesktopLayout.md#hidedeletefolder)
- [outDesktopMenuFolder](FastExt.DesktopLayout.md#outdesktopmenufolder)
- [recordMenu](FastExt.DesktopLayout.md#recordmenu)
- [refreshActiveToolbarButton](FastExt.DesktopLayout.md#refreshactivetoolbarbutton)
- [refreshMuuriGridContainers](FastExt.DesktopLayout.md#refreshmuurigridcontainers)
- [refreshMuuriGridMenuIndex](FastExt.DesktopLayout.md#refreshmuurigridmenuindex)
- [removeAllDesktopToolbarFixedButton](FastExt.DesktopLayout.md#removealldesktoptoolbarfixedbutton)
- [removeDesktopButton](FastExt.DesktopLayout.md#removedesktopbutton)
- [removeDesktopToolbarButton](FastExt.DesktopLayout.md#removedesktoptoolbarbutton)
- [removeDesktopToolbarFixedButton](FastExt.DesktopLayout.md#removedesktoptoolbarfixedbutton)
- [resetWindowMenuAnimTarget](FastExt.DesktopLayout.md#resetwindowmenuanimtarget)
- [restoreMenu](FastExt.DesktopLayout.md#restoremenu)
- [restoreSystemDesktopMenus](FastExt.DesktopLayout.md#restoresystemdesktopmenus)
- [safeGetMenuColor](FastExt.DesktopLayout.md#safegetmenucolor)
- [safeGetMenuIcon](FastExt.DesktopLayout.md#safegetmenuicon)
- [showDeleteFolder](FastExt.DesktopLayout.md#showdeletefolder)
- [showDesktopBackgroundImages](FastExt.DesktopLayout.md#showdesktopbackgroundimages)
- [showEditFolderName](FastExt.DesktopLayout.md#showeditfoldername)
- [showFolder](FastExt.DesktopLayout.md#showfolder)
- [showFolderByMenuId](FastExt.DesktopLayout.md#showfolderbymenuid)
- [showSystemLayout](FastExt.DesktopLayout.md#showsystemlayout)
- [showWindowMenu](FastExt.DesktopLayout.md#showwindowmenu)
- [showWindowMenuById](FastExt.DesktopLayout.md#showwindowmenubyid)
- [showWindowPanel](FastExt.DesktopLayout.md#showwindowpanel)
- [switchMuuriGrid](FastExt.DesktopLayout.md#switchmuurigrid)
- [takeIcon](FastExt.DesktopLayout.md#takeicon)
- [toggleStartMenu](FastExt.DesktopLayout.md#togglestartmenu)
- [updateDesktopMenuButton](FastExt.DesktopLayout.md#updatedesktopmenubutton)
- [updateFolderGridMenu](FastExt.DesktopLayout.md#updatefoldergridmenu)
- [updateMenuInfo](FastExt.DesktopLayout.md#updatemenuinfo)

## Constructors

### constructor

• **new DesktopLayout**(): [`DesktopLayout`](FastExt.DesktopLayout.md)

#### Returns

[`DesktopLayout`](FastExt.DesktopLayout.md)

## Properties

### desktopAllMenusInfo

▪ `Static` **desktopAllMenusInfo**: `Object` = `{}`

___

### desktopButtonMaxWidth

▪ `Static` **desktopButtonMaxWidth**: `any`

___

### desktopContainer

▪ `Static` **desktopContainer**: `any`

___

### desktopInitFinish

▪ `Static` **desktopInitFinish**: `any`

___

### desktopPanel

▪ `Static` **desktopPanel**: `any`

___

### disabledMenuPathClick

▪ `Static` **disabledMenuPathClick**: `boolean` = `false`

___

### disabledRecordMenu

▪ `Static` **disabledRecordMenu**: `boolean` = `false`

___

### folderColor

▪ `Static` **folderColor**: `string` = `"#FFBB00"`

___

### folderIcon

▪ `Static` **folderIcon**: `string` = `"icons/icon_system_file.svg"`

___

### lastActiveMenuId

▪ `Static` **lastActiveMenuId**: `any` = `null`

___

### lastSelectDesktopImageId

▪ `Static` **lastSelectDesktopImageId**: `any` = `null`

___

### muuriContainerIdIndex

▪ `Static` **muuriContainerIdIndex**: `number` = `1`

___

### muuriDragging

▪ `Static` **muuriDragging**: `any`

___

### muuriGridContainers

▪ `Static` **muuriGridContainers**: `any` = `null`

___

### startMenu

▪ `Static` **startMenu**: `any`

## Methods

### activeToolbarButton

▸ **activeToolbarButton**(`menuId`): `void`

激活工具栏的按钮

#### Parameters

| Name | Type |
| :------ | :------ |
| `menuId` | `string` |

#### Returns

`void`

___

### addDesktopButton

▸ **addDesktopButton**(`menu`, `silence?`): `void`

添加快捷方式

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |
| `silence?` | `boolean` |

#### Returns

`void`

___

### addDesktopToolbarButton

▸ **addDesktopToolbarButton**(`sourceMenu`): `void`

添加工具栏菜单按钮

#### Parameters

| Name | Type |
| :------ | :------ |
| `sourceMenu` | `any` |

#### Returns

`void`

___

### addDesktopToolbarFixedButton

▸ **addDesktopToolbarFixedButton**(`sourceMenu`, `silence?`): `void`

固定到桌面工具栏中

#### Parameters

| Name | Type |
| :------ | :------ |
| `sourceMenu` | `any` |
| `silence?` | `any` |

#### Returns

`void`

___

### buildDesktopItem

▸ **buildDesktopItem**(`menu`): `any`

构建桌面图标选项

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`any`

___

### buildDesktopItemPanel

▸ **buildDesktopItemPanel**(`menus`, `alignRight`, `horizontal`, `scrollable`): `Object`

构建桌面布局容器

#### Parameters

| Name | Type |
| :------ | :------ |
| `menus` | `any` |
| `alignRight` | `boolean` |
| `horizontal` | `boolean` |
| `scrollable` | `boolean` |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `addDesktopItem` | (`menu`: `any`) => `void` |
| `addDesktopItems` | (`menus`: `any`) => `void` |
| `alignRight` | `boolean` |
| `anchor` | `string` |
| `bindMuuriGrid` | (`callBack?`: `any`) => `void` |
| `border` | `number` |
| `configMenus` | `any` |
| `desktopItemContainer` | `boolean` |
| `flex` | `number` |
| `getAllDesktopItemMenus` | () => `any`[] |
| `getMuuriGridContainerId` | () => `any` |
| `horizontal` | `boolean` |
| `html` | `string` |
| `layout` | `string` |
| `listeners` | \{ `destroy`: () => `void`  } |
| `listeners.destroy` | () => `void` |
| `muuriGridContainerId` | `string` |
| `muuriGridLayout` | () => `void` |
| `muuriReady` | `boolean` |
| `removeAllDesktopItem` | () => `void` |
| `removeDesktopItem` | (`menu`: `any`) => `void` |
| `xtype` | `string` |

___

### buildFolderMenu

▸ **buildFolderMenu**(`menuText`): `any`

构建文件夹菜单对象

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `menuText` | `string` | 文件夹名 |

#### Returns

`any`

___

### buildToolbarButton

▸ **buildToolbarButton**(`menu`, `fixed`): `any`

构建工具栏上的按钮

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |
| `fixed` | `boolean` |

#### Returns

`any`

___

### checkDesktopButton

▸ **checkDesktopButton**(`menu`): `boolean`

检查菜单是否显示在桌面或含文件夹上显示

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`boolean`

___

### checkDesktopToolbarFixedButton

▸ **checkDesktopToolbarFixedButton**(`menu`): `any`

检测工具栏菜单是否存在

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`any`

___

### checkMenuByUserFolder

▸ **checkMenuByUserFolder**(`menu`): `boolean`

判断是否为用户自己创建文件夹

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`boolean`

___

### checkMenuFolder

▸ **checkMenuFolder**(`menu`): `boolean`

判断菜单是否为文件夹类型

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`boolean`

___

### checkMenuInFolder

▸ **checkMenuInFolder**(`menu`): `boolean`

判断菜单是否存处于文件夹中

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`boolean`

___

### checkMenuLocked

▸ **checkMenuLocked**(`menu`): `boolean`

判断菜单是否已锁定

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`boolean`

___

### checkMuuriGridContainer

▸ **checkMuuriGridContainer**(`x`, `y`): `any`

根据坐标检测所在的muuriGrid容器

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `number` |
| `y` | `number` |

#### Returns

`any`

___

### checkSystemLockedFolderMenu

▸ **checkSystemLockedFolderMenu**(`menu`): `boolean`

判断是否为系统配置菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`boolean`

___

### closeAllDesktopWin

▸ **closeAllDesktopWin**(): `void`

关闭桌面的所有菜单窗口

#### Returns

`void`

___

### closeAllToolbarMenuButton

▸ **closeAllToolbarMenuButton**(): `void`

关闭工具栏上的所有功能按钮

#### Returns

`void`

___

### closeOtherToolbarMenuButton

▸ **closeOtherToolbarMenuButton**(`anchorBtn`, `direction`): `void`

关闭出当前以外的其他菜单按钮

#### Parameters

| Name | Type |
| :------ | :------ |
| `anchorBtn` | `any` |
| `direction` | `any` |

#### Returns

`void`

___

### closeToolbarMenuButton

▸ **closeToolbarMenuButton**(`button`): `void`

关闭工具栏上的按钮

#### Parameters

| Name | Type |
| :------ | :------ |
| `button` | `any` |

#### Returns

`void`

___

### deactiveToolbarButton

▸ **deactiveToolbarButton**(`menuId`): `void`

激活工具栏的按钮

#### Parameters

| Name | Type |
| :------ | :------ |
| `menuId` | `string` |

#### Returns

`void`

___

### getAllDesktopMenuInfo

▸ **getAllDesktopMenuInfo**(`recordMenuConfig?`): `Object`

获取需要在桌面显示图标的菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `recordMenuConfig?` | `any` |

#### Returns

`Object`

___

### getDesktopButtonMaxWidth

▸ **getDesktopButtonMaxWidth**(): `any`

获取系统桌面的图标显示的宽度

#### Returns

`any`

___

### getDesktopButtonTitleMaxWidth

▸ **getDesktopButtonTitleMaxWidth**(): `any`

获取系统桌面的图标文字最大宽度

#### Returns

`any`

___

### getDesktopToolbarButton

▸ **getDesktopToolbarButton**(`sourceMenu`): `any`

获取工具栏的按钮对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `sourceMenu` | `any` |

#### Returns

`any`

___

### getDesktopToolbarButtonByGroup

▸ **getDesktopToolbarButtonByGroup**(`sourceMenu`): `any`

根据菜单分组获取工具栏上的按钮

#### Parameters

| Name | Type |
| :------ | :------ |
| `sourceMenu` | `any` |

#### Returns

`any`

___

### getFolderChildMenus

▸ **getFolderChildMenus**(`folderId`): `any`

查找存在文件夹内的菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `folderId` | `string` |

#### Returns

`any`

___

### getInsertFixedButtonIndex

▸ **getInsertFixedButtonIndex**(): `any`

获取工具栏可插入固定菜单的按钮位置

#### Returns

`any`

___

### getInsertMenuButtonIndex

▸ **getInsertMenuButtonIndex**(): `any`

获取工具栏可插入菜单按钮的位置

#### Returns

`any`

___

### getMenu

▸ **getMenu**(`menuId`): `any`

获取菜单对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `menuId` | `string` |

#### Returns

`any`

___

### getMenuByMuuriGridItem

▸ **getMenuByMuuriGridItem**(`item`): `any`

根据muuriGrid选项获取绑定的菜单对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `item` | `any` |

#### Returns

`any`

___

### getMenuPath

▸ **getMenuPath**(`menu`, `iconColor`, `iconSize`): `string`

获取菜单路径显示

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |
| `iconColor` | `string` |
| `iconSize` | `string` |

#### Returns

`string`

___

### getSystemHeaderPanel

▸ **getSystemHeaderPanel**(`cls?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `cls?` | `any` |

#### Returns

`any`

___

### getTopDesktopWindow

▸ **getTopDesktopWindow**(): `any`

获取最上层显示的窗体

#### Returns

`any`

___

### getWindowMenu

▸ **getWindowMenu**(`menu`): `any`

获取菜单打开的窗体的对象

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`any`

___

### hasWindowMenu

▸ **hasWindowMenu**(`menu`): `boolean`

检查是否存在menu的窗体对象，如果已打开则显示提示

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`boolean`

___

### hideAllDesktopWin

▸ **hideAllDesktopWin**(): `void`

隐藏桌面所有的窗口

#### Returns

`void`

___

### hideDeleteFolder

▸ **hideDeleteFolder**(): `void`

隐藏用于删除的垃圾箱

#### Returns

`void`

___

### outDesktopMenuFolder

▸ **outDesktopMenuFolder**(`sourceMenu`): `void`

将菜单移除文件夹

#### Parameters

| Name | Type |
| :------ | :------ |
| `sourceMenu` | `any` |

#### Returns

`void`

___

### recordMenu

▸ **recordMenu**(): `void`

记录菜单配置

#### Returns

`void`

___

### refreshActiveToolbarButton

▸ **refreshActiveToolbarButton**(): `void`

刷新当前被最高显示的菜单窗体

#### Returns

`void`

___

### refreshMuuriGridContainers

▸ **refreshMuuriGridContainers**(): `void`

刷新记录muuriGrid容器集合

#### Returns

`void`

___

### refreshMuuriGridMenuIndex

▸ **refreshMuuriGridMenuIndex**(): `void`

刷新menu排序索引

#### Returns

`void`

___

### removeAllDesktopToolbarFixedButton

▸ **removeAllDesktopToolbarFixedButton**(): `void`

移除所有固定在工具栏的按钮

#### Returns

`void`

___

### removeDesktopButton

▸ **removeDesktopButton**(`menu`, `silence?`): `void`

移除快捷方式

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |
| `silence?` | `boolean` |

#### Returns

`void`

___

### removeDesktopToolbarButton

▸ **removeDesktopToolbarButton**(`sourceMenu`): `void`

移除工具栏菜单按钮

#### Parameters

| Name | Type |
| :------ | :------ |
| `sourceMenu` | `any` |

#### Returns

`void`

___

### removeDesktopToolbarFixedButton

▸ **removeDesktopToolbarFixedButton**(`sourceMenu`): `void`

取消固定桌面工具栏中

#### Parameters

| Name | Type |
| :------ | :------ |
| `sourceMenu` | `any` |

#### Returns

`void`

___

### resetWindowMenuAnimTarget

▸ **resetWindowMenuAnimTarget**(`menu`, `target`): `void`

重新设置菜单的窗体对象的动画目标

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |
| `target` | `any` |

#### Returns

`void`

___

### restoreMenu

▸ **restoreMenu**(): `any`

恢复菜单配置

#### Returns

`any`

___

### restoreSystemDesktopMenus

▸ **restoreSystemDesktopMenus**(): `void`

还原系统菜单配置

#### Returns

`void`

___

### safeGetMenuColor

▸ **safeGetMenuColor**(`menu`): `string`

获取菜单颜色

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`string`

___

### safeGetMenuIcon

▸ **safeGetMenuIcon**(`menu`): `string`

获取菜单的图标

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`string`

___

### showDeleteFolder

▸ **showDeleteFolder**(): `void`

显示用于删除的垃圾箱

#### Returns

`void`

___

### showDesktopBackgroundImages

▸ **showDesktopBackgroundImages**(`obj`): `void`

查看桌面背景图片集合

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`void`

___

### showEditFolderName

▸ **showEditFolderName**(`menu`): `void`

修改文件夹名称

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`void`

___

### showFolder

▸ **showFolder**(`obj`, `menu`, `active?`): `void`

显示文件夹

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `menu` | `any` |
| `active?` | `boolean` |

#### Returns

`void`

___

### showFolderByMenuId

▸ **showFolderByMenuId**(`obj`, `menuId`): `void`

显示文件夹

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `menuId` | `string` |

#### Returns

`void`

___

### showSystemLayout

▸ **showSystemLayout**(): `void`

初始化桌面布局系统

#### Returns

`void`

___

### showWindowMenu

▸ **showWindowMenu**(`animObj`, `menu`, `active?`): `void`

在窗体中打开menu菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `animObj` | `any` |
| `menu` | `any` |
| `active?` | `boolean` |

#### Returns

`void`

___

### showWindowMenuById

▸ **showWindowMenuById**(`animObj`, `menuId`, `active?`): `void`

在窗体中打开menu菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `animObj` | `any` |
| `menuId` | `string` |
| `active?` | `boolean` |

#### Returns

`void`

___

### showWindowPanel

▸ **showWindowPanel**(`obj`, `title`, `panel`): `void`

弹出系统相关功能面板窗体查看

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |
| `title` | `string` |
| `panel` | `any` |

#### Returns

`void`

___

### switchMuuriGrid

▸ **switchMuuriGrid**(`muuriGrid`, `item`, `dragEnd`): `void`

将muuriGrid里的item切换到另一个grid里，并更新文件夹的信息

#### Parameters

| Name | Type |
| :------ | :------ |
| `muuriGrid` | `any` |
| `item` | `any` |
| `dragEnd` | `any` |

#### Returns

`void`

___

### takeIcon

▸ **takeIcon**(`icon`, `color`): `string`

提取svg图标，并返回指定颜色的svg图标

#### Parameters

| Name | Type |
| :------ | :------ |
| `icon` | `string` |
| `color` | `string` |

#### Returns

`string`

___

### toggleStartMenu

▸ **toggleStartMenu**(`obj`): `void`

打开或关闭系统菜单

#### Parameters

| Name | Type |
| :------ | :------ |
| `obj` | `any` |

#### Returns

`void`

___

### updateDesktopMenuButton

▸ **updateDesktopMenuButton**(`menu`): `void`

更新桌面菜单信息

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`void`

___

### updateFolderGridMenu

▸ **updateFolderGridMenu**(`muuriGrid`): `void`

更新grid对应的桌面菜单对象，一般用于拖拽时实时的更新文件夹显示的图标

#### Parameters

| Name | Type |
| :------ | :------ |
| `muuriGrid` | `any` |

#### Returns

`void`

___

### updateMenuInfo

▸ **updateMenuInfo**(`menu`): `void`

更新与菜单相关的消息，包括：桌面按钮、工具栏按钮、窗体等

#### Parameters

| Name | Type |
| :------ | :------ |
| `menu` | `any` |

#### Returns

`void`
