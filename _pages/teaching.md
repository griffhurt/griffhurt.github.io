---
layout: page
permalink: /teaching/
title: Teaching
description: Information about the courses I have TA'ed for.
nav: true
nav_order: 2
semesters: ["Spring 2024", "Fall 2023", "Spring 2023"]
---

<div class="teaching">
{% for semester in page.semesters %}
    <div class="semester mb-5">
        <h3>{{ semester }}</h3>
        {%- assign categorized_courses = site.teaching | where: "semester", semester -%}
        {% for course in categorized_courses %}
            <div class="card mt-3 p-3">
                <h5>{{ course.title }}</h5>
                <p>{{ course.time }} @ {{ course.room }}</p>
                <a class="btn btn-primary" href="{{ course.url | relative_url }}" role="button">Course Materials</a>
            </div>
        {% endfor %}
    </div>
{% endfor %}
</div>