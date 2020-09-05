---
layout: page
title: Quizzes
---

## Quizzes

{% assign ql = '' | split: '' %}
{%- for q in site.quizzes -%}
  {%- unless q.hide -%}
    {%- assign ql = ql | push: q -%}
  {%- endunless -%}
{%- endfor -%}
{%- assign ql = ql | sort: "quiznum" -%}

| **Quiz** | **Due Date** | **Solutions** |
| :--- | :--- | :--- |
{% for quiz in ql -%}

| [**Quiz {{ quiz.quiznum }} Instructions**]({{ quiz.url | relative_url }}) | {{ quiz.duedate | date_to_string: "ordinal", "US"  }} | {% if quiz.solutions %}[Solutions]({{ quiz.solutions }}){% endif %} |
{% endfor -%}
{%- if ql.size == 0 -%}
|   |   |   |
{%- endif -%}
