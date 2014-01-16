---
layout: default
title: 你好！GitHub Pages
---

今天参考[using-jekyll-with-pages](https://help.github.com/articles/using-jekyll-with-pages "GitHub Pages Help")教程,
把GitHub空间建立起来了，学到一些新的东西，也解决了几个windows下的问题。不错不错。

Troubleshooting
-----
### mkdir error
	Update Gemfile:
		source 'https://rubygems.org'
		gem 'jekyll','1.4.2'
	run command: bundle install

### Liquid error: incompatible character encodings: UTF-8 and GBK
	$chcp 65001
	$bundle exec jekyll serve