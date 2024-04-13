---
layout: page
permalink: /teaching/
title: Teaching
description: Information about the courses I have TA'ed for.
nav: true
nav_order: 2
semesters: ["Spring 2024", "Fall 2023", "Spring 2023"]
---

<h4>Current Office Hours:</h4>
<ul>
    <li>Mondays 1PM - 2:30PM: In-Person @ <a href="/130n">130 N Bellefield</a> or <a href="https://pitt.zoom.us/j/92691220005">Zoom</a></li>
    <li>Tuesdays 11AM - 2PM: In-Person @ <a href="/130n">130 N Bellefield</a> or <a href="https://pitt.zoom.us/j/92691220005">Zoom</a></li>
    <li>Thursdays 4PM - 5:30PM: <a href="https://pitt.zoom.us/j/92691220005">Zoom</a></li>
</ul>

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