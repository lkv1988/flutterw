## 使用说明

### 环境

确保你的电脑有Python3的命令行环境

> 当前仅支持MacOS

### 安装

下载`flutterw`到你的工程目录中，并赋予`flutterw`可执行权限

### 配置

- 在`flutterw`的同级目录中创建`flutterw.properties`文本文件
- 编辑`flutterw.properties`中`sdk.version`为目标版本
- 如果是中国大陆网络环境，可能需要网络加速，那么配置中加入`cn=true`即可

### 执行

- 命令行：直接执行`flutterw`，后跟正常的其他flutter命令即可
- IDE：修改`Flutter SDK path`为${HOME}/.flutterw/${VERSION}/flutter即可（所下载的不同版本flutter包就在这个文件夹下）

### 关于flutterw

受`gradlew`启发，有了`flutterw`后工程师们的flutter环境统一再也不是问题了。

### 开源协议

`Apache-2.0`

