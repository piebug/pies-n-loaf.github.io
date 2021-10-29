# pie-dough

pie dough is need to make pies

syntax to pass values into an include:

```liquid
{% include template.html myVal="value" %}
```

and then to use the value in the include:

```liquid
{{ include.myVal }}
```

to show drafts (located in `_drafts/`) use:

```shell
bundle exec jekyll serve --drafts
```
