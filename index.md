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

<!-- 
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
</section> -->


<section id="about" aria-labelledby="about-title">
  <h2 id="about-title">About</h2>
  <div class="item">
    <p>I always wanted to start my own blog. I wanliked the idea to share my ideas and get feedback on my thought process, but for a long time, though, I felt I have nothing worth sharing.</p>

    <p>That changed during my studies of Financial Mathematics at Charles University, where I discovered my passion for optimization. I really liked the idea of finding the best solution under given constraints. <em>TWe are doing thi all the time, so why not get better at it?</em> I thought. Over time, this interest led me towards stochastic optimization, which is as close to real life as possible. My program is  focused mainly on statistics and data  science, and I've come to see statistics and machine learning as different faces of optimization.That is when I realized what I wanna write about.</p>

    <p>This blog isn't meant to be educational material or an original take on optimization and ML. Instead it is my personal journey through these subjects I find fascinating. I'm also a terrible writer, which I want to fix through these short entries and become better at explaining math. I don't think I'll get any audience, so it’s more of a showcase for potential employers, and a way to share my thoughts with a very close circle of people who know me. I will also add my takes on some lectures I find interesting and try to enhance lecture notes with my interpretation. It will mostly be a simplified version of the lecture notes to help me understand presented ideas better.</p>

    <p>My journey starts here. I don't know where it will end, but I hope it brings me closer to understanding the problem of life's optimization. As for the format: I will try to add one entry a week, sometimes more, sometimes less. In the <strong>academic</strong> section, I will begin with analysis of spaces,move into mathematical programming and eventually explore machine learning algoritmhs through the lens of optimization, starting with linear regression and, hopefully, ending with transformers. The <strong>projects</strong> section I will collect notes on what I'm working on, doubling as an extended version of my CV. The <strong>personal</strong> section will hlod my reading log (mostly non-fiction books) with reflections on ideas that strike me as fascinating or unsettling.</p>

    <p>
      Contact: 
      <a href="mailto:personal@sykoramiroslav.cz">personal@sykoramiroslav.cz</a> · 
      <a href="https://github.com/Mirasyko">GitHub</a>
    </p>
  </div>
</section>