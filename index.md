---
layout: default
title: "Miroslav Sykora — Home"
---


<section class="hero" aria-labelledby="intro-title">
<h1 id="intro-title">Exploring Optimization, Math, and Machine Learning</h1>
<p class="meta">This site is my working lab notebook: sharing ideas, proofs, derivations, experiments, and reflections as I learn in public. It also doubles as a lightweight CV showcasing projects I’m building or have shipped.</p>
</section>


<section aria-labelledby="purpose-title">
<h2 id="purpose-title">Purpose</h2>
<div class="item">
<p>Two goals:</p>
<ol>
<li><strong>Share my academic journey</strong> — concise notes on optimization, probability, and ML. Expect definitions, theorems, proofs, and worked examples (with LaTeX).</li>
<li><strong>Show my work</strong> — personal notes and projects that reveal how I think, what I’m reading, and what I can build.</li>
</ol>
</div>
</section>


<section aria-labelledby="academic-title">
<h2 id="academic-title">Academic Notes (latest)</h2>
<div class="list">
{% assign items = site.academic | sort: 'date' | reverse | slice: 0, 5 %}
{% for post in items %}
<article class="item">
<h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
<div class="meta">{{ post.date | date: "%B %e, %Y" }}{% if post.tags %} · {{ post.tags | join: ', ' }}{% endif %}</div>
</article>
{% endfor %}
<p class="meta"><a href="{{ '/pages/academic' | relative_url }}">See all academic notes →</a></p>
</div>
</section>


<section aria-labelledby="personal-title">
<h2 id="personal-title">Personal Notes (latest)</h2>
<div class="list">
{% assign items = site.personal | sort: 'date' | reverse | slice: 0, 5 %}
{% for post in items %}
<article class="item">
<h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
<div class="meta">{{ post.date | date: "%B %e, %Y" }}{% if post.tags %} · {{ post.tags | join: ', ' }}{% endif %}</div>
</article>
{% endfor %}
<p class="meta"><a href="{{ '/pages/personal' | relative_url }}">See all personal notes →</a></p>
</div>
</section>


<section aria-labelledby="projects-title">
<h2 id="projects-title">Projects (in progress & shipped)</h2>
<div class="list">
{% assign items = site.projects | sort: 'date' | reverse | slice: 0, 6 %}
{% for post in items %}
<article class="item">
<h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
<div class="meta">{{ post.date | date: "%B %e, %Y" }}{% if post.role %} · Role: {{ post.role }}{% endif %}</div>
</article>
{% endfor %}
<p class="meta"><a href="{{ '/pages/projects' | relative_url }}">See all projects →</a></p>
</div>
</section>


<section id="about" aria-labelledby="about-title">
<h2 id="about-title">About</h2>
<div class="item">
<p>TODO: ADD bio. Include a simple contact: <a href="mailto:personal@sykoramiroslav.com">personal@sykoramiroslav.com</a> · <a href="https://github.com/Mirasyko">GitHub</a> .</p>
</div>
</section>