---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<br />
　　**Delu Zeng**, Ph.D., Professor, Ph.D. & M.S. Supervisor. I have published **100+ papers** in top journals and conferences, including:  
**IEEE TNNLS, IEEE TIP, IEEE GRSL, IEEE SPL**, and **ICML, AAAI, IJCAI, ICCV, CVPR, ICASSP**, etc. I have **led 3 NSFC projects** (National Natural Science Foundation of China), and many provincial/ministerial & industrial projects. I also serve as a reviewer for many leading journals, including **IEEE TIP, IEEE TNNLS, IEEE TII, IEEE TMM, Neural Networks, Neurocomputing**, etc. Member of **ACM, CCF, IEEE**.




Conferences
----------
<div>
  <table>
  {% for post in site.conferences_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
  <a href="/conferences/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>

<!-- <div margin-bottom:100px>
  <a href="/conferences/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>  -->


Journals
----------
<div>
  <table>
  {% for post in site.journals_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
   <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>

<!-- <div margin-bottom:100px>
  <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>  -->


