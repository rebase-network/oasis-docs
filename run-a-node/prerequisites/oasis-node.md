# Oasis Node

Oasis节点是从[Oasis Core](https://github.com/oasisprotocol/oasis-core)的`go/`路径下创建的二进制文件。

它既包含了运行Oasis节点的逻辑，也提供了注册、 抵押等命令行操作。

{% hint style="warning" %}
Oasis节点 当前仅支持 x86 \ _64 Linux系统。
{% endhint %}

## 下载二进制文件

{% hint style="success" %}
我们建议你自己从源码上编译Oasis Node，进行节点的部署运行。
{% endhint %}

二进制文件的链接在[网络参数](../../oasis-network/network-parameters.md) 页面提供。

## 从源码开始开始编译

从源码开始开始编译，请看 [Oasis Core的编译环境设置和方式](https://docs.oasis.dev/oasis-core/development-setup/build-environment-setup-and-building) 文档，来了解更多内容。

{% hint style="danger" %}
[`master`](https://github.com/oasisprotocol/oasis-core/tree/master/) 分支的代码可能与主网中其他节点使用的代码不兼容。

请确保使用[网络参数](../../oasis-network/network-parameters.md)中指定的版本。
{% endhint %}

## `PATH` 添加 `oasis-node`

To install the `oasis-node` binary for the current user, copy/symlink it to `~/.local/bin`.

要为当前用户安装`oasis-node`二进制文件，请将其复制或链接到 `~/.local/bin` 。

要为系统的所有用户安装`oasis-node`二进制文件，请将其复制到`/usr/local/bin`。

