---
layout: post
title: "Instruction for wirting a post"
excerpt: "Examples and code for details in a post."
tags: [learn, post, record]
comments: true
image:
  feature: sample-image-3.jpg
  credit: WeGraphics
  creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/
---
<section id="table-of-contents" class="toc">
  <header>
    <h3>Overview</h3>
  </header>
<div id="drawer" markdown="1">
*  Auto generated table of contents
{:toc}
</div>
</section><!-- /#table-of-contents -->


# 文字输出

* 文字前面会出现 特殊字符，用于列项

`文字会有底印`



<a markdown="0" href="//blog.csdn.net/hns20070" class="btn">BLOG in CSDN</a>

{% highlight html %}
<figure class="half">
    <a href="/images/image-filename-1-large.jpg"><img src="/images/image-filename-1.jpg"></a>
    <a href="/images/image-filename-2-large.jpg"><img src="/images/image-filename-2.jpg"></a>
    <figcaption>Caption describing these two images.</figcaption>
</figure>
{% endhighlight %}

{% highlight bash %}
highlight bash
{% endhighlight %}

{% highlight yaml %}
highlight yaml 
{% endhighlight %}

{% highlight text %}
highlight text
airway/
├── _includes/
|    ├── _author-bio.html        # bio stuff layout. pulls optional owner data from _config.yml
|    ├── _browser-upgrade.html   # prompt to install a modern browser for < IE9
|    ├── _disqus_comments.html   # Disqus comments script
|    ├── _footer.html            # site footer
|    ├── _head.html              # site head
|    ├── _navigation.html        # site top navigation
|    ├── _open-graph.html        # Twitter Cards and Open Graph meta data
|    └── _scripts.html           # site scripts
├── _layouts/
|    ├── home.html               # homepage layout
|    ├── page.html               # page layout
|    ├── post-index.html         # post index layout
|    └── post.html               # single post layout
├── _posts/                      # MarkDown formatted posts
├── _sass/                       # Sass stylesheets
├── _templates/                  # used by Octopress to define YAML variables for new posts/pages
├── about/                       # sample about page
├── assets/
|    ├── css/                    # compiled stylesheets
|    ├── fonts/                  # webfonts
|    ├── js/
|    |   ├── _main.js            # main JavaScript file, plugin settings, etc
|    |   ├── plugins/            # scripts and jQuery plugins to combine with _main.js
|    |   ├── scripts.min.js      # concatenated and minified _main.js + plugin scripts
|    |   └── vendor/             # vendor scripts to leave alone and load as is
|    └── less/
├── images/                      # images for posts and pages
├── 404.md                       # 404 page
├── feed.xml                     # Atom feed template
├── index.md                     # sample homepage. lists 5 latest posts 
├── posts/                       # sample post index page. lists all posts in reverse chronology
└── theme-setup/                 # theme setup page. safe to remove
{% endhighlight %}

**提示:**: You need to [apply for Twitter Cards](https://dev.twitter.com/docs/cards) before they will begin showing up when links to your site are shared.
{:.notice}


#图片输出:

## 单张图片输出:
<figure>
	<a href="http://ww1.sinaimg.cn/mw600/6c92090djw1elvvz6zsg3j20ph0o7goo.jpg"><img src="http://ww1.sinaimg.cn/mw600/6c92090djw1elvvz6zsg3j20ph0o7goo.jpg"></a>
</figure>

## 并排图片输出:

<figure class="half">
	<a href="http://www.patent-cn.com/wp-content/uploads/2014/10/20141028220.jpg"><img src="http://www.patent-cn.com/wp-content/uploads/2014/10/20141028220.jpg"></a>
	<a href="http://www.patent-cn.com/wp-content/uploads/2014/10/20141028227.jpg"><img src="http://www.patent-cn.com/wp-content/uploads/2014/10/20141028227.jpg"></a>
</figure>


<figure class="third">
	<a href="http://www.patent-cn.com/wp-content/uploads/2014/10/20141020211.jpg"><img src="http://www.patent-cn.com/wp-content/uploads/2014/10/20141020211.jpg"></a>
	<a href="http://www.patent-cn.com/wp-content/uploads/2014/10/20141020214.jpg"><img src="http://www.patent-cn.com/wp-content/uploads/2014/10/20141020214.jpg"></a>
	<a href="http://www.patent-cn.com/wp-content/uploads/2014/10/20141020212.jpg"><img src="http://www.patent-cn.com/wp-content/uploads/2014/10/20141020212.jpg"></a>
</figure>



#  视频输出
<iframe height="498" width="510" src="http://player.youku.com/embed/XNDIzOTMyMTUy" frameborder="0"></iframe>


#   结束
