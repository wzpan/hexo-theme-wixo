title: Tag Plugins
date: 2014-03-16 10:17:16
categories: Docs
toc: true
---

Like the [Freemind](http://github.com/wzpan/hexo-theme-freemind) theme, you can use [hexo-tag-bootstrap](https://github.com/wzpan/hexo-tag-bootstrap) to fully take advantages of Bootstrap. To use these tag plugins, you need to install it first. In your blog root folder, execute the following command:

```
$ npm install hexo-tag-bootstrap --save
```

Then you can use these tag plugins in your blog, as easily as you normally do using hexo tag plugins. 

<!-- more -->

## Text Color ##

Convey meaning through color with a handful of emphasis utility classes. These may also be applied to links and will darken on hover just like our default link styles.

### Syntax ###

{% raw %}
```
{% textcolor [style] %}
  text string
{% endtextcolor %}
```
{% endraw %}

### Examples ###

{% raw %}
```
{% textcolor muted %}Fusce dapibus, tellus ac cursus commodo, tortor mauris nibh.{% endtextcolor %}

{% textcolor primary %}Nullam id dolor id nibh ultricies vehicula ut id elit.{% endtextcolor %}

{% textcolor success %}Duis mollis, est non commodo luctus, nisi erat porttitor ligula.{% endtextcolor %}

{% textcolor info %}Maecenas sed diam eget risus varius blandit sit amet non magna.{% endtextcolor %}

{% textcolor warning %}Etiam porta sem malesuada magna mollis euismod.{% endtextcolor %}

{% textcolor danger %}Donec ullamcorper nulla non metus auctor fringilla.{% endtextcolor %}
```
{% endraw %}

### Results ###

{% textcolor muted %}Fusce dapibus, tellus ac cursus commodo, tortor mauris nibh.{% endtextcolor %}

{% textcolor primary %}Nullam id dolor id nibh ultricies vehicula ut id elit.{% endtextcolor %}

{% textcolor success %}Duis mollis, est non commodo luctus, nisi erat porttitor ligula.{% endtextcolor %}

{% textcolor info %}Maecenas sed diam eget risus varius blandit sit amet non magna.{% endtextcolor %}

{% textcolor warning %}Etiam porta sem malesuada magna mollis euismod.{% endtextcolor %}

{% textcolor danger %}Donec ullamcorper nulla non metus auctor fringilla.{% endtextcolor %}

## Buttons ##

Inserts a button with target links, text and specified color.

### Syntax ###

{% raw %}
```
{% btn url text [style] %}
```
{% endraw %}

### Examples ###

{% raw %}
```
{% btn http://hahack.com hahack %}

{% btn http://hahack.com hahack primary %}

{% btn http://hahack.com hahack success %}

{% btn http://hahack.com hahack warning %}

{% btn http://hahack.com hahack danger %}

{% btn http://hahack.com hahack info %}
```
{% endraw %}

### Results ###

{% btn http://hahack.com hahack %}

{% btn http://hahack.com hahack primary %}

{% btn http://hahack.com hahack success %}

{% btn http://hahack.com hahack warning %}

{% btn http://hahack.com hahack danger %}

{% btn http://hahack.com hahack info %}

## Labels ##

Inserts a label with text and specified color.

### Syntax ###

{% raw %}
```
{% label text [style] %}
```
{% endraw %}

### Examples ###

{% raw %}
```
{% label default %}

{% label warinng warning %}

{% label success success %}

{% label danger danger %}

{% label primary primary %}

{% label info info %}
```
{% endraw %}

### Results ###

{% label default %}

{% label warinng warning %}

{% label success success %}

{% label danger danger %}

{% label primary primary %}

{% label info info %}

## Badges ##

Inserts a badge with text.

{% alert danger %}Badges won't self collapse in Internet Explorer 8 because it lacks support for the `:empty` selector.{% endalert %}

### Syntax ###

{% raw %}
```
{% badge text %}
```
{% endraw %}

### Examples ###

{% raw %}
```
{% badge 42 %}
```
{% endraw %}

### Results ###

{% badge 42 %}

## Alerts ##

Inserts alert messages with text and specified color.

### Syntax ###

{% raw %}
```
{% alert [style] %}
   Alert string
{% endalert %}
```
{% endraw %}

### Examples ###

{% raw %}
```
{% alert warning %}Best check yo self, you're not looking too good.{% endalert %}

{% alert danger %}Change a few things up and try submitting again.{% endalert %}

{% alert success %}You successfully read this important alert message.{% endalert %}

{% alert info %}This alert needs your attention, but it's not super important.{% endalert %}
```
{% endraw %}

### Results ###

{% alert warning %}Best check yo self, you're not looking too good.{% endalert %}

{% alert danger %}Change a few things up and try submitting again.{% endalert %}

{% alert success %}You successfully read this important alert message.{% endalert %}

{% alert info %}This alert needs your attention, but it's not super important.{% endalert %}

