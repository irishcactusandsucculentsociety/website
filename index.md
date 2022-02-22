---
layout: default
title: Home
covid_holdoff: true
---
<section class="clearfix index">
    <div id="index_banner">
    </div>
    <h2 class="index_header">
        Welcome to the Irish Cactus and Succulent Society Website
    </h2>
</section>

<!-- Calendar -->
<section class="timetable clearfix">
    <div class="container">
        {% if page.covid_holdoff %}
        <strong><p class="center">
            Due to the ongoing COVID restrictions our regular monthly meeting is cancelled.
        </p>
        <p class="center">
            In the mean time, drop in to our <a href="{{ site.facebook_group_url }}" target="_blank">Facebook group</a> and say hello!
        </p></strong>
        <br />
        {% else %}
        <p class="center">
            <strong>Regular meetings</strong> take place on the second Thursday of <strong>each month of 2020 at 7.30pm</strong>  in the National Botanic Gardens, Glasnevin.
        </p>
        <p class="center">
            There are no meetings in January or December.
        </p>
        {% endif %}
    </div>
</section>

<!-- become a member -->
<section id="" class="potting clearfix">
    <div class="potting_small onleft">
        <div class="text" style="display:none">
            <h3>
                Become a member!*:)
            </h3>
        </div>
    </div>
    <div class="potting_small onright">
        <div class="text">
            <h3>
                <strong>
                    Benefits of membership
                </strong>
            </h3>
            <ul>
                <li>Illustrated talks on various methods of culture</li>
                <li>Extensive seed list  </li>
                <li>Society Library from which members may borrow books on all aspects of cacti and succulents </li>
                <li>Members plants sales or exchanges</li>
                <li>Advice on plant cultivation</li>
                <li>Four full colour magazines a year</li>
                <li>The Biannual Cactus & Succulent Society Branch Show.</li>
                <li>Lectures on various trips made to see these plants in their native habitat  </li>
                <li>Plants you wish to have identified  </li>
                <li>Exhibitions  </li>
            </ul>
        </div>
    </div>
</section>
<!-- Container element for parallax-->
<div class="potting_para"></div>
<section class="medias clearfix">
    <div class="container">
        <br>
        <!-- video cactus show -->
        <div class="video">
            <iframe src="https://www.youtube.com/embed/nULIo2jaWdo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        <div class="video-related">
            <h3>
                <strong>
                    Events
                </strong>
            </h3>
            <p> Our aim is to organize a show every year.</p>
            <p> Here is a glimpse at our last show.</p>
        </div>
    </div>
</section>
