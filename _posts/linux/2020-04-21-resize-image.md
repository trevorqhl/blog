---
layout: post
title:  "How to reszie, convert images from Linux"
date:   2020-04-21 08:30:52 -0400
img: linux.jpeg
categories: Linux
tags: OS
---

![Linux]({{site.baseurl}}/images/linux.jpeg)

1. Ensure epel is [installed][epel-url]

2. Install ImageMagick
{% highlight ruby %}
yum install imagemagick
{% endhighlight %}

3. Resize image
{% highlight ruby %}

# Convert by width
convert example.png -resize 200 example.png

# Convert by height
convert example.png -resize x100 example.png

# ImageMagick will preserve the aspect ratio
{% endhighlight %}

3. Convert Between Formats
 
{% highlight ruby %}
convert example.png example.jpg
{% endhighlight %}

6. The rest are customized to your preference and kick off installation

[epel-url]: {{site.baseurl}}/linux/2020/04/21/install-epel.html
