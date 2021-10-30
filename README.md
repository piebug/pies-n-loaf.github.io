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

projects:

- add "category" page(s) at the URL for the category that shows all posts in the category
- add a tag search page that shows all the current tags and allows clicking to see posts by tag
  - will allow multi-clicking (but OR and NOT functionality will be later... if ever)
- thoughts view without excerpts, plus a "continue" link at the end of excerpts
- recipe view with either a collection that has cute things like ingredients, cooktime, etc
- custom pagination
