# Base Theme

{% include example_image.html name="base" %}

# Mimeograph

{% include example_image.html name="mimeograph" %}

<pre><code>{{ page | jsonify  | escape }}</code></pre>
<pre><code>{{ site | jsonify  | escape }}</code></pre>
<pre><code>{{ jekyll.environment | jsonify | escape }}</code></pre>

{% capture md %}
```plantuml
{% include_relative generated/includes/mimeograph.iuml %}
```
{% endcapture %}
{{ md | markdownify }}

</code></pre>
