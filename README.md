[![Bolt.new：浏览器中的 AI 驱动全栈 Web 开发](./public/social_preview_index.jpg)](https://bolt.new)

# Bolt.new：浏览器中的 AI 驱动全栈 Web 开发

Bolt.new 是一个 AI 驱动的 Web 开发助手，让您可以直接在浏览器中提示、运行、编辑和部署全栈应用程序——无需本地环境设置。如果您想使用 Bolt 开源代码库构建自己的 AI 驱动的 Web 开发助手，[点击这里开始！](./CONTRIBUTING.md)

## Bolt.new 的独特之处

Claude、v0 等都很出色，但您无法安装软件包、运行后端或编辑代码。这就是 Bolt.new 的优势所在：

- **浏览器中的全栈开发**：Bolt.new 将前沿 AI 模型与基于 **StackBlitz WebContainers** 的浏览器开发环境相结合。这使您能够：
  - 安装和运行 npm 工具和库（如 Vite、Next.js 等）
  - 运行 Node.js 服务器
  - 与第三方 API 交互
  - 从聊天界面部署到生产环境
  - 通过 URL 分享您的作品

- **具有环境控制的 AI**：与传统开发环境中 AI 只能辅助代码生成不同，Bolt.new 赋予 AI 模型对整个环境的**完全控制**，包括文件系统、node 服务器、包管理器、终端和浏览器控制台。这使 AI 助手能够处理应用程序的整个生命周期——从创建到部署。

无论您是经验丰富的开发人员、产品经理还是设计师，Bolt.new 都能让您轻松构建生产级全栈应用程序。

对于有兴趣使用 WebContainers 构建自己的 AI 驱动开发工具的开发人员，请查看此代码库中的开源 Bolt 代码！

## 使用技巧

以下是充分利用 Bolt.new 的一些技巧：

- **明确指定技术栈**：如果您想使用特定的框架或库（如 Astro、Tailwind、ShadCN 或任何其他流行的 JavaScript 框架），请在初始提示中提及它们，以确保 Bolt 相应地搭建项目。

- **使用增强提示图标**：在发送提示之前，尝试点击"增强"图标，让 AI 模型帮助您完善提示，然后在提交前编辑结果。

- **先搭建基础，再添加功能**：在深入更高级功能之前，确保应用程序的基本结构已就位。这有助于 Bolt 理解项目的基础，并确保在构建更高级功能之前一切都正确连接。

- **批量处理简单指令**：将简单指令合并到一条消息中可以节省时间。例如，您可以一次性要求 Bolt 更改配色方案、添加移动端响应式设计并重启开发服务器，这样可以显著节省时间并减少 API 积分消耗。

## 常见问题

**在哪里注册付费计划？**  
Bolt.new 可以免费开始使用。如果您需要更多 AI 令牌或想要私有项目，可以在 [Bolt.new](https://bolt.new) 设置中（应用程序左下角）购买付费订阅。

**如果达到免费使用限制会怎样？**  
一旦达到每日免费令牌限制，AI 交互将暂停，直到第二天或您升级计划。

**Bolt 是否处于测试阶段？**  
是的，Bolt.new 目前处于测试阶段，我们正在根据反馈积极改进。

**如何报告 Bolt.new 问题？**  
查看 [Issues 部分](https://github.com/stackblitz/bolt.new/issues) 来报告问题或请求新功能。请使用搜索功能检查是否有人已经提交了相同的问题/请求。

**Bolt 目前支持哪些框架/库？**  
Bolt.new 支持大多数流行的 JavaScript 框架和库。如果它能在 StackBlitz 上运行，就能在 Bolt.new 上运行。

**如何确保我的框架/项目在 Bolt 中运行良好？**  
我们很高兴与 JavaScript 生态系统合作以改进 Bolt 的功能。通过 [hello@stackblitz.com](mailto:hello@stackblitz.com) 联系我们，讨论如何合作！
