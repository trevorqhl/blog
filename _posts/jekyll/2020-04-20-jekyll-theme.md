---
layout: post
title:  "How to install a Jekyll theme"
date:   2020-04-20 08:15:52 -0400
img: jekyll.png
categories: Jekyll
tags: Jekyll
---
![Jekyll]({{site.baseurl}}/images/jekyll.png)

In this example, we demonstrate how to install a jekyll theme to start your website. With the consent of my children, we use the [Webjeda cards theme][Webjeda-cards-demo], you can download it from [Github][Webjeda-cards-home].

# Installation 
{% highlight ruby %}
# Go to your home directory 
cd

# Download the project 
git clone git@github.com:sharu725/cards.git

# cd into the jekyll theme and start the jekyll server
cd cards
jekyll server

# If you see failure about missing paginate, you need to install it by root
sudo gem install jekyll-paginate

{% endhighlight %}

[Webjeda-cards-demo]: https://webjeda.com/cards/
[Webjeda-cards-home]: https://github.com/sharu725/cards
