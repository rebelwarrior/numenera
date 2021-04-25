---
title: Numenéra Tier Abilities
layout: default
---

## Tier Abilities 
{:.title.is-2.add_left_margin} 

<div class="container is-widescreen">
  <table class="table is-striped is-bordered">
    {% for row in site.data.tier_abilities %}
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
			Choose two Tier Abilities
		</tfoot>
  </table>
</div>
<br>