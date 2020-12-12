---
layout: page
title: Quizzes and Exams
---

## Quizzes

{% assign ql = '' | split: '' %}
{%- for q in site.quizzes -%}
  {%- unless q.hide -%}
    {%- assign ql = ql | push: q -%}
  {%- endunless -%}
{%- endfor -%}
{%- assign ql = ql | sort: "quiznum" -%}

| **Quiz** | **Due Date** | **Instructions** | **Solutions** |
| :--- | :--- | :--- | :--- |
{% for quiz in ql -%}

| **Quiz {{ quiz.quiznum }}** | {{ quiz.duedate | date_to_string: "ordinal", "US"  }} | [Quiz {{ quiz.quiznum }} Instructions]({{ quiz.url | relative_url }}) | {% if quiz.solutions %}[Quiz {{quiz.quiznum}} Solutions]({{ quiz.solutions }}){% endif %} |
{% endfor -%}
{%- if ql.size == 0 -%}
|   |   |   |
{%- endif %}




## Exams

| **Exam** | **Exam Date** | **Instructions** | **Study Guide** |
| :--- | :--- | :--- | :--- |
| **Exam 1** | Monday, October 5, 2020 | [Exam 1 Instructions]({{ "/exams/exam1-instructions" | relative_url }}) | [Exam 1 Study Guide]({{ "/exams/exam1-studyguide" | relative_url }}) |
| **Exam 2** | Monday, November 9, 2020 | [Exam 2 Instructions]({{ "/exams/exam2-instructions" | relative_url }}) | [Exam 2 Study Guide]({{ "/exams/exam2-studyguide" | relative_url }}) |
| **Final Exam** | Wednesday, December 16, 2020 | [Final Exam Instructions]({{ "/exams/finalexam-instructions" | relative_url }}) | [Final Exam Study Guide](https://zeno.boisestate.edu/classes/m333-fall2020/exams/final-studyguide.html) |
