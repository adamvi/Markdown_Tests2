---
layout: default
title: "HoMe"
---

#
(intentional blank space to get text below the Nav Bar)



Statistical graphics are powerful -- your eyes will jump to the graph below immediately and skip this paragraph automatically. When we see a nice graph, we often wonder how it was made (e.g. [this one](http://stackoverflow.com/q/12675147/559676) via xkcd).

![via xkcd](http://i.imgur.com/4staRNH.png)

Vistat aims to provide _working_ recipes for statistical graphics by building them from source. The website is based on Github/Jekyll, and graphs are generated dynamically through the R package [**knitr**](http://yihui.name/knitr), hence reproducibility is guaranteed, and readers can see the source code at the same time.

##  Annual Reports

[Reports](report_landing.html)

## Latest 10 posts

<section class="content">
  <ul class="listing">
  {% for post in site.posts limit:10 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  <li><a href="archive.html">Read More...</a></li>
</ul>
</section>

## How to contribute

You can [fork the repository](https://github.com/adamvi/Markdown_Tests2) on Github and submit a pull request to us. For more details, see [about](about.html).

## Copyright

All the content in this website is licensed under [CC BY-NC-SA 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/). This site is hosted on [GitHub](https://github.com) Pages using the [UP theme](http://carlosbecker.com/posts/up-a-jekyll-theme/) for [Jekyll Bootstrap](http://jekyllbootstrap.com).
