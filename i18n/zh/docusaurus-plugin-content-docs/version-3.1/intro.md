# 在 AWS 上使用 AWS CloudFormation 部署 StarRocks 集群

StarRocks 支持与 AWS CloudFormation 集成，您可以在 AWS 上使用 AWS CloudFormation 快速部署并使用 StarRocks 集群。

## AWS CloudFormation

AWS CloudFormation 是 AWS 提供的一项服务，支持简单且快速地对 AWS 资源和第三方资源（例如 StarRocks 集群）进行建模和配置，帮助您减少资源管理的时间成本，而花更多的时间在使用这些资源。您需要创建一个描述您所需的资源的模板，而 AWS CloudFormation 将负责为您配置这些资源。更多介绍，请参见[什么是 AWS CloudFormation](https://docs.aws.amazon.com/zh_tw/AWSCloudFormation/latest/UserGuide/Welcome.html)。

## 基本概念

### 模版

模板 (Template) 是 JSON 或 YAML 格式的文本文件，描述了 AWS 资源和第三方资源、以及这些资源的属性。更多介绍，请参见[模板](https://docs.aws.amazon.com/zh_cn/AWSCloudFormation/latest/UserGuide/cfn-whatis-concepts.html#w2aab5c15b7)。

### 堆栈

foo
