# centos-lain-box

`laincloud/centos-lain` 这个 vagrant box 的打包脚本。

> - 以下步骤均在 macOS 上进行
> - 打包脚本参考自 [chef/bento](https://github.com/chef/bento)

## 打包过程

### 安装依赖

```
brew install packer
```

### 打包

```
git clone https://github.com/laincloud/centos-lain-box
cd centos-lain-box/centos
bento build centos-lain-7.4-x86_64.json
```
