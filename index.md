---
layout: default
slug: call
---
<div class="row">
 <div class="col-md-8" markdown="1">

# MODELS 2018, Copenhagen - Denmark

<p class="text-justify">
MODELS is the premier conference series for model-driven software and systems engineering. Since 1998, MODELS has covered all aspects of modeling, from languages and methods, to tools and applications. Attendees of MODELS come from diverse backgrounds, including researchers, academics, engineers and industrial professionals. MODELS 2018 is a forum for participants to exchange cutting-edge research results and innovative practical experiences around modeling and model-driven software and systems. This year’s edition will provide an opportunity for the modeling community to further advance the foundations of modeling, and come up with innovative applications of modeling in emerging areas of cyber-physical systems, embedded systems, socio-technical systems, cloud computing, big data, security, open source, and sustainability. We invite you to join us at MODELS 2018, in Copenhagen, Denmark 14-19 October 2018, and to help shape the modelling methods and technologies of the future!
</p>

</div>
<div class="col-md-4">
    <div class="panel panel-primary">
      <div class="panel-heading">
        <h3 class="panel-title">News</h3>
      </div>
      <ul class="list-group">
        {% for post in site.posts limit:10 %}
        <li class="list-group-item">
          <h5 class="list-group-item-heading">{{ post.date | date: "%B %-d, %Y" }}</h5>
          <p class="list-group-item-text">{{ post.title }}</p>
        </li>
        {% endfor %}
      </ul>
  </div>
  <a class="twitter-timeline" data-lang="en" data-width="400" data-height="400" href="https://twitter.com/modelsconf">Tweets by @modelsconf</a> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
 </div>
</div>


