---
layout: default
title: News
---

<div class="pagebackground clearfix">
        <!-- Title Page -->
    <div class="main_wrapper secondary">
        <section class="background_pages">
            <div class="about_header">
                <h2>
                    News
                </h2>
                <p class="moto">Our Stories</p>
            </div>
        </section>
        <!-- content page -->
        <section>
            <div class="section_stories_category clearfix">
                <!-- Categories -->
                <div id="myBtnContainer" class=" clearfix">
                    <button class="btn active" onclick="filterSelection('all')">All</button>
                    <button class="btn" onclick="filterSelection('cactus')">Cactus</button>
                    <button class="btn" onclick="filterSelection('succulent')"> Succulents</button>
                    <button class="btn" onclick="filterSelection('soil')"> Soil</button>
                    <button class="btn" onclick="filterSelection('pots')"> Pots</button>
                </div>
            </div>
            <ul class="blog-reel">
               {% for post in site.posts %}
                   <li class="{{ post.tag}}">
                   {{ post.excerpt}}
                    <a href="{{ post.url }}" class="learn-more">Learn more about {{ post.title }}&nbsp;<i class="fa fa-angle-double-right" ></i></a>
                   <br><br><br>
                    </li>
               {% endfor %}
            </ul>
        </section>
    </div>
</div>
<script src="../../javascripts/filter.js"></script>
