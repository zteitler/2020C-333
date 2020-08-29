---
layout: page
title: Quizzes
---

## Quizzes

{% assign ql = site.quizzes | sort: "quiznum" %}

| **Quiz** | **Due Date** | **Solutions** |
| :--- | :--- | :--- |
{% for quiz in ql -%}

| [**Quiz {{ quiz.quiznum }} Instructions**]({{site.baseurl}}{{ quiz.url }}) | {{ homework.duedate | date_to_string: "ordinal", "US"  }} |  |
{% endfor %}
