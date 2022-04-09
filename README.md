 ## zsh usage on MacOS

 在升级MacOS Catalina以上， 使用shell工具时，经常提示

 ```
The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.

```
简而言之，就是从这个版本开始，macos 开始使用 zsh 替代 bash 用做默认的 shell 工具。

### Mac 上将 zsh 用作默认 Shell

Apple官网操作指南：https://support.apple.com/zh-cn/HT208050 -> 如何更改默认 Shell

### 安装

macos 默认已经安装了 zsh，贴一下安装/升级方式。

```
//升级brew
brew upgrade
// 升级
brew install zsh

```

### 使用 oh my zsh

安装 oh my zsh 可以通过 curl 方式或 wget 方式，或者使用国内镜像

```

# curl
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# wget
$ sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"

# gitee
$ sh -c "$(curl -fsSL https://gitee.com/mcornella/ohmyzsh/raw/master/tools/install.sh)"

```

### 配置主题

全部主题可以在omz Github 主题列表上查看（https://github.com/ohmyzsh/ohmyzsh/wiki/Themes）

oh my zsh: https://ohmyz.sh/
