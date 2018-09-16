---
title: Testing the post theme
layout: post
bg_color_1: rgb(74, 144, 226)
bg_color_2: rgb(144, 19, 254)
gradient_angle: 45
content_bg_color: rgb(255, 255, 255)
heading_color: rgb(0, 0, 0)
heading_link_color: rgb(74, 144, 226)
body_text_color: rgb(54, 54, 54)
body_text_link_color: rgb(74, 144, 226)
nav_text_color: rgb(0, 0, 0)
footer_post_link_color: rgb(0, 0, 0)
date: 2018-09-16 00:00:00 +0000
sub_heading: ''
tags: []
banner_image: ''
related_posts: []
post_content:
- template: markdown
  markdown: "<p>Aquaero is an interactive art experience that allows users to create
    creatures using their hands and other objects. Once these generated creatures
    have been made, they can be moved around by swiping across the table.<br><br>The
    creatures interact with the environment through audio events triggered by the
    audience, such as bubbles or lightning strikes. Flocking creatures such as jellyfish,
    fish and birds can be found in levels and add to the interaction. Audio and Environments
    transition seamlessly as the characters move around.</p>"
- template: image
  caption_alignment: right
  bg_color_1: rgb(255, 255, 255)
  bg_color_2: rgb(255, 255, 255)
  bg_angle: '0'
  bg_opacity: '1'
  image: "/uploads/2017/11/14/andrew-robles-300868.jpg"
  caption: Lorem ipsum dolor sit amet, consectetur adip*isicing elit, sed do eiusmod
    *tempor incididunt ut labore et dolore magna aliqua.
- template: markdown
  markdown: |-
    <pre><code>&lt;nav class="navigation"&gt;
      &lt;div class="nav-wrapper"&gt;
        &lt;div class="nav-list"&gt;
        &lt;div class="nav-logo-container"&gt;
            &lt;div class="nav-logo"&gt;
              &lt;a href="&lt;?php echo esc_url( home_url( '/' ) ); ?&gt;"&gt;
                &lt;div class="logo-container"&gt;
                  &lt;?php include "nav-logo.php" ?&gt;
                &lt;/div&gt;
              &lt;/a&gt;
            &lt;/div&gt;
          &lt;/div&gt;
          &lt;div class="nav-links-container"&gt;
          {%- for link in site.menus.navigation -%}
            &lt;div class="nav-item"&gt;
              &lt;a href="{{ link.url }}"&gt;{{ link.title }}&lt;/a&gt;
            &lt;/div&gt;
          {%- endfor -%}
          &lt;/div&gt;
        &lt;/div&gt;
      &lt;/div&gt;
    &lt;/nav&gt;</code></pre>
- template: code
  code: "<p>&lt;footer class=\"site-footer\"&gt;</p><p>\t&lt;div class=\"container
    pure-g\"&gt;</p><p>        &lt;div class=\"footer-col pure-u-1 pure-u-md-1-4\"&gt;</p><p>
    \           &lt;img src=\"{{ \"/img/logo-white.png\" | absolute_url }}\" alt=\"\"
    class=\"footer-logo\"&gt;</p><p>        &lt;/div&gt;</p><p>        &lt;div class=\"footer-col
    pure-u-1 pure-u-md-1-4\"&gt;</p><p>            &lt;h3&gt;About {{ site.short_title
    }}&lt;/h3&gt;</p><p>            &lt;ul&gt;</p><p>            {% for item in site.menus.footer
    %}</p><p>                &lt;li&gt;&lt;a href=\"{{ item.url | absolute_url }}\"&gt;{{
    item.title }}&lt;/a&gt;&lt;/li&gt;</p><p>            {% endfor %}</p><p>            &lt;/ul&gt;</p><p>
    \       &lt;/div&gt;</p><p>        &lt;div class=\"footer-col pure-u-1 pure-u-md-1-4\"&gt;</p><p>
    \           &lt;h3&gt;Projects&lt;/h3&gt;</p><p>            &lt;ul&gt;</p><p>
    \           {% for project in site.projects limit:5 %}</p><p>                &lt;li&gt;&lt;a
    href=\"{{ project.url | absolute_url }}\"&gt;{{ project.title }}&lt;/a&gt;&lt;/li&gt;</p><p>
    \           {% endfor %}</p><p>            {% if site.projects | size &gt; 5 %}</p><p>
    \               &lt;li&gt;&lt;a href=\"{{ \"/projects/\" | absolute_url }}\"&gt;See
    all projects&lt;/a&gt;&lt;/li&gt;</p><p>            {% endif %}</p><p>            &lt;/ul&gt;</p><p>
    \       &lt;/div&gt;</p><p>        &lt;div class=\"footer-col pure-u-1 pure-u-md-1-4\"&gt;</p><p>
    \           &lt;h3&gt;Contact&lt;/h3&gt;</p><p>        &lt;/div&gt;</p><p>\t&lt;/div&gt;</p><p>\t&lt;div
    class=\"copyright\"&gt;</p><p>        &lt;p&gt;</p><p>            &amp;copy;{{
    'now' | date: \"%Y\" }} {{ site.title }} - All Rights Reserved&lt;br&gt;</p><p>\t\t\t&lt;a
    href=\"{{ \"/admin\" | absolute_url }}\"&gt;Site Admin&lt;/a&gt;</p><p>\t\t&lt;/p&gt;</p><p>\t&lt;/div&gt;</p><p>&lt;/footer&gt;</p>"
border_color: ''
post_header_image: ''
post_subtitle: ''
post_description: ''
show_header_image_on_post: false

---
