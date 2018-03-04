### 在这里记录一些自己喜欢的工具以及喜欢的主题的配置（防止每次换电脑或者需要重新安装的时候又要各种去找资料）

对于一些比较日常的工具，如果有一款自己觉得赏心悦目的主题配置，该是一件多么赞的事情啊（作为一个简单阳光的人，真是不能容忍没有色彩的世界，哈哈）

### vs code
比较喜欢的是一个主题插件，属于`atom`的主题，插件名字为`One Dark Pro`,直接安装重启就行,效果如下，我个人比较喜欢的清新类型：

![images](https://raw.githubusercontent.com/SunShinewyf/tools-setting/master/assets/1.png)

### iterm

`iterm`的体验还是很棒的，但是主题有点少，而且按照[这里]去配置`iterm`的主题，没有达到效果，于是看到一个同事的配色非常炫酷，然后就直接收藏了，这个主题叫`oh-my-zsh`

github地址在[这里](https://github.com/robbyrussell/oh-my-zsh),[这里](http://www.jianshu.com/p/0d265d9f914b)有具体的安装过程

配色也是我喜欢的类型，很清新，而且比较好的是它在执行`git`命令会显示对应的分支，效果如下：

![images](https://raw.githubusercontent.com/SunShinewyf/tools-setting/master/assets/2.png)

### macdown

对于`macdown`这款`markdown`编辑器，觉得还是挺不错的，对于编辑工具这种，我原始的做法是使用的线上的`马克飞象`,然后过渡到像`vs code`这种编辑器里面直接写`markdown`，但是体验不太好，因为不能立即看到效果，开始用`macdown`的时候，还是觉得蛮清爽的。并且找到了一种比较喜欢的主题方案，主题也是借鉴的别人的，地址移步[这里](https://github.com/cssmagic/Oh-My-MacDown),将文件下载并拷贝到`macdown`的主题文件里面，就可以在`macdown`的配置中直接选择主题样式就搞定了，最后的效果显示如下:


![images](https://raw.githubusercontent.com/SunShinewyf/tools-setting/master/assets/3.png)

### autojump

- `autojump`使用
    在命令行中可以随便跳转到某个目录，而不需要一次次地 `cd ./`,但是前提是你必须在此之前去到过这个目录，因为`autojump`中有一个文件存放着所有你去过的目录

- `autojump`安装
   - 安装包
   ```js
    $ brew install autojump
   ```
   - 修改`~/.zshrc`里面的`plugin`：
   ```js
    plugins=(git autojump)
   ```
   然后继续在上述文件中添加:
   ```js
   [[ -s $(brew --prefix)/etc/profile.d/autojump.sh ]] && . $(brew --prefix)/etc/profile.d/autojump.sh
   ```
   - 使配置生效
   ```js
    source ~/.zshrc
   ```

- 使用
  ```js
    j directory
  ```
