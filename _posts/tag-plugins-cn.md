title: "Tag Plugins（中文）"
date: "2014-03-16 10:10:16"
categories: Docs
toc: true
---

和 [Freemind](http://github.com/wzpan/hexo-theme-freemind) 一样，你可以使用 [hexo-tag-bootstrap](https://github.com/wzpan/hexo-tag-bootstrap) 来充分发挥 Bootstrap 的威力。在你的 Hexo 博客目录，执行下列命令：

```
$ npm install hexo-tag-bootstrap --save
```

然后就可以像使用其他 hexo tag plugins 一样使用这些 Bootstrap tag plugins 了。

## 文本颜色 ##

插入一段文本，并用特殊的颜色高亮它。

### 语法 ###

```
{% textcolor [style] %}
  text string
{% endtextcolor %}
```

### 示例 ###

```
{% textcolor muted %}Fusce dapibus, tellus ac cursus commodo, tortor mauris nibh.{% endtextcolor %}

{% textcolor primary %}Nullam id dolor id nibh ultricies vehicula ut id elit.{% endtextcolor %}

{% textcolor success %}Duis mollis, est non commodo luctus, nisi erat porttitor ligula.{% endtextcolor %}

{% textcolor info %}Maecenas sed diam eget risus varius blandit sit amet non magna.{% endtextcolor %}

{% textcolor warning %}Etiam porta sem malesuada magna mollis euismod.{% endtextcolor %}

{% textcolor danger %}Donec ullamcorper nulla non metus auctor fringilla.{% endtextcolor %}
```

### 结果 ###

{% textcolor muted %}Fusce dapibus, tellus ac cursus commodo, tortor mauris nibh.{% endtextcolor %}

{% textcolor primary %}Nullam id dolor id nibh ultricies vehicula ut id elit.{% endtextcolor %}

{% textcolor success %}Duis mollis, est non commodo luctus, nisi erat porttitor ligula.{% endtextcolor %}

{% textcolor info %}Maecenas sed diam eget risus varius blandit sit amet non magna.{% endtextcolor %}

{% textcolor warning %}Etiam porta sem malesuada magna mollis euismod.{% endtextcolor %}

{% textcolor danger %}Donec ullamcorper nulla non metus auctor fringilla.{% endtextcolor %}

## 按钮（Buttons） ##

插入一个按钮，按钮可以带有链接、文本，并可以指定样式。

### 语法 ###

```
{% btn url text [style] %}
```

### 示例 ###

```
{% btn http://hahack.com hahack %}

{% btn http://hahack.com hahack primary %}

{% btn http://hahack.com hahack success %}

{% btn http://hahack.com hahack warning %}

{% btn http://hahack.com hahack danger %}

{% btn http://hahack.com hahack info %}
```

### 结果 ###

{% btn http://hahack.com hahack %}

{% btn http://hahack.com hahack primary %}

{% btn http://hahack.com hahack success %}

{% btn http://hahack.com hahack warning %}

{% btn http://hahack.com hahack danger %}

{% btn http://hahack.com hahack info %}

## 标签（Labels） ##

插入一个标签，并为其指定文本和样式。

### 语法 ###

```
{% label text [style] %}
```

### 示例 ###

```
{% label default %}

{% label warinng warning %}

{% label success success %}

{% label danger danger %}

{% label primary primary %}

{% label info info %}
```

### 结果 ###

{% label default %}

{% label warinng warning %}

{% label success success %}

{% label danger danger %}

{% label primary primary %}

{% label info info %}

## 徽章（Badges） ##

插入一个徽章，并为其指定文本。

### 语法 ###

```
{% badge text %}
```

### 示例 ###

```
{% badge 42 %}
```

### 结果 ###

{% badge 42 %}

## 警报（Alerts） ##

插入一段警报文本信息，并为其指定样式。

### 语法 ###

```
{% alert [style] %}
   Alert string
{% endalert %}
```

### 示例 ###

```
{% alert warning %}Best check yo self, you're not looking too good.{% endalert %}

{% alert danger %}Change a few things up and try submitting again.{% endalert %}

{% alert success %}You successfully read this important alert message.{% endalert %}

{% alert info %}This alert needs your attention, but it's not super important.{% endalert %}
```

### 结果 ###

{% alert warning %}Best check yo self, you're not looking too good.{% endalert %}

{% alert danger %}Change a few things up and try submitting again.{% endalert %}

{% alert success %}You successfully read this important alert message.{% endalert %}

{% alert info %}This alert needs your attention, but it's not super important.{% endalert %}
