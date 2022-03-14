# 1.4 与其他 NIST 指导文件的关系

由于参考平台是由容器编排和资源管理平台以及服务网格软件组成的，以下出版物为确保该平台的安全提供了指导，并为本文件的内容提供了背景信息。

- SP800-204，[基于微服务的应用系统的安全策略](https://doi.org/10.6028/NIST.SP.800-204)，讨论了基于微服务的应用的特点和安全要求，以及满足这些要求的总体策略。
- SP800-204A，[使用服务网格构建基于微服务的安全应用](https://doi.org/10.6028/NIST.SP.800-204A)，为基于微服务的应用的各种安全服务（如建立安全会话、安全监控等）提供了部署指导，这些服务使用基于独立于应用代码运行的服务代理的专用基础设施（即服务网格）。
- SP800-204B，[使用服务网格的基于微服务的应用的基于属性的访问控制](https://doi.org/10.6028/NIST.SP.800-204B)，为在服务网格中构建满足安全要求的认证和授权框架提供了部署指导，例如：（1）通过在任何一对服务之间的通信中实现相互认证来实现零信任；（2）基于访问控制模型，如基于属性的访问控制（ABAC）模型的强大访问控制机制，可用于表达广泛的策略集，并在用户群、对象（资源）和部署环境方面可扩展。
- SP800-190，[应用容器安全指南](https://doi.org/10.6028/NIST.SP.800-190)，解释了与容器技术相关的安全问题，并为在规划、实施和维护容器时解决这些问题提出了实用建议。这些建议是针对容器技术架构中的每个层级提供的。