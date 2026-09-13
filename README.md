# 快速设置灯光 (Quick Light Setup)

在 Blender 里完整设置一盏灯，需要在属性编辑器的灯光页来回找：功率、色温、尺寸、阴影、光型各在一处，打光过程中反复跳转，效率很低。

本插件把灯光设置集中到一个弹窗：**物体模式选中灯光按 `D`**，调光、色温、类型、尺寸阴影、朝向、命名一屏搞定；同样的界面也集成在 3D 视图 `N` 面板中。

![使用预览](preview_1.png)

## 功能总览

| 模块 | 内容 |
| --- | --- |
| 快捷调光 | 骤减 / 轻减 / 轻增 / 骤增 四档功率倍数（×0.5 / ×0.67 / ×1.5 / ×2） |
| 色温与光色 | 12 档色温预设（蜡烛 1800K ～ 暮光 12000K），当前档位高亮 |
| 类型与光型 | 面光 / 点光 / 聚光 / 日光一键切换，面光形状直接修改 |
| 尺寸与阴影 | 按灯光类型显示对应参数：尺寸 / 半径 / 角度 / 柔化 / 扩散 |
| 强度与曝光 | 功率（日光为强度）与曝光 |
| 朝向对齐 | 一键让灯光沿当前 3D 视图方向照射 |
| 灯光命名 | 主光 / 补光 / 轮廓光 / 点缀光 一键命名 |
| 共享与光照链接 | 检测共享的灯光数据与光照链接集合，一键独立化或清除；仅在灯光存在此类数据时显示 |

所有操作支持 Blender 的撤销（Ctrl+Z）。

## 快捷键与入口

- **`D`**（物体模式，选中灯光）：打开灯光设置弹窗，点击空白处关闭
- **N 面板**：3D 视图 → `N` → 快速设置灯光，功能与弹窗一致，并含模块显示开关

## 自定义

偏好设置（编辑 → 偏好设置 → 扩展 → 快速设置灯光）或 N 面板顶部可调整：

- **模块显示**：8 个模块可独立显示 / 隐藏，按自己的打光流程精简界面
- **弹窗宽度**：180 ～ 500 可调

## 安装

1. 在 [Releases](../../releases) 页面下载 `quick_light_setup-x.x.x.zip`
2. Blender → 编辑 → 偏好设置 → 获取扩展（Get Extensions）
3. 点击右上角下拉箭头 → 从磁盘安装（Install from Disk），选择 zip 并启用

> Blender 3.2～4.1（无扩展系统）：下载仓库中的 `__init__.py`，改名为 `quick_light_setup.py`，通过偏好设置 → 插件 → 安装（旧式插件）安装。

## 兼容性

- 代码支持 Blender 3.2 及以上
- 扩展方式安装需 Blender 4.2+

## 许可证

[GPL-3.0-or-later](LICENSE)

## 同系列插件 · More by wen-yifeng

**相机 / Camera** — [camera_list](https://github.com/wen-yifeng/camera_list)（F10 切相机）· [quick_camera_setup](https://github.com/wen-yifeng/quick_camera_setup)（D 键相机设置）

**灯光 / Lighting** — [quick_light_setup](https://github.com/wen-yifeng/quick_light_setup)（D 键灯光设置）· [smart_light_size](https://github.com/wen-yifeng/smart_light_size)（拖拽调灯大小）

**视图 / Viewport** — [view_reset](https://github.com/wen-yifeng/view_reset)（Alt+R 一键复位）· [view_rotate_mode_switch](https://github.com/wen-yifeng/view_rotate_mode_switch)（轨迹球旋转）· [view_alerts_hud](https://github.com/wen-yifeng/view_alerts_hud)（Shift+F2 状态 HUD）

**工作流 / Workflow** — [outliner_smart_sync](https://github.com/wen-yifeng/outliner_smart_sync)（大纲批量显隐）· [editor_split](https://github.com/wen-yifeng/editor_split)（一键分屏）· [npanel_focus](https://github.com/wen-yifeng/npanel_focus)（Q 键 N 面板）· [duplicate_to_collection](https://github.com/wen-yifeng/duplicate_to_collection)（复制到集合）· [object_mode_uv_unwrap](https://github.com/wen-yifeng/object_mode_uv_unwrap)（物体模式 UV）· [render_auto_save](https://github.com/wen-yifeng/render_auto_save)（F12 自动存图）

**预设 / Presets** — [pme_preset](https://github.com/wen-yifeng/pme_preset)（Pie Menu Editor 80 个饼菜单）

好用的话点个 Star ⭐ · A star is appreciated if it helps you.
