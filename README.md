# Fittable

A [Typst](https://typst.app/) package distributing leftover space of table or grid into `auto` columns.

```typ
#import "@preview/fittable:0.1.0 as fittable: fit
```

```typ
#let data = ([a], [long long column], [middle])
#fit(columns: (auto,) * data.len(), ..data)
```
