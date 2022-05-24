## Tell VSCode's Comment Shortcut to use Liquid Comments on .liquid files

### Before

.liquid
```liquid
<!-- {% if product.tags contains 'new' %} -->
```

### After

.liquid
```liquid
{% comment %} {% if product.tags contains 'new' %}  {% endcomment %}
```

### Why?

Keep your .liquid file comments hidden from the client.
