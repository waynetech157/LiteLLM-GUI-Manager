# LiteLLM GUI Manager

**LiteLLM GUI Manager 是一款面向 Windows 的 LiteLLM 图形化管理工具。**

通过图形界面管理 YAML 配置、Provider 与模型前缀、API Base URL、.env 环境变量、LiteLLM Proxy 启停和本地使用统计——无需手工编辑配置文件或频繁使用命令行。

> [LiteLLM](https://github.com/BerriAI/litellm) 本身是开源项目。LiteLLM GUI Manager 是独立开发的第三方 Windows 桌面工具，并非 LiteLLM 官方产品，将作为**收费商业软件**发布。

**状态：v1.0.0 — 即将发布**

---

[English](README.md) &nbsp;|&nbsp; [价格](#价格) &nbsp;|&nbsp; [下载](#下载) &nbsp;|&nbsp;[观看演示](#演示视频) &nbsp;|&nbsp; [条款](https://waynetech157.github.io/LiteLLM-GUI-Manager/terms.html) &nbsp;|&nbsp; [隐私](https://waynetech157.github.io/LiteLLM-GUI-Manager/privacy.html) &nbsp;|&nbsp; [退款](https://waynetech157.github.io/LiteLLM-GUI-Manager/refund.html)

---

## 价格

**US$29 — 一次性购买**

LiteLLM GUI Manager 当前商业方案为 **永久 License（Perpetual License）**。

永久 License 允许你持续使用已购买的版本。未来重大版本或单独发布的产品可能需要另行购买。

> 正式公开发布后将开放购买结账。

**技术支持：** [waynetech157@outlook.com](mailto:waynetech157@outlook.com)

[条款与条件](https://waynetech157.github.io/LiteLLM-GUI-Manager/terms.html) · [隐私政策](https://waynetech157.github.io/LiteLLM-GUI-Manager/privacy.html) · [退款政策](https://waynetech157.github.io/LiteLLM-GUI-Manager/refund.html)

---
## 演示视频

观看完整的 LiteLLM GUI 管理器演示：

**LiteLLM GUI Manager for Windows – Easy Setup, Model Management & Claude Code Demo**

[![LiteLLM GUI 管理器演示](screenshots/youtube-demo-thumbnail.png)](https://youtu.be/DaOdhE2iS-U)

▶ [在 YouTube 上观看完整演示](https://youtu.be/DaOdhE2iS-U)

---

## 软件截图



**主界面**
![主界面](screenshots/main-interface.png)

**Provider 与 Base URL 管理**
![Provider 与 Base URL 管理](screenshots/base-provider-management.png)

**环境变量与 API Key 管理**
![环境变量与 API Key 管理](screenshots/env-api-key-management.png)

**使用统计**
![使用统计](screenshots/usage-statistics.png)

**License 与激活**
![License 与激活](screenshots/license-activation.png)

---

## 为什么需要 LiteLLM GUI Manager

[LiteLLM](https://github.com/BerriAI/litellm) 是一个强大的代理，可以统一接入数十家 LLM 服务商。但在 Windows 上配置它，意味着需要手工编辑 YAML 文件、`.env` 文件、Provider 前缀、Base URL 和 API Key，并在每次改动后重新从终端重启代理。

LiteLLM GUI Manager 是一个桌面管理层，作为 LiteLLM 的辅助工具运行。**它不替代 LiteLLM，也不自行提供 AI 模型服务。** 它通过本地 Python 环境启动 LiteLLM Proxy，并为周边所有配置提供结构化的图形界面。

---

## 主要功能

- **多 YAML 配置管理** — 通过表单式编辑器创建、复制、重命名、删除和切换多个 LiteLLM YAML 配置文件。
- **模型配置与模型列表获取** — 添加和编辑 `model_name`、真实模型 ID、`api_base`、`api_key`、高级参数及 `model_info`；从配置的 API Base 获取可用模型列表。
- **BASE URL / 自定义 Provider 管理** — 在一处统一保存和管理 API Base URL、Provider 名称和接入点别名。
- **`.env` 环境变量管理** — 表格式编辑器，敏感值支持显示/隐藏，自动标记在 YAML 中引用但 `.env` 中缺失的变量。
- **API Key / master key 掩码编辑** — 敏感字段默认隐藏，限制复制/剪切路径以减少意外泄露。
- **LiteLLM Proxy 启动 / 停止与实时日志** — 选择配置和端口后启动或停止代理，应用内实时查看日志输出。
- **LiteLLM 组件安装 / 版本检查 / 卸载** — 无需接触命令行即可安装、更新或移除 LiteLLM 包。
- **Provider 目录 / 前缀更新** — 保持 Provider 前缀和基础 Provider 目录处于最新状态，辅助填写模型 ID。
- **使用统计、筛选、CSV 导出与删除** — 本地记录每次请求的 Provider、模型、Token 数、估算费用、延迟和成功状态，支持筛选、CSV 导出和按时间范围删除。
- **设置备份与恢复** — 将 GUI 设置、BASE/Provider 数据和 YAML 配置打包为单个 ZIP 归档。
- **中英文界面** — 随时切换语言，激活窗口中也可切换。
- **商业设备绑定 License 激活** — 开发者签发、与设备绑定的 `.lic` 文件解锁应用。

支持 LiteLLM 所支持的服务商，包括 OpenAI、Anthropic、NVIDIA、Ollama、Gemini、Groq、OpenRouter 等 LiteLLM 支持的服务。LiteLLM GUI Manager 不声称获得上述任何服务商的官方支持、合作或背书——具体的服务商连接能力取决于 LiteLLM 本身及各服务商自己的 API。

---

## 快速开始

1. 下载并解压 LiteLLM GUI Manager。
2. 运行 `LiteLLM_GUI_Manager.exe`。
3. 首次使用可直接在激活窗口中切换中文/英文界面。
4. 使用与设备绑定的 `.lic` License 激活软件。
5. 如果本机尚未安装 LiteLLM，请使用**管理 → 安装组件**。
6. 选择或创建一个 LiteLLM YAML 配置。
7. 根据需要配置模型、BASE URL 和 `.env` / API 凭据。
8. 选择启动配置和端口。
9. 启动 LiteLLM Proxy。
10. 将 Claude Code 或其他兼容的 API 客户端连接到本地 LiteLLM Proxy，并发起一次测试请求。

---

## License 激活

LiteLLM GUI Manager 使用**设备绑定 License**，每台设备单独签发。

**激活步骤：**

1. 启动应用 — 若未找到有效 License，激活窗口会自动打开。
2. 复制激活窗口中显示的**设备 ID**。
3. 正式公开发布后，通过购买页面完成购买。
4. 你将收到一个与你的设备 ID 绑定的 `.lic` 文件。
5. 点击**导入 License** 并选择该 `.lic` 文件。
6. 应用解锁，可进入主界面。

**迁移到新设备：**  
`.lic` 文件与一台设备绑定。更换新设备需要使用该设备自己的设备 ID 重新激活——设置备份不能转移或替代 License。机器迁移政策请联系技术支持。

---

## 备份与恢复

使用**管理 → 备份与恢复**将配置迁移到另一台电脑或保留安全副本。

| 默认包含 | 可选（需用户主动勾选） | 不包含 |
|---|---|---|
| GUI 设置 | `.env` — 可能含 API Key；备份 ZIP 本身未加密 | `license.lic` |
| BASE / Provider 数据 | `usage_stats.db`（历史使用统计） | |
| YAML 配置文件 | | |

在新电脑上恢复备份可以找回你的配置，但该电脑仍需使用自己的设备 ID 重新完成有效激活。

与设备相关的具体路径不会从旧电脑迁移过来；恢复的配置将被放入目标电脑当前的配置目录中。

---

## 隐私与本地数据

LiteLLM GUI Manager 不为你的配置、API Key、License 数据或使用统计数据库提供自己的云同步服务。设置、YAML 配置和统计数据均写入本地文件，应用不会向开发者发送遥测数据或崩溃报告。

但这**不代表**应用永远不产生网络请求。根据你在 GUI 中的操作，以下场景会产生正常的网络访问：

- LiteLLM / 模型服务商 API 请求（通过 LiteLLM Proxy 转发）
- 获取 Provider 模型列表
- Provider 目录更新
- 在 GitHub 上检查 LiteLLM 最新版本

API Key 保存在你配置的位置——通常是本地 `.env` 文件或直接写在 YAML 配置中——并仅按照 LiteLLM 与服务商的正常认证流程，用于你自己发起的请求。GUI 中的字段掩码可以减少屏幕显示和复制粘贴时的意外泄露，但这是一项便利措施，不能替代操作系统级别的安全防护或你自身的凭据管理习惯。

---

## 数据存放位置

在打包版 Windows 应用中，典型的用户数据目录是：

`%APPDATA%\LiteLLM_GUI_Manager\`


其中可能包括：

| 文件 | 用途 |
|---|---|
| `settings.json` | GUI 设置 |
| `license.lic` | 设备绑定 License |
| `usage_stats.db` | 本地使用统计 |
| `provider_endpoints_custom.json` | 自定义 BASE 条目 |
| `provider_endpoints.json` | 可选的完整 BASE 目录覆盖 |
| `crash.log` | 仅在需要写入诊断/错误信息时生成 |

`provider_prefixes.json` 可能存放在 `%APPDATA%\LiteLLM_GUI_Manager\` 中，也可能存放在应用程序可执行文件旁边，具体取决于可写位置和 Provider 目录的更新历史。

**YAML 配置文件**默认存放在程序旁的 `config\` 目录中。配置目录可在 GUI 中修改。

**`.env`** 跟随当前选定的配置目录——不固定存放在 `%APPDATA%` 下。

---

## 系统要求

| 要求 | 详情 |
|---|---|
| 操作系统 | Windows 10 / 11，64 位 |
| GUI 运行时 | 打包版 GUI 本身无需额外安装 |
| LiteLLM Proxy | 需要本地 Python 环境（推荐 3.10–3.13），通过**管理 → 安装组件**安装 |
| 网络 | API 调用、模型列表获取和版本检查需要网络连接；激活后打开 GUI 本身无需联网 |

---

## 下载

> **v1.0.0 — 即将发布。**  
> 发布 ZIP 和版本说明将在正式发布时在此处公布。自 v1.0.0 正式版本起，每个发布文件都会附带 SHA-256 校验值，方便你核对下载文件。

<!-- 发布文件将在此列出 -->

请仅从本官方仓库页面下载。

---


## 常见问题

**LiteLLM GUI Manager 是什么？**  
一款 Windows 桌面应用，为配置和运行 LiteLLM Proxy 提供图形界面——包括 YAML 配置、Provider、`.env` 变量、代理启停和本地使用统计。

**这是 LiteLLM 官方产品吗？**  
不是。LiteLLM GUI Manager 是独立第三方应用，与 LiteLLM / BerriAI 项目没有隶属、背书或赞助关系。

**LiteLLM GUI Manager 是否包含 LiteLLM 本身？**  
不包含。LiteLLM GUI Manager 不捆绑 LiteLLM 的源代码。它通过**管理 → 安装组件**在你的机器上安装和管理官方 `litellm` Python 包，并通过本地 Python 环境启动它。

**我的配置、API Key 和统计数据存放在哪里？**  
均存放在你本机。具体路径见[数据存放位置](#数据存放位置)。应用不提供任何云端存储或同步。

**可以把设置迁移到另一台电脑吗？**  
可以，使用**备份与恢复**功能。GUI 设置、BASE/Provider 数据和 YAML 配置默认包含在内。可选与排除项见[备份与恢复](#备份与恢复)。

**备份中包含我的 API Key 或 License 吗？**  
`.env`（可能含 API Key）仅在你创建备份时主动勾选后才会包含——备份 ZIP 未加密，请妥善保管。`license.lic` 文件永远不会包含在设置备份中。

**可以使用比 GUI 当前已验证版本更新的 LiteLLM 版本吗？**  
可以，由你自行决定尝试。GUI 会区分"当前已验证版本"（经过测试）与 GitHub 上的最新发布版本。它不会因为发现较新但尚未验证的版本，就自动安装、自动降级或强制切换你的 LiteLLM 版本——版本变更始终是你通过**管理 → 安装组件**主动执行的操作。

**可以使用自定义或兼容 OpenAI 的 Provider 吗？**  
可以。除内置 Provider 目录外，你可以通过 BASE / Provider 管理器添加自定义 Base URL 和 Provider 条目。

---

## 技术支持

如有激活问题、Bug 反馈或其他疑问：

- 支持联系方式：`waynetech157@outlook.com`
- 请附上你的 Windows 版本、问题描述，以及相关日志内容（如有）。

---

## 免责声明

LiteLLM GUI Manager 是由独立开发者开发和维护的独立第三方桌面应用。它**不是** LiteLLM / BerriAI、OpenAI、Anthropic、Google、NVIDIA 或任何其他 AI 模型及 API 服务商的官方产品。不暗示与上述任何方存在关联、赞助或背书关系。

LiteLLM、模型 API、网络服务、模型输出质量、定价、配额、可用性及服务商服务条款完全由各自的第三方控制。用户须自行负责遵守所有适用的服务商条款和法律法规、保护自身凭据，并承担产生的所有 API 费用。

LiteLLM GUI Manager 的专有软件许可证将随正式发布提供，文件名为 `EULA-en.txt` / `EULA-zh.txt`。第三方开源组件声明将提供为 `THIRD_PARTY_LICENSES.txt`。两者目前仍为草稿，尚未在本仓库中发布。

---

## 相关链接

- LiteLLM 文档：[https://docs.litellm.ai/](https://docs.litellm.ai/)
- LiteLLM 源码：[https://github.com/BerriAI/litellm](https://github.com/BerriAI/litellm)
- 功能演示：[LiteLLM GUI Manager for Windows – Easy Setup, Model Management & Claude Code Demo](https://youtu.be/DaOdhE2iS-U)
- 购买：即将上线
- 技术支持：`waynetech157@outlook.com`

---

*版权所有 © 2026。保留所有权利。*  
*LiteLLM GUI Manager 是专有商业软件。*
