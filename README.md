# pie-dough

pie dough is need to make pies.

made with [jekyll](https://github.com/jekyll/jekyll) ([documentation](https://jekyllrb.com/)) using [minima v2.5.1](https://github.com/jekyll/minima/tree/v2.5.1) as the base theme.

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
