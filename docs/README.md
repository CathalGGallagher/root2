

# Air Lcl
Air and LCL is Awesome


<!--
{% if page.show_sidebar %}
### found sidebar
  <div class="sidebar">
    <ul>
    {% for post in site.posts %}
        <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }} 
        </li>
    {% endfor %}
    </ul>

  </div>
{% endif %}-->


## Background

## OnBoarding/How to 
### How to write an article
### Kramdown
A [link](http://kramdown.gettalong.org)
to the kramdown homepage.


{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
       {{ post.excerpt }} 
    {% endfor %}
  </ul>
{% endfor %}


test [post](./2021/03/29/how-to-post.html)





