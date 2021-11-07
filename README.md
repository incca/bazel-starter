# 前端项目的 Bazel 实践

## 一、环境配置

### bazelisk

可以通过 npm 的方式安装 [bazelisk](https://github.com/bazelbuild/bazelisk)

```shell
npm i -g @bazel/bazelisk
bazel --version
```

## 二、命令

### 1. 构建

```shell
bazel build ${rule_name}
```

### 2. 运行

```shell
bazel run ${rule_name}
```
