---
layout: post
title: "Profil Andrianto"
author: Andrianto
modified:
excerpt: Hey Semuanya, apakabarr."
tags: []
---

For those of you who may have content written by multiple authors on your site you can now assign different authors to each post if desired.

Previously the theme used a global author for the entire site and those attributes would be used in all bylines, social networking links, Twitter Card attribution, and Google Authorship. These `owner` variables were defined in `config.yml`

Start by modifying or creating a new `authors.yml` file in the `_data` folder and add your authors using the following format.

{% highlight yaml %}
# Authors

Andrianto:
  name: Andrianto
  web: http://andrianto.com
  email: andrinto21@gmail.com
  bio: "Ibadah adalah prioritas utama ku."
  avatar: bio-photo-2.jpg
  twitter: extravagantman
  google:
    plus: Andt Nto

cornelius_fiddlebone:
  name: Rudi Wijaya
  email: rudiwijayaa15@gmail.com
  bio: "Selalu bersyukur, Insya Allah?"
  avatar: bio-photo.jpg
  twitter: @rudi_wijayaa
  google:
    plus: CorneliusFiddlebone
{% endhighlight %}

To assign Billy Rick as an author for our post. You'd add the following YAML front matter to a post:

{% highlight yaml %}
author: billy_rick
{% endhighlight %}
