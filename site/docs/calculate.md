---
layout: docs
menu: docs
title: Calculate Transform
permalink: /docs/calculate.html
---

{:#calculate}
### Calculate

{: .suppress-error}
```json
{
  ...
  "transform": [
    {"calculate": ..., "as" ...} // Calculate Transform
     ...
  ],
  ...
}
```

{% include table.html props="calculate,as" source="CalculateTransform" %}
__Example__

This example use `calculate` to derive a new field, then `filter` data based on the new field.

<span class="vl-example" data-name="bar_filter_calc"></span>