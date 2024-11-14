---
id: about
layout: page
title: About
description: Basic info and contact info of Daphne Soegijono.
permalink: /about/
---

I write code that makes web/mobile apps run in exchange of coffee fund.

#### Experiences

- Staff Software Engineer at [ProducePay](https://producepay.com/) (April 2022 - Present)
- Senior Software Engineer at [RapidAI](https://www.rapidai.com/) (January 2020 - April 2022)
- Senior Software Engineer at [Invoice2go](https://invoice.2go.com/en-au/) (August 2015 - July 2020)
- Software Developer at Gimmie (September 2014 - July 2015)
- Freelance software engineer (March 2014 - October 2014)
- Software Engineer at SaaS*hr* / A Kronos Company (June 2011 - November 2013)

#### Education

Bachelor of Science degree in Computer Science from [Rutgers University](http://nb.rutgers.edu/)

#### Contact Me

If you'd like to contact me, you can <a href="mailto:hello@thisisdee.com">email me</a> or find me on any of the sites listed below.

#### Me Around the Web

<div class="profiles">
  <ul>
    {% for site in site.data.profiles %}
      <li><a href="{{ site.url }}"><i class="fa fa-{{ site.icon }}"></i> {{ site.name }}</a></li>
    {% endfor %}
  </ul>
</div>
