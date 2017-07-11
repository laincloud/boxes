# centos-lain-box

`laincloud/centos-lain` 这个 vagrant box 的打包脚本。

> 以下步骤均在 macOS 上进行。

## 打包过程

### 安装依赖

```
brew install packer
gem install bento-ya
```

### 打包

```
git clone https://github.com/laincloud/centos-lain-box
cd centos-lain-box/
bento build centos-lain-7-x86_64.json
```
