# symbols
A repository dedicated to the development of graphical symbols for the AIXM fetures.


{% for image in site.static_files %}
 {% if image.path contains 'features/' %}
  {% if image.path contains '.png' %}
   ![image]({{ image.path }} 'image')
  {% endif %}
 {% endif %}
{% endfor %}
