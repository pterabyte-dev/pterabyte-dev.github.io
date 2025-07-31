---
 title: Hello World!
 tags: []
 color: primary
 description: Look at that, a new site where I can share my configurations, testing, and thoughts on different topics relating to Docker, TrueNAS, networking, and home lab in general
 comments: true
---
{%- assign assets = "/" | append: site.baseurl | append: "assets/posts/" | append:  page.path | replace: ".md","" | replace: "_posts/","" -%}
![]({{ assets }}/heroimg.png)

**Hello Everyone!** 

{% raw %}
{% capture carousel_images %}
https://bit.ly/2BBbVhc
https://bit.ly/2DOtxXB
{% endcapture %}
{% include elements/carousel.html %}
{% endraw %}

The purpose of this site is to share different configurations, testing, and thoughts I may have on topics relating to technology and things I am currently messing around with in my home lab. Primary topics will include docker apps, docker configurations, networking, TrueNAS, etc. Based on the my previous statement, it would be easy to guess that I am currently using docker-compose and TrueNAS in my home lab.

## How Was This Site Made?
This site was created using a modified Jekyll template hosted on GitHub Pages. The original template being used is [portfolYOU](https://github.com/yousinix/portfolYOU){:target="_blank"} created by Youssef Andrawes. A guide will be posted at a later date detailing how to host your own static website on Github Pages and how to modify an existing Jekyll template.

## Future Topics and Projects
Posts and topics will closely be related to things that I am testing and deploying in my home lab. Lately I have been messing around with docker networking, iptables, scripting, and docker-compose behavior, all on TrueNAS. Potential future topics are as follows:
* Docker MACVLAN Networks
* Docker IPVLAN Networks
* VLANS, Trunks, and Bridges on TrueNAS
* Docker Isolated One-to-Many Internal Network
* Persistant iptables on TrueNAS
* Managing Custom Applications on TrueNAS

I also will be sharing docker-compose files and different scripts I create along the way. My one goal here is to share the information I have that I wish I had when I originally ran into an issue, in hopes that someone will find it useful.
