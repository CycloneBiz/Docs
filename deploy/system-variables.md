# System Variables

For configuring MongoDB you have two options. If you are deploying with systemd on a linux server, use the `config.ini` file. If you are using a docker/git hosting option use System Variables (which is seamless and will update automatically).

### Configurating

{% code title="config.ini" %}
```ini
[MongoDB]
uri = mongodb://localhost:27017
name = OpenLoop

[Customize]
name = OpenLoop
theme = primary
```
{% endcode %}

For system variables use \`type\_setting\`. A example would be `mongodb_uri`.
