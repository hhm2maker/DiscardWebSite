---
layout: default
---

# 欢迎来到Maker

## FAQ

> 为什么下载文件(Maker)的速度这么慢？<br/>

因为下载文件放置在Github，所以国内访问会比较慢，如果有小伙伴愿意提供国内服务器可以联系我（可以通过下个问题后面两种方式联系我）。

> 如何反馈BUG或提出建议？<br/>

*   [Github issues](https://github.com/hhm2maker/Maker/issues) 
*   邮箱：1248694620@qq.com
*   Q群：586779832

> Maker左侧每个按钮对应的界面都有什么用？

1. 逐帧：一帧一帧的绘制，通常用来绘制不规则的灯光
2. 灯光语句：制作富有逻辑的灯光，也是主推的功能
3. 页面：把绘制的灯光和按键绑定到一起
4. 演奏导出：把几个页面合成到一起，生成演奏的文件
5. 演奏：Maker与Launchpad进行连接，然后开始演奏啦ヽ(○´∀`)ﾉ♪
6. 播放器：定制你的播放器
7. 帮助：你懂的

> 我认为有些界面风格不统一，而且不怎么好看。

对的，我非常需要一位（或多位）UI帮助我完成对界面的整改。

> Maker对于设备的控制如何，我是说发送长消息？

Maker可以发送长消息，但是仅限于娱乐，因为长消息的功能太强大了，我无法马上消化完。<br/>（短消息为发送普通的单色灯光，一个Midi灯光会发送几十上百个短消息，长消息除了可以发送单色灯光还可以发送Novation给设备预支好的内容,比如自定义RGB颜色的灯光（Retina就是发送长消息）

> Maker会自动更新吗？

软件正在频繁的迭代功能和修复BUG，无法给出一个稳定的版本，所以暂不提供自动更新服务。

> Maker还有会有其他辅助功能吗？

现在的Maker更像是Live的大型插件，所以会有丰富的功能，比如教程轨辅助、模拟键盘等。祝你们玩的开心！

> 软件自带了两个项目，分别是什么内容呢？

*  Nothing对应的是教程轨辅助的功能，里面什么也没有，因为这样会让教程轨提示的按键更加明显。
*  Keyboard对应的是模拟键盘，一些简单的单键灯光。

> Maker可以和Live配合吗，在灯光方面？

当然，我也十分推荐相互配合，因为Maker没有独立输出音频的功能。灯光方面可以相互弥补，例如：按任意键都能亮对应按键的灯，那么肯定是Live制作的更加简单便捷。

> Maker是否需要Max软件的支持，如果Live（9）不安装Max是否会影响灯光效果？

不需要，因为Maker会自己建立与Launchpad的连接。不过需要安装novation-usb-driver-2.7，你可以从Attachments文件夹中找到（进入演奏页面的时候也会提示安装），它的作用是可以让两款或以上的软件同时控制Launchpad。




Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.



###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
