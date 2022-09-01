# react基础环境安装

默认已经安装过react

## react-native-cli

```bash
#使用npx
sudo npx install -g react-native-cli
#使用npm
sudo npm install -g react-native-cli
```

## CocoaPods

[CocoaPods](https://cocoapods.org/)是用 Ruby 编写的包管理器（可以理解为针对 iOS 的 npm）。从 0.60 版本开始 react native 的 iOS 版本需要使用 CocoaPods 来管理依赖。你可以使用下面的命令来安装 cocoapods。

```bash
sudo gem install cocoapods
```

或者可以使用 brew 来安装

```bash
brew install cocoapods
```



## 安装react-native-cli常见问题

### 问题1

执行 react-native init XXX 创建 ReactNative 项目的时候遇到了如下异常提示：

```bash
Installing react-native...
Consider installing yarn to make this faster: https://yarnpkg.com
```

解决办法

首先，终端中输入如下命令：

```bash
npm install -g yarn 
```

其次，执行安装成功后校验版本

```bash
yarn --version
```

