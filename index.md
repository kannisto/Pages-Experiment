
# Github pages experiment

This is an experiment.

<h2>{{ site.data.menu.menuitem_list_title }}</h2>
<ul>
   {% for item in site.data.menu.menuitems %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>
