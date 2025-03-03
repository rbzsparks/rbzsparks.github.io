---
layout: default
title: publications
permalink: /publications
---

## In Prep
{% bibliography --template bibtemplate --style _bibliography/rbzs.csl --query @*[year=in prep] %}
{% bibliography --template bibtemplate --style _bibliography/rbzs.csl --query @*[year=accepted pending data collection] %}
<br>

## Under Review
{% bibliography --template bibtemplate --style _bibliography/rbzs.csl --query @*[year=under review] %}
<br>

## In Press
 {% bibliography --template bibtemplate --style _bibliography/rbzs.csl --query @*[year=in press] %}
<br>

{% for year in (2022..2025) reversed %}
<h2>{{year}}</h2>
{% bibliography --template bibtemplate --style _bibliography/rbzs.csl --query @*[year={{year}}] %}
<br>
{% endfor %} 

<script>
    $("body").html($("body").html().replace(/R. Z. Sparks/g,'<b>R. Z. Sparks</b>'));
</script>




