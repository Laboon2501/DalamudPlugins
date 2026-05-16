# Laboon2501 Dalamud Plugins

This repository is a unified Dalamud / XIVLauncherCN custom plugin repository index. It only stores publishing metadata such as `repo.json`, README, and icons. Plugin source code stays in each plugin's own source repository.

本仓库是统一的 Dalamud / 卫月自定义插件源索引仓库，只维护 `repo.json`、README、图标等发布索引文件，不存放插件源码。

## Plugin Repository URL

Add this URL in Dalamud Plugin Installer -> Third-Party Plugin Repositories:

在 Dalamud / 卫月插件安装器的第三方插件仓库中添加：

```text
https://raw.githubusercontent.com/Laboon2501/DalamudPlugins/main/repo.json
```

After updating the plugin list, you should see:

- Gpose Camera Saver
- Hyperborea

## Source Repositories

- [Gpose Camera Saver](https://github.com/Laboon2501/GposeCameraSaver)
- [Hyperborea](https://github.com/Laboon2501/Hyperborea)

## Deprecated Standalone Source

The old standalone Gpose Camera Saver source is deprecated and kept only for compatibility:

```text
https://raw.githubusercontent.com/Laboon2501/GposeCameraSaver/main/repo.json
```

If you previously added the old standalone source, remove it after adding the unified source. Keeping both sources may make the plugin installer show duplicate Gpose Camera Saver entries.

旧的 Gpose Camera Saver 单独插件源已废弃，仅为兼容保留。如果以前添加过旧源，请在添加统一源后删除旧源，避免插件安装器里出现重复插件。
