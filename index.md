---
layout: default
title: Home
covid_holdoff: false
---
<section class="clearfix index">
    <div id="index_banner">
    </div>
   <div class="credits">
       [Notocactus Uebelmannianus in Derek Cluskey's collection] 
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
        </p></strong>
        <p class="center">
            In the mean time, drop in to our <a href="{{ site.facebook_group_url }}" target="_blank">Facebook group</a> and say hello!
        </p>
        <br />
        {% else %}
<!--        <p class="center" style="margin-top:-10px; font-size:1.7em;">
           <strong>ANNUAL PLANT SALE</strong>
        </p>
        <p class="center" style="font-size:1.2em;">
            <strong>Our next meeting/PLANT SALE is on Thursday, June 9th at 7:30pm at the Botanic Gardens.</strong>
        </p>
        <p class="center" style="margin-top:-10px; font-size:1.2em;">
            We hope to see you all there! 
        </p>
-->
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
                <li>Online meetings to discuss plants, cultivation, and meet growers</li>
                <li>In person meetings covering cacti and succulents</li>
                <li>Members plants sales or exchanges</li>
                <li>Society Library from which members may borrow books on all aspects of cacti and succulents</li>
                <li>Advice on plant cultivation</li>
                <li>Cactus & Succulent Shows held throughout the year.</li>
                <li>Plants you wish to have identified</li>
                <li>Exhibitions</li>
                <li><b><a href="https://www.irelandcactus.com/join.html">Sign up here!</a></b></li>
            </ul>
        </div>
    </div>
</section>
<!-- Container element for parallax-->
<div class="potting_para"></div>
<section class="medias clearfix">
    <div class="main_wrapper">
        <br>
        <div class="video-related">
            <h3>
                <strong>
                    Events
                </strong>
            </h3>
            <p> <b>April 28th:</b> <a href="https://www.facebook.com/events/1112751436732005/">Visit to Martin Bergman's Greenhouse</a></p>
            <p> <b>May 25th:</b> <a href="https://www.facebook.com/events/2029021420812053/">Cactus and Succulent Show at the National Botanic Gardens</a> </p>
            <p> <b>June 22nd:</b> <a href="https://www.facebook.com/events/3424715277673778/">Visit to Derek Cluskey's Greenhouse</a></p>
            <p> <b>August 17th:</b> <a href="https://www.facebook.com/events/766119132142495/">Visit to Jurate Simkute's Greenhouse</a></p>
            <p> Here is a glimpse at a previous show.</p>
        </div>
        <!-- video cactus show -->
        <div class="video">
            <iframe src="https://www.youtube.com/embed/nULIo2jaWdo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>
</section>
