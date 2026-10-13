<p align="center"><a href="README.md"><strong>中文（默认）</strong></a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a></p>

<p align="center">
  <img src="outputs/desktop-pet/apps/community-web/dist/assets/brand-logo.png" width="112" alt="desktop pet 标志">
</p>

<h1 align="center">desktop pet</h1>

<p align="center"><strong>可共创的桌面伙伴：自定义动作、人物人设、可选插件与多 AI 工作联动。</strong></p>

<p align="center">
  <a href="https://github.com/xunguangzlj-cloud/desktop-pet-community/releases/latest">下载安装包</a> ·
  <a href="https://desktoppet-e9e.pages.dev">共创平台</a> ·
  <a href="https://github.com/xunguangzlj-cloud/desktop-pet-community/issues">问题反馈</a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/xunguangzlj-cloud/desktop-pet-community?label=%E7%89%88%E6%9C%AC" alt="发布版本">
  <img src="https://img.shields.io/github/downloads/xunguangzlj-cloud/desktop-pet-community/total?label=%E4%B8%8B%E8%BD%BD" alt="发布文件下载数">
  <img src="https://img.shields.io/badge/%E5%B9%B3%E5%8F%B0-Windows%20x64-60bba0" alt="Windows x64">
  <img src="https://img.shields.io/badge/macOS-arm64%20%2F%20x64-60bba0" alt="macOS arm64 / x64">
  <img src="https://img.shields.io/github/stars/xunguangzlj-cloud/desktop-pet-community?label=Star" alt="GitHub Star">
</p>

## 1. 主要功能

