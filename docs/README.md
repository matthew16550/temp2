# Base Theme

{% include example_image.html name="base" %}

# Mimeograph

{% include example_image.html name="mimeograph" %}

<pre><code>{{ page | jsonify  | escape }}</code></pre>
<pre><code>{{ site | jsonify  | escape }}</code></pre>
<pre><code>{{ jekyll.environment | jsonify | escape }}</code></pre>

{% capture content %}{% include_relative generated/includes/mimeograph.iuml %}{% endcapture %}
{% capture md %}
```plantuml
{{ content | strip %}
```
{% endcapture %}
{{ content | jsonify | escape }}
{{ md | jsonify | escape }}
{{ md | markdownify }}

</code></pre>
