---
date: 2025-04-11
hide:
  - navigation
---

# DCE 5.0 商业版 v0.27.1

本页可下载 DCE 5.0 商业版的离线安装包和校验文件。

[返回下载导览页](../index.md#_2){ .md-button } [更多历史版本](./dce5-installer-history.md){ .md-button }

## 下载

| 文件名称 | 版本 | 架构 | 文件大小 | 下载 | 更新日期 |
| ------- | --- | ---- | ------ | --- | ------- |
| offline-v0.27.1-amd64.tar | v0.27.1 | AMD 64 | 28.47 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.27.1-amd64.tar) | 2025-04-11 |
| offline-v0.27.1-arm64.tar | v0.27.1 | <font color="green">ARM 64</font> | 25.74 GB | [:arrow_down: 下载](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/dce5/offline-v0.27.1-arm64.tar) | 2025-04-11 |

## 校验

进入离线安装包下载目录。

=== "AMD 64"

    执行以下命令校验安装包：

    ```sh
    echo "6b3c7e365349b594c0b5b9636b1b6dfe8892652c1c07596c9a4017e4a4222971585409f43387e2a7743da3022da8a10438a5d31eb166c6ba8c10fee579fef347  offline-v0.27.1-amd64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-v0.27.1-amd64.tar: OK
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令校验安装包：

    ```sh
    echo "eb94f2d33fb3751dc49176030b5fe857b257b55f1284dbd4a0768ef5f36b179479a9eef885352badb0c361d0d4655693ed2a24569ce5e8eb71137625953518d0  offline-v0.27.1-arm64.tar" | sha512sum -c
    ```

    校验成功会打印：

    ```none
    offline-v0.27.1-arm64.tar: OK
    ```

## 安装

成功校验离线包之后，

=== "AMD 64"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-v0.27.1-amd64.tar
    ```

=== "<font color="green">ARM 64</font>"

    执行以下命令解压缩 tar 包：

    ```sh
    tar -zxvf offline-v0.27.1-arm64.tar
    ```

- 安装请参阅[商业版安装流程](../../install/commercial/start-install.md)
- 成功安装之后请联系我们授权：电邮 info@daocloud.io 或致电 400 002 6898

## 模块

DCE 5.0 商业版包含以下模块，按需即插即用满足各类应用场景：

| 模块 | 介绍 | 最新动态 |
| ---- | --- | ------ |
| 全局管理 | 负责用户访问控制、权限、工作空间与层级、审计日志、个性化外观设置等 | [0.35.0](../../ghippo/intro/release-notes.md#0350) |
| 容器管理 | 管理集群、节点、工作负载、Helm 应用、CRD、命名空间等 K8s 核心功能 | [0.37.0](../../kpanda/intro/release-notes.md#0370) |
| 可观测性 | 提供丰富的仪表盘、场景监控、数据查询、告警等图文信息 | [0.35.1](../../insight/intro/release-notes.md#0351) |
| 应用工作台 | 基于容器的 DevOps 应用平台，支持 Jenkins, Tekton, GitOps 等流水线作业 | [0.35.0](../../amamba/intro/release-notes.md#0350) |
| 多云编排 | 集中管理多云、混合云、跨云资源的应用编排，具备多云灾备、故障恢复等能力 | [0.24.0](../../kairship/intro/release-notes.md#0240) |
| 微服务引擎 | 提供注册发现、服务治理、配置管理、微服务网关等治理能力 | [0.45.0](../../skoala/intro/release-notes.md#0450) |
| 服务网格 | 基于 Istio 开源技术构建的面向云原生应用的下一代服务网格 | [v0.34.1](../../mspider/intro/release-notes.md#v0341) |
| 中间件 Elasticsearch | 目前首选的全文搜索引擎 | [0.24.0](../../middleware/elasticsearch/release-notes.md#0240) |
| 中间件 Kafka | 基于开源软件 Kafka 提供的分布式消息队列服务 | [0.23.0](../../middleware/kafka/release-notes.md#0230) |
| 中间件 MinIO | 一款非常热门的轻量、开源对象存储方案 | [0.21.0](../../middleware/minio/release-notes.md#0210) |
| 中间件 MySQL | 应用最广泛的开源关系数据库 | [0.26.0](../../middleware/mysql/release-notes.md#0260) |
| 中间件 RabbitMQ | 实现了高级消息队列协议 (AMQP) 的开源消息代理软件 | [0.27.0](../../middleware/rabbitmq/release-notes.md#0270) |
| 中间件 Redis | 一款内存数据库缓存服务 | [0.27.0](../../middleware/redis/release-notes.md#0270) |
| 镜像仓库 | 用于存储 K8s、DevOps 和容器应用开发的镜像 | [0.24.0](../../kangaroo/intro/release-notes.md) |
| 网络 | 针对不同的 Linux 内核，支持多种 CNI 组合方案 | [0.16.2](../../network/intro/release-notes.md) |
| 存储 | 提供统一数据存储服务，支持文件、对象、块、本地存储，轻松接入存储厂商方案 | [v0.16.2](../../storage/hwameistor/release-notes.md) |

## 更多

- [在线文档](../../dce/index.md)
- [报告 bug](https://github.com/DaoCloud/DaoCloud-docs/issues)
