# Base Theme

<img src="generated/images/base.png" alt="TODO" width="250"/>

# Mimeograph

<a href="{{site.repository_url}}/tree/main/examples/mimeograph.puml"><img src="generated/images/mimeograph.png" alt="" width="250"/></a>


<pre><code>{{ page | jsonify  | escape }}</code></pre>
<pre><code>{{ site | jsonify  | escape }}</code></pre>
<pre><code>{{ jekyll.environment | jsonify | escape }}</code></pre>

{% capture foo %}
```plantuml
title bar
```
{% endcapture %}
{{ foo | markdownify }}

include_relative generated/includes/mimeograph.iuml %}</code></pre>
