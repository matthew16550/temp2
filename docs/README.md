# Base Theme

{% include example_image.html name="base" %}

# Mimeograph

| {% include example_image.html name="mimeograph" %} | {% include plantuml_file.html file="generated/includes/mimeograph.iuml" %} |

{% capture content %}{% include_relative generated/includes/mimeograph.iuml %}{% endcapture %}
```plantuml
{{ content | strip }}
```
