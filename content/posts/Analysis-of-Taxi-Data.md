---
date: 2021-05-13T15:00:59-04:00
description: "An in depth study of the Taxi Trip Dataset"
featured_image: "/images/taxi-times-square.jpeg"
title: "Study of the Taxi Trip Dataset"
---

Through-out this article we will be analysing trends in taxi usage in New York City. 
We will see how usage changes during the day-month-year, so get pen and paper ready as, believe me, you don't want to get stuck in NYC traffic!

<div style="text-align: center;">
<img src="{{< baseurl >}}/images/hourly distr.png" style="width:auto;height=100%" title="Figure 1 - Hourly Distribution of Pick-Ups">
</div>

The working day in New York starts at 8:24 on average, we can infer from the taxi hourly distribution that the city wakes up at around 7:00 and keeps busy through-out the day until around 21:00-22:00 when taxi demand starts to decrease. 
Between 13:00 and 16:00 there is a little peak, as some workers finish working around these hours or start it if they have evening shifts, and others have their lunch break. 
However, the decrease of demand after 16:00 is caused by the taxis shift change hour, nothing related to the behaviour of the city. After the decrease due to the shift change we can see the biggest peak as most people go home regardless of the reason they were out as it’s bed-time!

<div style="text-align: center;">
<img src="{{< baseurl >}}/images/week distr.png" style="width:auto;height=100%" title="Figure 2 - Weekly Distribution of Pick-Ups">
</div>

Analyzing the distribution of trips throughout the week we see that Mondays and Sundays definitely have less trips. This is due to the fact that on Sundays people stay at home with their families mostly, whilst on Mondays taxis are used almost exclusively for work related transport as it’s the beginning of the week and there is less social activity. 
We can also see how on Fridays and Saturdays transport is used to go out with friends and enjoy the weekend. It’s very surprising how the amount of use is highest on Saturday even though most people don’t need to use transport methods to reach their work-place. 

<div style="text-align: center; ">
<img src="{{< baseurl >}}/images/month distr.png" style="width:auto;height=100%" title="Figure 3 - Monthly Distribution of Pick-Ups">
</div>

The yearly distribution is also interesting as we can see that in the colder months there are less trips, probably due to people not wanting to leave the comfort of their home to go out and party. We can see that when it starts to get warmer the trend increases to finally decrease again, where we have our minimum in August. In August most people are probably on vacation, taxis aren’t used for work-transport and there are less people overall who utilize them to move around. 

<div style="text-align: center">
<iframe src = {{< baseurl >}}/html/Lineplot_taxi.html style="width: 900px; height: 600px; left.-140px" frameborder="0" scrolling="no" onload="resizeIframe(this)"  title="Figure 4 - Hourly Distributions by Day Taxis"> </iframe>
</div>

Although this is an interactive plot we will give some interesting points to further analyze. In proposing it we are aiming at pinpointing the changes between the hourly distribution on different days. 
This is most notable between weekdays and weekends. The peak from 8:00 to 9:00 on weekends disappears and also the peak at 19:00 decreases. At the same time the demand for transport increases on the Friday and Saturday nights as people need to reach and come back from the party areas in the city.

<div style="text-align: center">
<div class="row">
  <div class="column">
    <img src="{{< baseurl >}}/images/hourly distr.png" style="width:auto;height=40%" title="Figure 2 - Weekly Distribution of Pick-Ups">
  </div>
  <div class="column">
    <img src="{{< baseurl >}}/images/average_speed.jpeg" style="width:auto;height=40%" title="Figure 5 - Average Speed of trips">
  </div>
</div>
</div>

Looking at these two images side by side we can see how taxi demand and average speed are inversely proportional. This is clearly due to the fact that in certain moments of the day there is more traffic and congestion, hence the trips take longer. 


























<script>
  function resizeIframe(obj) {
    obj.style.height = obj.contentWindow.document.documentElement.scrollHeight + 'px';
  }
</script>


