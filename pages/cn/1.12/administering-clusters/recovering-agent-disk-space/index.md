---
layout: layout.pug
navigationTitle: 恢复代理磁盘空间
title: 恢复代理磁盘空间
menuWeight: 900
excerpt: 恢复代理节点卷上的空间
enterprise: false
---

<!-- The source repo for this topic is https://github.com/dcos/dcos-docs -->

如果任务填满代理节点的保留卷，有一些选项可以恢复空间：

- 检查每个组件的运行状况并重新启动每个组件。

- 如果工作目录位于单独的卷上（如按建议在 [代理节点](/cn/1.12/installing/production/system-requirements/#agent-nodes) 中），则您可以清空此卷并重新启动该代理。

如果两种方法均无效，您可能需要重新镜像节点。
