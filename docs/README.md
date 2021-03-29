# Air Lcl

## Background

## OnBoarding/How to 
### How to write an article
### Kramdown
A [link](http://kramdown.gettalong.org)
to the kramdown homepage.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p> {{ post.summary }} </p>
    </li>
  {% endfor %}
</ul>
