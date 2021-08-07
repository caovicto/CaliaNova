---
layout: default
title: Archive
---

<div class="glitch" data-text="Archive">Archive</div>

<div class="flex-container">
    <div class="flex-child simple-list">
        <ul> 
            {% for chapter in site.archive %}
                <li>
                <a href="{{ site.baseurl }}{{ chapter.url }}">{{ chapter.title }}</a>
                </li>
            {% endfor %}
        </ul>
    </div>
    <div class="flex-child" >
        <script type="text/javascript" src="https://spiderforest.com/widgets/portrait-banner.php?g=false&id=cano"></script>
    </div>
</div>
