# 豆包工作 · 设计规范与品牌资产

基于《豆包工作品牌视觉识别系统 VIS 2026》整理的设计指南，供设计师、前端工程师和 AI 编程助手设计豆包工作相关网页、产品界面、演示页面及品牌物料时参考。

**从 [design.md](design.md) 开始；下载文件和校验摘要见[资产清单](assets/README.md)。**

公开仓库：[vibe-lark/doubao-work-design](https://github.com/vibe-lark/doubao-work-design)。

本项目是对原始 VIS 的整理与界面设计建议，不代表豆包工作官方发布、认证或背书，也不替代官方品牌规范。当前交付包含文档和素材，不包含可运行应用或完整组件库。

## 出处与版本

| 项目 | 说明 |
| --- | --- |
| 原始文档 | [《豆包工作品牌视觉识别系统 VIS 2026》](https://bytedance.larkoffice.com/wiki/KbcTwrtXxirALlkfCQnccAa1n0d) |
| 读取版本 | revision 351 |
| 整理与附件核验日期 | 2026-09-29 |
| 设计指南版本 | 1.0.3（完整素材版） |
| 原始附件入口 | [原文「资源文件下载」](https://bytedance.larkoffice.com/wiki/KbcTwrtXxirALlkfCQnccAa1n0d#doxcnFvcP9qYqdYa8QhBXng1Ucd) |
| 版权说明出处 | [原文「版权说明」](https://bytedance.larkoffice.com/wiki/KbcTwrtXxirALlkfCQnccAa1n0d#doxcnmpAjlpLZxlckawv5hD9Dfh) |

源文及其附件入口可能需要飞书账号和相应访问权限。本项目记录的是上述日期读取的版本，不保证与后续更新的源文自动同步；品牌要求以最新官方规范及权利人说明为准。

## 如何使用

1. 阅读 [design.md](design.md) 的使用方式与品牌规则，先确定页面范围和实际素材用途。
2. 将该文件提供给设计师或 AI 编程助手，并说明具体产品需求、已有组件库及输出要求。可使用：“请按 design.md 设计本项目；遵守 [VIS] 规则，将 [建议] 作为默认值，遇到冲突或缺失资产时明确标注。”
3. 根据语言、背景和使用场景，从 [Logo 清单](assets/README.md#可直接选用的官方-logo-png) 选择正式素材，保持原比例、最小尺寸和安全区。
4. 需要 App icon、组件图标或品牌字体时，先核对素材与适用授权，再完成目标格式导出。AI 源文件不等于已可直接使用的网页图标。
5. 按设计指南末尾的验收清单检查品牌、组件状态、可访问性和窄屏适配。

## 开发时引用哪个链接

- 给 AI 编程助手读取规范：[design.md 原始文本（跟随 main 更新）](https://raw.githubusercontent.com/vibe-lark/doubao-work-design/main/design.md)。
- 人工浏览规范：[GitHub 文档页](https://github.com/vibe-lark/doubao-work-design/blob/main/design.md)。
- 选择 Logo、下载原件：[资产清单](assets/README.md)；Logo PNG 位于 [assets/logo](assets/logo)，原始附件位于 [assets/source](assets/source)。

给开发助手的示例指令：

```text
请读取 https://raw.githubusercontent.com/vibe-lark/doubao-work-design/main/design.md，
按照其中的 [VIS] 品牌规则和 [建议] UI 默认值开发本项目。
Logo 使用同仓库 assets/logo 中匹配语言与背景的官方 PNG，不要自行重绘。
产品 UI 按规范使用系统字体；需要品牌物料字体时再选择官方字体包。
```

开始一个正式项目时，建议把所采用的 design.md 与所需素材复制到项目中，并记录本仓库的 commit SHA。`main` 链接会更新；需要固定版本时，将原始文本 URL 中的 `main` 替换为该 commit SHA，素材也使用同一版本。网页运行时使用自己项目托管的选定素材，不把整个字体包或 AI 源文件作为页面资源加载。

## 规则边界

- **[VIS]**：源文正文明确规定，或已从原图核验的品牌规则，包括 Logo、品牌色、字体场景和安全区等。
- **[建议]**：本项目新增的界面默认值，包括语义色、字号、间距、圆角、布局、组件状态及 CSS 变量；可按项目调整，但不能覆盖 VIS 规则。
- 原 VIS 没有定义完整产品功能、交互系统或后端架构。本项目中的界面示意和 AI 任务状态建议不代表现有产品已具备这些能力。

## 文件目录

```text
.
├── README.md                    # 项目说明、出处与使用边界
├── design.md                    # 品牌规则、UI 建议、CSS 示例及验收清单
└── assets/
    ├── README.md                # 附件清单、Logo 入口、SHA-256
    ├── logo/                    # 从原始 ZIP 原样解压的 9 张 PNG
    └── source/                  # 4 项原始附件
        ├── 豆包工作_标志.zip
        ├── 豆包工作_app icon.ai
        ├── 豆包工作品牌字体.zip
        └── 豆包工作产品icon.ai
```

## 素材状态

四项原始附件已于 2026-09-29 通过当时用户权限下载，字节数与源文附件元数据一致。两个 ZIP 已通过完整性检查；AI 文件核验到 PDF 兼容文件头，尚未在 Illustrator 中打开或导出。文件哈希见[资产清单](assets/README.md#完整性摘要)。

| 素材 | 已提供 | 使用前仍需完成 |
| --- | --- | --- |
| [Logo 包](<assets/source/豆包工作_标志.zip>) | 9 张 PNG、1 个 AI 源文件；PNG 已解压 | 按场景选版并核对可见边界；原包未提供 SVG |
| [App icon](<assets/source/豆包工作_app icon.ai>) | AI 源文件 | 按目标系统要求导出和核对裁切 |
| [品牌字体](<assets/source/豆包工作品牌字体.zip>) | 8 个方正兰亭黑 TTF、1 个 Inter 可变 TTF | 核对 family、字重和授权；未提供 WOFF/WOFF2，未安装字体 |
| [产品组件 icon](<assets/source/豆包工作产品icon.ai>) | AI 源文件 | 打开核对内容，导出项目所需的 SVG/PNG 等格式 |

四项附件没有单列官方账号头像成品。公开项目中的下载文件仍受其原有权利及使用条件约束。

## DESIGN.md 格式兼容情况

2026-09-29 已使用 [Google design.md 官方 CLI](https://github.com/google-labs-code/design.md) 的 `@google/design.md@0.4.0` 核验设计指南基线版本 1.0.1；后续版本补充公开资产与获取说明，未添加 YAML token 层：

| 检查 | 实际结果 |
| --- | --- |
| `lint` | 退出码 0；0 errors、1 warning |
| 警告内容 | 未发现 YAML frontmatter 或 fenced YAML 内容 |
| `export --format dtcg` | 退出码 0，但结果只有 schema 声明，没有任何 token |

因此，当前文件适合人和 AI 阅读，包含可参考的 CSS 变量，**尚不是可通过该 CLI 导出设计 token 的结构化设计系统**。不能把 `lint` 的 0 errors 理解为所有 token 已通过校验。

依据本次核验的 [Google DESIGN.md alpha 规范](https://github.com/google-labs-code/design.md/blob/main/docs/spec.md)，YAML 层是可选项；中文章节和资产清单是本项目的组织方式。若要使用自动导出能力，后续需增加机器可读 token 层并重新验证。本项目不宣称符合所有工具或某个统一行业标准。

## 权利与使用说明

品牌名称、Logo、字体、源文图像及其他第三方素材的权利仍归各自权利人。项目公开可见或可下载不等于素材已获得开源授权，也不自动授予商标使用、商业使用、再分发或字体 Web 分发许可。

本项目未为这些品牌资产及第三方素材附加 MIT 等开源许可证。引用出处用于追溯来源，不替代使用授权；实际使用请遵循[源文版权说明](https://bytedance.larkoffice.com/wiki/KbcTwrtXxirALlkfCQnccAa1n0d#doxcnmpAjlpLZxlckawv5hD9Dfh)及相关权利人的许可条件。品牌规则疑问交由品牌负责人确认，界面建议由具体项目设计负责人判断。
