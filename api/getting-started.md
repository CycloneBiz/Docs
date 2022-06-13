---
description: How to start to build a OpenLoop Plugin
---

# Getting Started

By default OpenLoop executes your plugin in a environment with attributes to control. You can access the Environment with the variable `plugin`.

{% code title="starter.pyl" %}
```python
plugin.name = "My Cool Plugin"
print("You can see this in console!")
```
{% endcode %}
