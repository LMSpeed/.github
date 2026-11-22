<div align="center">

<a href="https://lmspeed.net/zh"><img src="https://raw.githubusercontent.com/LMSpeed/.github/main/profile/assets/logo-square.png" width="96" height="96" alt="LMSpeed" /></a>

# LMSpeed

**丈量智能前进的速度。**

独立的 LLM API 基准评测、模型对比与循证式端点审计。

[官网](https://lmspeed.net/zh) · [API 测速](https://lmspeed.net/zh/speed) · [在线审计](https://lmspeed.net/zh/audit) · [使用文档](https://docs.lmspeed.net)

[English](https://github.com/LMSpeed/.github/blob/main/profile/README.md) · **简体中文** · [Русский](https://github.com/LMSpeed/.github/blob/main/profile/README.ru.md)

</div>

## 用证据做选择

LMSpeed 帮助开发者看清快速变化的模型与 API 生态。我们测量接口性能、整理模型和服务商信息，并开发开放工具，让你更好地了解所依赖的服务。

- **比较性能：** 首 Token 延迟、吞吐量、可用性与 API 速度。
- **了解模型与服务商：** 模型规格、能力、公开价格与服务商选项。
- **检查端点行为：** 流式响应、工具调用、结构化输出、提示词隔离、上下文召回与经过校准的指纹证据。

## 开放项目

| 项目 | 提供什么 | 从这里开始 |
| --- | --- | --- |
| [Audit](https://github.com/LMSpeed/Audit) | 面向 LLM API 与中转接口的 26 项模块化探针，提供 CLI 和 SDK，支持 OpenAI Chat/Responses 与 Anthropic Messages。 | [在线运行](https://lmspeed.net/zh/audit) · [安装指南](https://github.com/LMSpeed/Audit/blob/main/README.zh-CN.md#安装) · [npm](https://www.npmjs.com/package/@lmspeed/audit) |
| [models](https://github.com/LMSpeed/models) | 附带来源归属的开放模型规格项目。**筹备中**，仓库尚未提供已发布的数据集。 | [浏览现有模型目录](https://lmspeed.net/zh/model) |

单次在本地使用时，可先查看已发布命令的帮助：

```sh
pnpm dlx @lmspeed/audit --help
```

## 探索 LMSpeed

| 资源 | 你可以做什么 |
| --- | --- |
| [API 测速](https://lmspeed.net/zh/speed) | 测量端点的响应性能。 |
| [模型目录](https://lmspeed.net/zh/model) | 比较模型规格与能力。 |
| [服务商目录](https://lmspeed.net/zh/provider) | 了解 API 服务商及其提供的模型。 |
| [在线审计](https://lmspeed.net/zh/audit) | 运行端点检测并分享报告。 |
| [免费 API Key](https://lmspeed.net/zh/free-api-keys) | 查找服务商提供的 API 试用机会。 |
| [使用文档](https://docs.lmspeed.net) | 阅读产品与集成指南。 |

## 我们如何报告结果

观察事实、执行覆盖与结论需要一起看待。能力不支持或请求被拦截不代表检测通过；行为指纹与响应头线索不能证明真实上游模型身份；无发现的审计只覆盖实际测试的负载。详见 [Audit 方法论与证据边界](https://github.com/LMSpeed/Audit/blob/main/README.zh-CN.md#方法论与证据边界)。

## 参与和联系

- **Audit 问题与功能建议：** [提交 Issue](https://github.com/LMSpeed/Audit/issues)，附上版本、协议、预期结果与已脱敏的复现步骤。
- **网站反馈与一般咨询：** 发送邮件至 [team@lmspeed.net](mailto:team@lmspeed.net)。
- **维护者动态：** [X 上的 @nexmoe](https://x.com/nexmoe)。

发布 Issue 或报告前，请移除 API Key、凭据和私有端点细节。参与贡献与使用代码时，请遵循各仓库的贡献说明和许可证。
