---
layout: post
title: "Document for python learning"
excerpt: "Some tips."
tags: [learn, post, python]
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

# 问题集：

## import失败，提示缺少什么modoule，怎么办？
	
	* 1 下载pip,https://pypi.python.org/pypi/pip
	
	* 2 WINDOWS下进入cmd，进入get-pip.py所在目录，运行python get-pip.py (注意此时，要将python放入系统路径内。如果你的电脑中有多个版本的python，请注意修改系统路径，因为pip只会被安装到当前cmd中正在被调用的python里面)
	
	* 3 将python 目录下的script ，放入系统路径即可。
	
	* 4 重新启动cmd, 运行pip install [你所需要的module的名字]
	
	* 5 如果以上步骤无法解决问题的话，也可以去http://www.lfd.uci.edu/~gohlke/pythonlibs/， 寻找你想要安装的包。（注意这个网址里面的包非官方，但是可以找到支持64位的安装包，官方的通常没有。）





<a markdown="0" href="//blog.csdn.net/hns20070" class="btn">BLOG in CSDN</a>
