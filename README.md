# Fcitx5 Dark Transparent DarkRed

一个我自己暗红色主题配色的 [fcitx5-dark-transparent](https://github.com/hosxy/fcitx5-dark-transparent) fork，默认的紫色和我的桌面主题色不太搭配。

## 使用方式

### 1. 安装主题

```shell
# make fcitx5 themes directory
mkdir -p ~/.local/share/fcitx5/themes/fcitx5-dark-transparent-darkred

# clone the repository into fcitx5's themes directory
git clone https://github.com/k4yt3x/fcitx5-dark-transparent-darkred.git ~/.local/share/fcitx5/themes/fcitx5-dark-transparent-darkred
```

### 2. 修改配置文件

然后修改配置文件： `~/.config/fcitx5/conf/classicui.conf`

```conf
# 垂直候选列表（可选）
Vertical Candidate List=False

# 按屏幕 DPI 使用
PerScreenDPI=True

# Font (设置成您喜欢的字体)
Font="Iosevka Regular 14"

# 主题
Theme=fcitx5-dark-transparent-darkred
```

## 截图

![截图](https://user-images.githubusercontent.com/21986859/94630817-50edd780-02b6-11eb-8dae-86f674ba6630.png)

## 本项目基于以下项目

- [fcitx5-dark-transparent](https://github.com/hosxy/fcitx5-dark-transparent)
- [fcitx5-dark](https://github.com/evansan/fcitx5-dark)
