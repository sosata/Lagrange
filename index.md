---
layout: page
title: 
---
Sohrab Saeb is a computer science researcher at [kernel.co](http://kernel.co).

<!-- Pagination links -->
<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-button pagination-active" href="{{ site.github.url }}{{ paginator.next_page_path }}" class="next">Older</a>
  {% else %}
    <span class="pagination-button">Older</span>
  {% endif %}

  {% if paginator.previous_page %}
    <a class="pagination-button pagination-active" href="{{ site.baseurl }}{{ paginator.previous_page_path }}">Newer</a>
    {% else %}
      <span class="pagination-button">Newer</span>
  {% endif %}

</div>
