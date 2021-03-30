---

---

# Air Lcl
Air and LCL is Awesome


{% if page.show_sidebar %}
### found sidebar
 <!--> <div class="sidebar">
    <ul>
    {% for post in site.posts %}
        <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }} 
        </li>
    {% endfor %}
    </ul>

  </div>-->
{% endif %}


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
       {{ post.excerpt }} 
    </li>
  {% endfor %}
</ul> 

