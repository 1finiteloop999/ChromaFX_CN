# ChromaFX_CN
Unity 粒子特效改色插件｜为已有的多层粒子特效配置和切换配色。中文版 Unity 包下载。
ChromaFX 是一个 Unity 编辑器改色工具，不负责生成特效本身。

演示过程链接：https://www.bilibili.com/video/BV1uWYF6YETE

**下载与安装**

下载下方 Assets 中的「ChromaFX_CN.unitypackage」，导入 Unity 项目。

导入完成后，通过 Tools → ChromaFX → 配色面板 打开工具。

此包只包含工具，不包含演示特效或第三方 Shader。

**使用前注意**

- 请先备份特效及其材质。复制 Prefab 并不会自动复制它引用的材质。
- 已在 Unity 2022.3.62f3 中测试，其他 Unity 版本尚未验证。
- 已测试 BRP 和 URP 下的部分 Shader，不代表支持所有 Shader。（测试使用shader为PandaShader的URP版本和BRP版本）
- 工具处理 Start Color、Color over Lifetime 和材质的 _MainColor。Shader 需要支持相应颜色输入。
- 建议使用灰度纹理；彩色纹理或 Shader 内其他颜色运算可能影响最终配色。
- 请在首次改色前记录基线，以便还原原始状态。

遇到问题可以通过仓库的 Issues 反馈，请附上 Unity 版本、渲染管线、Shader 名称和复现步骤。
