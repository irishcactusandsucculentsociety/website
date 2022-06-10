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
<!--        <p class="center">
            <strong>Our next meeting is on Thursday June 9th at 7:30pm at the Botanic Gardens.</strong>
        </p>
        <p class="center" style="margin-top:-10px;">
           <strong>Annual Plant Sale</strong>
        </p>
        <p style="margin-top:-10px;">
	    While we have had to postpone the Cactus & Succulent show until next year, the good news is our Annual Plant Sale will be going ahead in June. Visitors & non-members are very welcome!
        </p>
        <p style="margin-top:-10px;">
            If you're a member, you'll even get a discount on the plants!
        </p>
        <p style="margin-top:-10px;"><em>
            As always, feel free to bring along appropriate plants each month to show off and discuss them - after all horticultural societies are about plants!
        </em></p>
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
    <div class="main_wrapper">
        <br>
        <div class="video-related">
            <h3>
                <strong>
                    Events
                </strong>
            </h3>
            <p> Our aim is to organize a show every year, our next one is on Saturday June 11th.</p>
            <p> Here is a glimpse at our 2019 show.</p>
        </div>
        <!-- video cactus show -->
        <div class="video">
            <iframe src="https://www.youtube.com/embed/nULIo2jaWdo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>
</section>
