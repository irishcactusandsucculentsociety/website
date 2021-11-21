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
<section class="newproducts clearfix">
    <div class="container">
        {% if page.covid_holdoff %}
        <p class="center">
            Due to the ongoing COVID restrictions our regular monthly meeting is cancelled.
        </p>

        <p class="center">
            In the mean time, drop in to our <a href="{{ site.facebook_group_url }}">Facebook group</a> and say hello!
        </p>
        <br />
        {% else %}
        <p class="center">
            <strong>Regular meetings</strong> take place on the second Thursday of <strong>each month of 2020 at 7.30pm</strong>  in the National Botanic Gardens, Glasnevin.
        </p>
        <p class="center">
            There are no meetings in January or December.
        </p>
        <!-- Slide2 -->
        <div class="wrap-slick2">
            <div class="slick2">
            </div>
        </div>
        {% endif %}
    </div>
</section>

<!-- potting party -->
<section id="" class="potting clearfix">
    <div class="potting_small onleft">
        <div class="text">
            <h3>
                Become a MEMBER!*:)
            </h3>
        </div>
    </div>

    <div class="potting_small onright">
        <div class="text">
            <p>
                <strong>
                    Benefits of membership
                </strong>
            </p>
            <ul>
                <li><span class="">&centerdot;</span> Illustrated talks on various methods of culture</li>
                <li><span class="">&centerdot;</span> Extensive seed list  </li>
                <li><span class="">&centerdot;</span> Society Library from which members may borrow books on all aspects of cacti and succulents </li>
                <li><span class="">&centerdot;</span> Members plants sales or exchanges</li>
                <li><span class="">&centerdot;</span> Advice on plant cultivation</li>
                <li><span class="">&centerdot;</span> Four full colour magazines a year</li>
                <li><span class="">&centerdot;</span> The Biannual Cactus & Succulent Society Branch Show.</li>
                <li><span class="">&centerdot;</span> Lectures on various trips made to see these plants in their native habitat  </li>
                <li><span class="">&centerdot;</span> Plants you wish to have identified  </li>
                <li><span class="">&centerdot;</span> Exhibitions  </li>
            </ul>
        </div>
    </div>
</section>

<section class="stories clearfix">
    <div class="container">
        <h3 class="center">
            Latest News
        </h3>
        <!-- blog post -->
    </div>
</section>