- **桌面陪伴**：可拖拽、调整大小和隐藏。默认安静待机，点击随机回应；关闭安静模式后随机播放动作，真实 AI 工作状态优先联动。
- **自由定义动作**：支持图集、动画 WebP 和视频动作，可修改动作名称、类别、随机候选与 AI／点击／拖拽等状态绑定。
- **和桌宠对话**：为宠物大脑配置自己的云端或本机 AI，支持多个来源和自定义兼容接口。输入与回答的字体、气泡样式可调整，控制中心显示带时间的历史。
- **人物人设**：自行编写全局 Markdown，导入人物 Skill、Tavern V1／V2／V3 JSON 或 PNG 角色卡，或用已配置的 AI 从资料提炼人设。已启用的完整 Skill 人设随桌宠对话使用，无需触发词；不自动执行其中的任意脚本。
- **多个 AI 工作联动**：一个桌宠可展示多个已接入会话的工作状态、具体工具和成功编辑文件数。Codex、ZCode 提供 Hook 接入，其他工具按各自桥接能力配置；工作监测与桌宠对话的 AI 分开管理。
- **按支持情况查看额度**：Codex 支持官方只读订阅额度窗口；DeepSeek 对话来源支持官方余额查询，OpenRouter 支持官方密钥额度适配。未接通的来源显示未知，桌宠对话的 token 用量不冒充其他 AI 工具的剩余额度。
- **按需安装插件**：喝水、久坐、眼睛休息、番茄钟等提醒，以及文件助手、电脑守护均为可选插件。提醒进入同一桌宠对话；文件助手提供本地定位与虚拟分类库，实际整理先查看计划，电脑守护提供监测和建议。
- **共创平台**：桌宠广场、插件广场、需求广场、榜单与作者页；制作和直接导入分开，支持自定义视频动作、插件封面及完整作品投稿。现有 362 件桌宠与 24 件插件，其中包含 Codex Pet 全部 316 件作品；每件保留原作者与原素材条款。默认按真实点赞与下载量热门优先展示，右上角支持中英日韩四语切换并记忆选择，首次使用默认中文。[共创平台](https://desktoppet-e9e.pages.dev/#pets)
- **开放导入**：兼容作品在本系统安装运行；不兼容项目保留原件，无法支持的操作禁用。有可识别原程序及运行环境时，可明确选择独立启动，不强制改写原项目逻辑。

外部 AI 需要自己的账号、工具和配置；预设入口、链路测试或原程序启动不代表全部平台已经接通，也不代表任意导入项目都能完整运行。当前实际交付和验证范围见[交付状态](outputs/desktop-pet/docs/release-status.md)。

### 社区收录桌宠示例

| <a href="https://desktoppet-e9e.pages.dev/#pets/firefly--lingxiaotian"><img src="outputs/desktop-pet/apps/community-web/dist/assets/pets/upstream-20261009/firefly--lingxiaotian-thumb.webp" width="150" alt="流萤"></a> | <a href="https://desktoppet-e9e.pages.dev/#pets/lulu--yogazz"><img src="outputs/desktop-pet/apps/community-web/dist/assets/pets/upstream-20261009/lulu--yogazz-thumb.webp" width="150" alt="Lulu"></a> | <a href="https://desktoppet-e9e.pages.dev/#pets/pc2005-dsh-pet"><img src="outputs/desktop-pet/apps/community-web/dist/assets/pets/pc2005-dsh-pet-20261011/thumbnail.webp" width="150" alt="dsh-pet"></a> |
|:---:|:---:|:---:|
| **流萤** | **Lulu** | **[dsh-pet](https://desktoppet-e9e.pages.dev/#pets/pc2005-dsh-pet)** |
| <a href="https://desktoppet-e9e.pages.dev/#pets/bongocat-vladelaina"><img src="outputs/desktop-pet/apps/community-web/dist/assets/pets/adapted-20261010/bongocat-vladelaina/thumbnail.webp" width="150" alt="BongoCat"></a> | <a href="https://desktoppet-e9e.pages.dev/#pets/cloud-lykinzlj1"><img src="outputs/desktop-pet/apps/community-web/dist/assets/pets/user-projects-20261010/cloud-lykinzlj1/thumbnail.webp" width="150" alt="真珠"></a> | <a href="https://desktoppet-e9e.pages.dev/#pets/danya-pet-windows"><img src="outputs/desktop-pet/apps/community-web/dist/assets/pets/user-projects-20261010/danya-pet-windows/thumbnail.webp" width="150" alt="达妮娅 · 三形态"></a> |
| **BongoCat** | **真珠** | **达妮娅 · 三形态** |

## 2. 安装方法

### 若不熟悉 GitHub 下载流程

1. 直接把网址复制给 AI，让 AI 帮你安装。
2. [Windows 一键下载](https://github.com/xunguangzlj-cloud/desktop-pet-community/releases/download/v4.0.6/desktop-pet-4.0.6-windows-x64-portable.zip)，完整解压后双击 `desktop-pet.exe`。macOS 用户可下载下方对应的 Mac 包。

### Windows

1. 打开 [v4.0.6 Release](https://github.com/xunguangzlj-cloud/desktop-pet-community/releases/latest)，下载 Windows x64 便携 ZIP 和 `SHA256SUMS.txt`。GitHub 自动生成的 `Source code` ZIP 是源码。
2. 将便携 ZIP **完整解压**到一个可写目录，例如 `D:\Apps\desktop-pet`。保留同目录的 `resources`、运行库与其他文件，不单独移动 EXE，也不直接在 ZIP 内启动。
3. 双击解压目录中的 `desktop-pet.exe`。自带运行环境，无需安装 Node.js 或 Python；首次启动创建本机档案，不附带作者的 AI 账号或个人设置。
4. 平时直接打开此 EXE；也可为它创建桌面快捷方式。基础桌宠无需配置 AI，插件从共创平台按需下载后导入。

提供 **Windows x64**、**macOS arm64（Apple Silicon）** 与 **macOS x64（Intel）** 包。Windows 程序尚未进行代码签名；Linux 与 Windows ARM 暂无本项目已验收的安装包。控制中心「设置」可检查 GitHub 更新；更新保留本机人设、插件、对话与 AI 配置。

核对下载文件完整性可在 PowerShell 执行：

```powershell
Get-FileHash -Algorithm SHA256 .\desktop-pet-4.0.6-windows-x64-portable.zip
```

将结果与同一 Release 的 `SHA256SUMS.txt` 对照；核对哈希只能确认文件一致，不能代替安全审计。

### macOS（Apple Silicon／Intel）

[Mac M 系列下载](https://github.com/xunguangzlj-cloud/desktop-pet-community/releases/download/v4.0.6/desktop-pet-4.0.6-mac-arm64.zip) · [Mac Intel 下载](https://github.com/xunguangzlj-cloud/desktop-pet-community/releases/download/v4.0.6/desktop-pet-4.0.6-mac-x64.zip)：完整解压，将 `desktop-pet.app` 放入“应用程序”后打开。

支持 macOS arm64 / x64 源码构建；PR #2 的 Mac 打包改动已合并。与 Windows 一样，桌宠、控制中心、人设和本系统插件使用同一套代码；Windows 专用诊断、原 Windows EXE 与依赖原宿主的功能仍按平台能力限制。

在 Apple Silicon Mac 上安装 Node.js 24、pnpm 11.0.8 与 Xcode Command Line Tools，然后执行：

```bash
git clone https://github.com/xunguangzlj-cloud/desktop-pet-community.git
cd desktop-pet-community/outputs/desktop-pet
pnpm install --frozen-lockfile
pnpm build
pnpm --filter @open-pets/desktop exec electron-builder --mac --arm64 --publish never
node apps/desktop/dist/check-packaging-contract.js --output --platform darwin --arch arm64
```

输出位于 `apps/desktop/dist-electron/`，ZIP 内为完整的 `desktop-pet.app`，DMG 可拖入“应用程序”。Mac 构建采用 ad-hoc 本机签名，尚未取得 Apple Developer ID 签名与公证；遇 Gatekeeper 提示时，可按系统“隐私与安全性”中的提示批准自己信任的下载。CI 在 macOS arm64 / x64 上检查实际包、原生依赖、控制中心、桌宠显示与正常退出；最新结果和可下载构建见 [macOS 构建](https://github.com/xunguangzlj-cloud/desktop-pet-community/actions/workflows/macos.yml)。CI 验收不代表所有 Mac 型号与第三方宿主均已实测。

### 从源码开发与构建

建议 Node.js 24 和 pnpm 11.0.8：

```powershell
git clone https://github.com/xunguangzlj-cloud/desktop-pet-community.git
cd desktop-pet-community\outputs\desktop-pet
pnpm install
pnpm build
pnpm --filter @open-pets/desktop dev
```

执行 `pnpm --filter @open-pets/desktop package:dir` 可构建桌面目录版。源码保留部分上游包名和协议字段，以保持已有工具与素材兼容；正常用户使用 Release 无需执行上述命令。

网站源码、后台与部署示例也在本仓库。需要部署自己的网站时，在仓库根目录运行：

```powershell
npm ci --prefix outputs/community-site
node outputs/community-host/scripts/build.mjs
node outputs/community-cloudflare/scripts/build.mjs
```

网站部署模板见 [Cloudflare 配置示例](outputs/community-cloudflare/wrangler.toml.example)。复制为自己的 `wrangler.toml`，填写账号与 D1 数据库标识，按 `deployment-migrations` 中 `0000`、`0001`、`0011` 的顺序初始化数据库，并在平台秘密中设置 `HASH_SALT`；仓库不包含作者的部署凭据。

## 3. 使用方法

### 桌宠操作

| 操作 | 用途 |
| --- | --- |
| 拖拽桌宠 | 移动到合适位置 |
| 点击桌宠 | 安静模式下随机播放回应动作 |
| 右键 → 打开控制中心 | 管理本机桌宠、AI、人设、样式与插件 |
| 右键 → 动作 | 选择动作、调整安静模式和自定义动作 |
| 右键 → 隐藏 | 收起桌宠，通过托盘入口再显示 |
| 右键 → 对话／连续两次右键 | 打开桌宠旁的同一输入框 |
| 右键 → 大小 | 调整显示大小 |
| 对话框右上角 × | 关闭输入框，保留会话 |

### 配置对话、人设与外部监测

1. 在控制中心“接入 AI”保存提供方、模型与接口，使用连接测试后为宠物大脑选择来源。密钥在本机设置填写，不提交到仓库。
2. 在“人设个性”写入全局 Markdown，或点击“导入已蒸馏 Skill”。完整人物技能包可保留 `SKILL.md`、`manifest.json` 与 `references/`；导入后检查启用状态。
3. 在“连接外部 AI 工具”配置 Codex、ZCode 等实际安装的工具。按工具要求审阅、信任 Hook，并让新会话加载配置；不要用对话提供方设置代替外部工具监测。
4. 在额度页面查看受支持来源的官方数据与时间。没有公开接口、未登录或数据过期时，以界面“未知／待确认”为准。

详细操作见[宠物大脑](outputs/desktop-pet/docs/companion-ai.md)、[人物人设](outputs/desktop-pet/docs/companion-persona.md)与[外部 AI 接入](outputs/desktop-pet/docs/agent-integrations.md)。

### 共创平台

[共创平台](https://desktoppet-e9e.pages.dev/#pets)

下载作品包，再到控制中心“我的桌宠”或“插件管理”导入 ZIP／文件夹；查看兼容性及权限，确认后启用。新档案不预装全部插件，文件助手、电脑守护和健康提醒也需要自行安装。

网站制作与导入、本机桌宠完整包的总量上限为 **1 GiB**、单文件 **512 MiB**、最多 **10,000 条目**；Codex 图集文件另限 **100 MiB**。本机原生 SDK 插件仍为 **32 MiB**、单文件 **5 MiB**，入口代码另限 **1 MiB**。ZIP 会检查压缩包与解压后的体积；大作品可清理缓存、按独立角色拆包，或按投稿指南提供完整作品包链接。当前不支持分卷导入。

共创投稿在网站打包填写信息后，打开本站 GitHub 表单，由投稿者使用自己的 GitHub 身份附包提交，维护者审核收录；打包成功不表示已经公开。保留原项目导入及独立运行的具体范围见[桌宠与导入](outputs/desktop-pet/docs/pets.md)。

## 4. 贡献者

<!-- CONTRIBUTORS_START -->
<p>
  <a href="https://github.com/xunguangzlj-cloud"><img src="assets/contributors/xunguangzlj-cloud.svg" width="64" height="64" alt="Lykinzlj" title="Lykinzlj"></a>
  <a href="https://github.com/wuxuancheng66"><img src="assets/contributors/wuxuancheng66.svg" width="64" height="64" alt="wuxuancheng66" title="wuxuancheng66"></a>
  <a href="https://github.com/huty828"><img src="assets/contributors/huty828.svg" width="64" height="64" alt="mythos@memes" title="mythos@memes"></a>
  <a href="https://github.com/jibo1601-lang"><img src="assets/contributors/jibo1601-lang.svg" width="64" height="64" alt="jibo1601-lang" title="jibo1601-lang"></a>
</p>
<!-- CONTRIBUTORS_END -->

感谢每一位贡献桌宠、插件、代码、文档、评审和创意的伙伴。

头像墙展示本仓库贡献者与本站已收录作品的作者，点击可打开对应主页；没有有效 GitHub 主页的署名链接到本站作者页。**Lykinzlj**（[xunguangzlj-cloud](https://github.com/xunguangzlj-cloud)）维护本项目。各作品保留原作者，本站代码贡献另见 [GitHub 贡献记录](https://github.com/xunguangzlj-cloud/desktop-pet-community/graphs/contributors)。

提交作品请使用[桌宠投稿](https://github.com/xunguangzlj-cloud/desktop-pet-community/issues/new?template=pet-submission.yml)或[插件投稿](https://github.com/xunguangzlj-cloud/desktop-pet-community/issues/new?template=plugin-submission.yml)，附上完整文件、运行要求、真实作者与许可。提交代码或测试请使用 Pull Request；不要提交密钥、个人档案、聊天记录及未经授权的素材。

投稿提交后进入人工审核队列，审核、测试、收录和网站部署完成后才会上架。投稿说明见 [贡献指南](CONTRIBUTING.md)，维护者收到投稿后的步骤见 [投稿处理指南](docs/submission-maintenance.md)。

## 5. 致谢

- [OpenPetsHQ/openpets](https://github.com/OpenPetsHQ/openpets)：迁入的桌面基础、插件 SDK 与工具接入实现，保留其 MIT 许可和原版权声明。
- [legeling/awesome-codex-pet](https://github.com/legeling/awesome-codex-pet) 与 [Codex Pet](https://codexpet.top/)：桌宠社区、广场与共创流程参考，以及按作品许可保留的素材与作者资料。
- Electron、React、Vite、TypeScript、Sharp、Cloudflare 等项目及其维护者。
- 所有桌宠、插件、字体和其他素材的作者，以及参与反馈和测试的用户。

具体许可和版权资料见[第三方声明](THIRD-PARTY-NOTICES.md)，代码、字体、插件和角色素材分别按适用条款使用。

## 6. 许可与版权声明

| 内容 | 适用许可与权利范围 |
| --- | --- |
| 本项目自己的代码、说明与模板 | [MIT License](LICENSE)，版权声明为 Lykinzlj |
| 迁入的桌面代码 | 保留 [OpenPets 原 MIT 许可及版权](outputs/desktop-pet/LICENSE) |
| 插件、字体、桌宠素材 | 各自目录与下载包中的 `LICENSE`、署名和素材条款分别适用；见 [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) |
| 角色形象、作品 IP、商标与参考素材 | 相应权利属于各权利人，代码 MIT 许可不授予这些素材或角色的额外权利 |

素材中存在 CC BY、CC BY-NC 等不同条款；非商业许可作品仅在许可范围内使用，不能因本项目代码开放就统一商用。全量收录保留每件原许可；个人使用、原仓库限定或需另行许可等限制仍然有效，本站不授予额外权利。本项目不宣称取得所有角色或参考素材的独立官方授权；投稿者须明确自己可许可的内容与条件。

应用的本机档案、凭据、聊天、日志、浏览器状态和历史制作记录不随源码或便携包发布。启用自己配置的 AI 后，请求按照对应提供方条款处理；使用前按需检查发送内容和插件权限。当前测试和发布范围以[交付状态](outputs/desktop-pet/docs/release-status.md)为准。

## 7. Star 与支持作者

如果这些项目对你有帮助的话，右上角给个star🌟吧~

欢迎提交反馈、分享作品或参与贡献~

