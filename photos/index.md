---
layout: page
title: Photos
excerpt: "Photo Gallery"
comments: false
---

{% capture the_gallery %}
	../assets/img/gallery/1.jpg
	../assets/img/gallery/2.jpg
	../assets/img/gallery/3.jpg
	../assets/img/gallery/4.jpg
	../assets/img/gallery/5.jpg
	../assets/img/gallery/6.jpg
	../assets/img/gallery/7.jpg
	../assets/img/gallery/8.jpg
	../assets/img/gallery/9.jpg
	../assets/img/gallery/10.jpg
	../assets/img/gallery/11.jpg
	../assets/img/gallery/12.jpg
	../assets/img/gallery/13.jpg
	../assets/img/gallery/14.jpg
	../assets/img/gallery/15.jpg
	../assets/img/gallery/16.jpg
{% endcapture %}

{% include gallery images=the_gallery caption="" cols=3 %}
