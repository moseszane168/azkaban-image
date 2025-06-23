<p align="center">
  <h1 align="center">Azkaban 任务调度器</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>
</p>

## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍
‌[Azkaban‌](https://github.com/azkaban/azkaban) Azkaban 是一个由LinkedIn 开源的批量工作流任务调度器，用于在一个工作流中以特定顺序运行一组工作和流程。它通过定义任务之间的依赖关系并提供Web 用户界面来帮助用户管理和跟踪工作流。Azkaban 适用于调度各种类型的作业，如Command、Hadoop MapReduce、Hive、Spark 和Pig 等，并支持自定义插件。

**核心特性：**
1. 批量工作流调度：Azkaban 允许用户定义和执行包含复杂依赖关系的工作流。
2. Web 用户界面：提供一个易于使用的Web 界面，用于创建、维护、监控和跟踪工作流。
3. 任务依赖：Azkaban 使用job 配置文件来定义任务之间的依赖关系，确保作业按照正确的顺序执行。
4. 支持多种作业类型：可以调度各种类型的作业，如Command、Hadoop MapReduce、Hive、Spark 和Pig 等。
5. 可插拔的插件机制：支持自定义插件，扩展Azkaban 的功能，例如支持新的作业类型或与其他系统集成。
6. 分布式执行：Azkaban 可以通过多个执行器来提高调度能力和可靠性。
7. 错误处理和重试：支持重试机制，可以在任务失败时自动重试。
8. 安全管理：提供身份验证和授权机制，确保只有授权用户才能访问和操作工作流。
9. 历史记录和审计：记录作业的执行历史，方便进行审计和问题排查。

本项目提供的开源镜像商品 [**`Azkaban-任务调度器`**]()，已预先安装 Azkaban 软件及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。

**架构设计：**

![](./images/img.png)

> **系统要求如下：**
> - CPU: 4vCPUs 或更高
> - RAM: 16GB 或更大
> - Disk: 至少 50GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                                           | 特性说明 | 备注 |
|--------------------------------------------------------------------------------------------------------------------------------| --- | --- |
| [Azkaban24.1.3-arm-v1.0](https://github.com/HuaweiCloudDeveloper/azkaban-image/tree/Azkaban24.1.3-arm-v1.0?tab=readme-ov-file) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/azkaban-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md