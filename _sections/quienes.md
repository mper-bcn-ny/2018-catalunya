---
title: Quienes somos
icon: fa-users
order: 5
---

This Jekyll theme lets you build as many of these sections as you want. They live in the _sections folder in your project's root directory. For some examples, see the [GitHub repository](https://github.com/chrisbobbe/jekyll-theme-prologue). Just be sure to add some [frontmatter](https://jekyllrb.com/docs/frontmatter/) to each section.

All sections have titles, which are listed in the site's navigation menu. At the top of each section, the section's title will render by default (e.g., Welcome to Jekyll!). If you want it to show something different (see Intro), add **auto-header: none** to your frontmatter, and add your text in a <h2> tag inside a <header> tag outside the frontmatter. You'll want to give each section an **order** parameter, also in the frontmatter, or it won't know where to put itself and will hide. Icons are from [Font Awesome](http://fontawesome.io/icons/).

You may notice that this section is written in Markdown -- either Markdown or html works!

<div class="row">
    <div class="4u 12u$(mobile)">
      <div class="item">
        <a href="#" class="image fit"><img src="{{ 'assets/images/pic02.jpg' | relative_url }}" alt="Ipsum Feugiat" /></a>
        <header>
          <h3>Ipsum Feugiat</h3>
        </header>
      </div>
      <div class="item">
        <a href="#" class="image fit"><img src="{{ 'assets/images/pic03.jpg' | relative_url }}" alt="Rhoncus Semper" /></a>
        <header>
          <h3>Rhoncus Semper</h3>
        </header>
      </div>
    </div>
    <div class="4u 12u$(mobile)">
      <div class="item">
        <a href="#" class="image fit"><img src="{{ 'assets/images/pic04.jpg' | relative_url }}" alt="Magna Nullam" /></a>
        <header>
          <h3>Magna Nullam</h3>
        </header>
      </div>
      <div class="item">
        <a href="#" class="image fit"><img src="{{ 'assets/images/pic05.jpg' | relative_url }}" alt="Natoque Vitae" /></a>
        <header>
          <h3>Natoque Vitae</h3>
        </header>
      </div>
    </div>
    <div class="4u 12u$(mobile)">
      <div class="item">
        <a href="#" class="image fit"><img src="{{ 'assets/images/pic06.jpg' | relative_url }}" alt="Dolor Penatibus" /></a>
        <header>
          <h3>Dolor Penatibus</h3>
        </header>
      </div>
      <div class="item">
        <a href="#" class="image fit"><img src="{{ 'assets/images/pic07.jpg' | relative_url }}" alt="Orci Convallis" /></a>
        <header>
          <h3>Orci Convallis</h3>
        </header>
      </div>
    </div>
  </div>
