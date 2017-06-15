---
layout:     post
title:      "June 2017 Newsletter!"
subtitle:   "In the days before camp we need your help ensuring everything is ready! Read the latest news!"
date:       2017-06-11 12:00:00
author:     "Cookie Monster & Jellybean"
header-img: "img/newsletter/spring2017/cover.jpg"
---
<style>
    .space {
        margin-bottom: 15px;
    }
    .text-align {
        text-align: center;
    }
    .margins {
        margin-bottom: 25px;
    }
    .birthday-box {
        border-style: solid;
        border-width: 52px 54px 49px 51px;
        -moz-border-image: url(/img/newsletter/june2017/birthday-border-icons.png) 89 91 91 104 repeat;
        -webkit-border-image: url(/img/newsletter/june2017/birthday-border-icons.png) 89 91 91 104 repeat;
        -o-border-image: url(/img/newsletter/june2017/birthday-border-icons.png) 89 91 91 104 repeat;
        border-image: url(/img/newsletter/june2017/birthday-border-icons.png) 89 91 91 104 repeat;
        padding: 25px;
    }
    .space-box {

    }
</style>
<h1 style="text-align: center;">Hoping you're keeping cool and staying hydrated in the final two months before camp!</h1>
<p style="text-align: center;">Summer's here and now it's time for campers to start packing their bags! We can't wait to meet everyone at Camp Eaton. But, before that we have a few more things to get done.</p>

<div class="birthday-box space">
    <h2 class="section-heading">Happy Birthday to Campers!</h2>
    <p>We'd like to say Happy Birthday to all the campers who've had birthdays since last camp!</p>
    <ul>
        {% for camper in site.data.birthdays2017 %}
        <li>{{camper.nickname}} - {{camper.birthday | date: "%B, %d" }}</li>
        {% endfor %}
    </ul>
</div>


<!-- TODO: COUNTDOWN TIMER -->
<div class="green-box space">
    <h2 class="section-heading">Upcoming Events!!</h2>
    <div class="row">
        <div class="col-md-10 col-md-offset-1">
            <h4>Camp! - Sunday July 31st - August 5th</h4>
            <p>That's right it's finally time for camp! Don't be late because we have some great activities planned!</p>
            <!-- Picture of Camp Eaton -->
            <p>If you have questions about camp please contact <a href="mailto:claremont.outreach@campkesem.org">claremont.outreach@campkesem.org</a>.</p>
        </div>
    </div>
</div>

<div class="blue-box">
    <h2 class="section-heading">Camp Kesem Claremont T-Shirt Designs Are Here!</h2>
    <img src="/img/newsletter/june2017/camp-design.jpg"/>
    <img src="/img/newsletter/june2017/shirt-example-design.jpg"/>
</div>

<div class="margin-b-20">
    <h2 class="section-heading">Coordinator Retreat!</h2>
    <img src="/img/newsletter/june2017/counselor_retreat_2017.jpg">
    <span class="caption text-muted">Back: Glub, Cookie Monster, Carrots, Poofy, Scuba <br> Front: Jellybean, Pogo, Stitch, Carebear, Papaya <br> Not Pictured: Rainy</span>
</div>

<!-- TODO: Include Kid Friendly Section Here -->

<div class="row margins">
    <div class="col-md-8 col-md-offset-2 left-margin blue-box">
        <h2 class="section-heading">We've fundraised <span style="font-weight: 800; color: #a4d55d; font-size: 45px; text-decoration: underline;">$14,200</span> so far!</h2>
        <p>Everyone on the Coordination Board and Counselors have been raising money and holding on-campus fundraisers to make camp happen. We're super excited to announce we've raised over $11,000! But we're still short of $30,000. Help us fundraise by setting up a classy page and sending it to friends and family!</p>
        <img src="/img/newsletter/spring2017/thermometer3.gif">
        <div class="text-align"><h4 class="section-heading-h4">Create Your Own Donation Page!</h4></div>
        <p>You can also help by <strong>creating your own donation page</strong>!
        Simply click on <a href="https://donate.kesem.org/events/friends-camp-kesem-at-claremont-colleges-fy-2017/e93166">this fundraising link</a> and click <strong>"Become a Fundraiser"</strong>. You will then be given instructions for completing your donation page profile which can be shared with friends and family! Contact <a href="mailto:claremont.development@campkesem.org">claremont.development@campkesem.org</a> if you would like assistance!
        </p>
    </div>
</div>

<div>
    <h2>Help Us Prepare for Camp! Wishlist!</h2>
</div>

<div class="col-md-12 green-box margins">
    <h2 class="section-heading">New Advisory Board Members!</h2>
    <div class="row">
        <div class="col-md-8 col-md-offset-2">
                <img src="/img/newsletter/november2016/comet-advisory-board.jpg">
        </div>
    </div>
    <p> Each year Camp Kesem at the Claremont Colleges relies on our Advisory Board to help us recruit campers and volunteers, raise funds, serve as Kesem ambassadors in the local community. Our Advisory Board members work in fields including philanthropy, medicine, education, youth development, and business. If you are interested in learning more about Advisory Board opportunities, please contact our Directors at <a href="claremont@campkesem.org">claremont@campkesem.org</a>.</p>
</div>

<h2 class="section-heading">Sponsor Thank You's!</h2>
<!-- TODO: JPL / Specialized -->
<p>Camp Kesem at the Claremont Colleges is currently looking for sponsors to donate or help fundraise! If you have any kind of partnership in mind, please send us a message at <a href="mailto:claremont@campkesem.org">claremont@campkesem.org</a>. We look forward to hearing from you!</p>
<div class="green-box">
    <h2 class="section-heading">Tentative Camp Schedule!</h2>
    <img src="/img/newsletter/november2016/campeaton.jpg">
    <p>Our operations coordinator, Pogo has been at work planning camp! In fact, she has a tentative schedule for the upcoming week. Each day will have a special theme. Here's a couple exciting activities and themes she has planned!</p>
    <div class="row">
        <div class="col-md-6">
            <h4>Themes</h4>
            <ul>
                <li>Gadgets</li>
                <li>Disguises</li>
                <li>Spy Prison Break</li>
                <li>Mission Impossible</li>
            </ul>
            <h4>Activities</h4>
            <ul>
                <li>Movie Night</li>
                <li>Outdoor Activities</li>
                <li>Water Wars</li>
                <li>Messy Wars</li>
            </ul>
            <p>These are just a few of the many activities we have planned! Stay up to date with our <a href="https://www.facebook.com/campkesemclaremont">Facebook</a> and <a href="https://www.instagram.com/campkesemclaremont/">Instagram</a> page to get the latest information on camp!</p>
        </div>
        <div class="col-md-6">
            <img src="/img/newsletter/spring2017/pogo.jpg">
            <span class="caption text-muted">Operations Coordinator: Pogo!</span>
        </div>
    </div>
</div>