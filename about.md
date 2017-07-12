---
id: about
layout: page
title: About
description: Basic info and contact info of Daphne Soegijono.
permalink: /about/
---

I am a software engineer with a Bachelor of Science degree in Computer Science from [Rutgers University](http://nb.rutgers.edu/).

[Manchester United](http://www.manutd.com/) fanatic, [loves TV shows and movies](http://my-sedentary-life.blogspot.com/), runs on coffee.
Dreams of travelling the world; secretly dreams of being a writer.

#### Experiences

- Software Engineer, Web/Payments at [Invoice2go](https://invoice.2go.com/en-au/) (August 2015 - present)
- Software Developer at [Gimmie](http://www.gimmie.io/) (September 2014 - July 2015)
- Freelance software engineer (March 2014 - October 2014)
- Software Engineer at [SaaS*hr* / A Kronos Company](http://saashr.com/ta/shr2/index.jsp) (June 2011 - November 2013)

#### Contact Me

If you'd like to contact me, you can <a href="mailto:d.soegijono@gmail.com">email me</a>,
<a title="Twitter" href="https://twitter.com/intent/tweet?screen_name=dsoegijono">tweet me</a>, or find me on any of the sites listed below.

#### Me Around the Web

<div class="profiles">
  <ul>
    {% for site in site.data.profiles %}
      <li><a href="{{ site.url }}"><i class="fa fa-{{ site.icon }}"></i> {{ site.name }}</a></li>
    {% endfor %}
  </ul>
</div>
