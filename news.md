---
layout: default
title: News
---

<script>
function expand() {
  var x = document.getElementById("expand");
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
    x.style.display = "none";
  }
}
</script>
<div class="pagebackground clearfix">
    <div class="container">
        <!-- Title Page -->
        <section class="background_pages banner_about">
            <div class="about_header">
                <h2>
                    News
                </h2>
                <p class="moto">Our Stories</p>
            </div>
        </section>
        <!-- content page -->
        <section class="section_about clearfix">
            <div class="section_stories_category">
                <!-- Categories -->
                <div id="myBtnContainer" class=" clearfix">
                    <button class="btn active" onclick="filterSelection('all')">All</button>
                    <button class="btn" onclick="filterSelection('cactus')">Cactus</button>
                    <button class="btn" onclick="filterSelection('succulent')"> Succulents</button>
                    <button class="btn" onclick="filterSelection('euphorbia')"> Euphorbia</button>
                    <button class="btn" onclick="filterSelection('pots')"> Pots</button>
                </div>
            </div>
            <div class="full_stories clearfix">
                <div class="story">
                    <div class="story_details filterDiv cactus">
                        <ul>
                          {% for post in site.posts %}
                            <li>
                                {{ post.excerpt}}<a href="{{ post.url }}">Learn more about {{ post.title }}>></a>
                            </li>
                          {% endfor %}
                        </ul>
                    </div>
                </div>
            </div>
        </section>
    </div>
</div>
<script src="../../javascripts/filter.js"></script>
