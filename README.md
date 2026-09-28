# 豆包工作 · 设计规范

基于《豆包工作品牌视觉识别系统 VIS 2026》整理的设计指南，供设计师、前端工程师和 AI 编程助手设计豆包工作相关网页、产品界面、演示页面及品牌物料时参考。

**从 [design.md](design.md) 开始；素材名称、核验记录和获取方式见[素材来源索引](assets/README.md)。**

项目地址：[vibe-lark/doubao-work-design](https://github.com/vibe-lark/doubao-work-design)。本项目是对原始 VIS 的整理与界面设计建议，不代表豆包工作官方发布、认证或背书，也不替代官方品牌规范。

## 出处与版本

| 项目 | 说明 |
| --- | --- |
| 原始文档 | [《豆包工作品牌视觉识别系统 VIS 2026》](https://bytedance.larkoffice.com/wiki/KbcTwrtXxirALlkfCQnccAa1n0d) |
| 读取版本 | revision 351 |
| 整理与源附件核验日期 | 2026-09-29 |
| 设计指南基线版本 | 1.0.1（补充素材核验） |
| 本仓库文档版本 | 1.0.2（公开文档版） |
| 官方素材入口 | [原文「资源文件下载」](https://bytedance.larkoffice.com/wiki/KbcTwrtXxirALlkfCQnccAa1n0d#doxcnFvcP9qYqdYa8QhBXng1Ucd) |
| 版权说明出处 | [原文「版权说明」](https://bytedance.larkoffice.com/wiki/KbcTwrtXxirALlkfCQnccAa1n0d#doxcnmpAjlpLZxlckawv5hD9Dfh) |

源文及其素材入口可能需要飞书账号和相应访问权限。本项目记录的是上述日期读取的版本，不保证与后续源文更新自动同步；品牌要求以最新官方规范及权利人说明为准。

## 如何使用

1. 阅读 [design.md](design.md)，确定实际页面范围、品牌规则和素材用途。
2. 将该文件提供给设计师或 AI 编程助手，同时说明具体产品需求、已有组件库及输出要求。例如：“请按 design.md 设计本项目；遵守 [VIS] 规则，将 [建议] 作为默认值，遇到冲突或缺失资产时明确标注。”
3. 根据[素材来源索引](assets/README.md)，前往官方源文获取有权使用的素材。按语言、背景和场景选取正式 Logo，保持原比例、最小尺寸与安全区。
4. 使用 App icon、组件图标或品牌字体前，核对内容及适用授权，再完成目标格式导出。
5. 按设计指南的验收清单检查品牌、组件状态、可访问性和窄屏适配。

## 规则边界

- **[VIS]**：源文正文明确规定，或已从原图核验的品牌规则，包括 Logo、品牌色、字体场景和安全区等。
- **[建议]**：本项目新增的界面默认值，包括语义色、字号、间距、圆角、布局、组件状态及 CSS 变量；可按项目调整，但不能覆盖 VIS 规则。
- 原 VIS 没有定义完整产品功能、交互系统或后端架构。本项目中的界面示意和 AI 任务状态建议不代表现有产品已具备这些能力。

## 仓库内容

```text
.
├── README.md          # 项目用途、出处和使用说明
├── design.md          # 品牌规则、UI 建议、CSS 示例及验收清单
└── assets/
    └── README.md      # 素材来源索引与核验记录
```

此公开仓库提供设计文档与素材出处索引，不托管 PNG、ZIP、AI、TTF 等品牌素材二进制文件，也不包含可运行应用或完整组件库。具体素材请经官方源文取得。

## 官方素材索引

以下为 2026-09-29 通过当时用户权限下载并核验的源附件信息，文件本身未收录于本仓库。

| 源附件名称 | 已核验内容 | 使用前仍需完成 |
| --- | --- | --- |
| `豆包工作_标志.zip` | 9 张 PNG、1 个 AI 源文件；ZIP 完整性通过 | 按场景选版并核对可见边界；原包未提供 SVG |
| `豆包工作_app icon.ai` | AI 源文件，具有 PDF 兼容文件头 | 在设计软件中核对，按目标系统导出并检查裁切 |
| `豆包工作品牌字体.zip` | 8 个方正兰亭黑 TTF、1 个 Inter 可变 TTF；ZIP 完整性通过 | 核对 family、字重和授权；原包未提供 WOFF/WOFF2 |
| `豆包工作产品icon.ai` | AI 源文件，具有 PDF 兼容文件头 | 在设计软件中核对，导出项目所需格式 |

四项附件的字节数与源文元数据一致。AI 文件尚未在 Illustrator 中打开或导出，字体未安装；四项附件没有单列官方账号头像成品。核验记录和获取入口见[素材来源索引](assets/README.md)。

## DESIGN.md 格式兼容情况

2026-09-29 对设计指南基线版本使用 [Google design.md 官方 CLI](https://github.com/google-labs-code/design.md) `@google/design.md@0.4.0` 的实测结果：

| 检查 | 实际结果 |
| --- | --- |
| `lint` | 退出码 0；0 errors、1 warning |
| 警告内容 | 未发现 YAML frontmatter 或 fenced YAML 内容 |
| `export --format dtcg` | 退出码 0，但结果只有 schema 声明，没有任何 token |

当前设计指南适合人和 AI 阅读，包含可参考的 CSS 变量，**尚不是可通过该 CLI 导出设计 token 的结构化设计系统**。不能把 `lint` 的 0 errors 理解为所有 token 已通过校验。

依据本次核验的 [Google DESIGN.md alpha 规范](https://github.com/google-labs-code/design.md/blob/main/docs/spec.md)，YAML 层是可选项。若要使用自动导出能力，需增加机器可读 token 层并重新验证。本项目不宣称符合所有工具或某个统一行业标准。

## 权利与使用说明

品牌名称、Logo、字体、源文图像及其他第三方素材的权利仍归各自权利人。项目公开可见不等于品牌素材已获得开源授权，也不自动授予商标使用、商业使用、再分发或字体 Web 分发许可。

本项目未为品牌资产及第三方素材附加 MIT 等开源许可证。引用出处用于追溯来源，不替代使用授权；实际使用请遵循[源文版权说明](https://bytedance.larkoffice.com/wiki/KbcTwrtXxirALlkfCQnccAa1n0d#doxcnmpAjlpLZxlckawv5hD9Dfh)及相关权利人的许可条件。品牌规则疑问交由品牌负责人确认，界面建议由具体项目设计负责人判断。
