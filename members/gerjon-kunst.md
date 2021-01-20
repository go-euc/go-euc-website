---
layout: page
title: Gerjon Kunst
comments: false
---
{% assign author = site.authors['gerjon'] %}

<img style="float: left; width: 250px; margin-right: 30px;" src="{{ site.url }}{{ author.picture | relative_url }}" alt="{{ author.display_name }}"> Gerjon Kunst is a Principal Consultant at RawWorks in het Netherlands, focusing on future Workspace and Cloud. Gerjon has 20 years experience in the IT business starting as a system engineer working his way up to a IT pro with broad and in depth knowledge of Workspace and Cloud. 

Gerjon is a known presenter on Citrix User Groups and E2EVC and as he is a Microsoft Certified Trainer you might have met him in a classroom somewhere.

<div class="social-button-member">
{% if author.linkedin %}
<a style="text-decoration: none;" href="{{author.linkedin}}" target="_blank"><img class="author-box-socials-icon" src="{{ site.baseurl }}/assets/images/social/027-linkedin.png" alt="linkedin"></a>
{% endif %}

{% if author.twitter %}
<a style="text-decoration: none;" href="{{author.twitter}}" target="_blank"><img class="author-box-socials-icon" src="{{ site.baseurl }}/assets/images/social/008-twitter.png" alt="twitter"></a>
{% endif %}

{% if author.web %}
<a style="text-decoration: none;" href="{{author.web}}" target="_blank"><img class="author-box-socials-icon" src="{{ site.baseurl }}/assets/images/social/030-html-5.png" alt="website"></a>
{% endif %}

{% if author.github %}
<a style="text-decoration: none;" href="{{author.github}}" target="_blank"><img class="author-box-socials-icon" src="{{ site.baseurl }}/assets/images/social/050-github.png" alt="github"></a>
{% endif %}

{% if author.reddit %}
<a style="text-decoration: none;" href="{{author.reddit}}" target="_blank"><img class="author-box-socials-icon" src="{{ site.baseurl }}/assets/images/social/018-reddit.png" alt="reddit"></a>
{% endif %}
</div>

