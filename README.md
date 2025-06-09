# DevPath

高效管理文件夹路径，提升开发效率。

## 特性

- 根路径配置：可自定义根路径，如 `/content/category/model/`。
- 子路径配置：支持配置多个子路径，如 `images/`, `videos/`。
- 路径拼接：自动将 `根路径` 与 `子路径` 组合，生成完整路径。

## 用法

- 配置根路径：
  - 格式示例：
    - 相对路径：`/content/category/model/`。
    - 绝对路径：`https://example.com/content/category/model/`。
  - 操作方式：
    - 点击状态栏 `DevPath`，输入根路径。
    - 在插件设置界面中完成配置。

- 配置子路径：
  - 格式示例：`images/`, `videos/`。
  - 操作方式：在插件设置界面中完成配置。

- 执行路径拼接：
  - 通过使用快捷键 `Ctrl+Alt+P` 或右键菜单选择 `DevPath` 运行指令。
  - 运行后自动将基础路径与文档内所有匹配的子路径拼接。
  - 转换示例：
    - `images/hero.jpg` → `/content/category/model/images/hero.jpg`
    - `videos/hero.mp4` → `/content/category/model/videos/hero.mp4`
