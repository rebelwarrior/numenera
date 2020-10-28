---
title: Numenéra Descriptors
layout: default

---

## Foci
{:.title.is-2.add_left_margin} 

<div class="container is-widescreen">
  <table class="table is-striped is-bordered">
    {% for row in site.data.foci %}
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
		<tfoot class="grey-text">
			* Numenera Destiny
		</tfoot>
  </table>
</div>
<br>