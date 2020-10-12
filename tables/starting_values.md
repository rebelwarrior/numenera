---
title: Numenéra Starting Values
layout: default
---

<div class="container is-widescreen">
  <table class="table is-striped is-bordered">
    {% for row in site.data.starting_values %}
      {% if forloop.first %}
        <tr>
          {% for pair in row %}
            <th class="is-selected">{{ pair[0] }}</th>
          {% endfor %}
        </tr>
      {% endif %}

      {% tablerow pair in row %}
        {{ pair[1] }}
      {% endtablerow %}
    {% endfor %}
  </table>
</div>