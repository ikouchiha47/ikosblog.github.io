<!DOCTYPE html>

<html>

{% include head.html %}

<body>

  {% include navbar.html %}

  {{ content }}

  {% include footer.html %}

  {% include scripts.html %}

  {% unless site.disable_tracking  %}
    {% include google-analytics.html %}
  {% endunless %}

</body>

</html>
