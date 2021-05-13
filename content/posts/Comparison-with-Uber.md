---
date: 2017-04-10T11:00:59-04:00
description: "A comparison of the Uber Dataset and Taxis ranging from ... to ..."
featured_image: "/images/taxi-vs-uber.jpeg"
title: "Comparison Between Uber and Taxis"
---

<script>
  function resizeIframe(obj) {
    obj.style.height = obj.contentWindow.document.documentElement.scrollHeight + 'px';
  }
</script>


# CODE FOR IMAGES
<script>
  img {
  width: auto;
  height: 100%;
  max-height: 20vh;
}
</script>

There has been debate about the different ride-hailing method in New York, since Uber arrives to the city. One of the most critical topics was about traffic congestion in the city. That concluded in a case study carried out by NYC Taxi & Limousine Commission (TLC) which thanks FiveThirtyEigh and their request regarding the law of Freedom of Information, the corresponding Uber data used for the study became public. Therefore, giving us the opportunity of analysing NYC taxis with respect to uber and highlight the underlying differences between this two similar but different transport methods.

(First, a little explanation about the data. The taxi data was filtered for the same year, months present in the uber dataset and then down sampled to the same number of pickups. Therefore, balancing the dataset to be able to differentiate between the different behaviour of both ride-hailing methods. Uber dataset is composed of 3 features, latitude longitude and pickup time. Therefore, we focus on those columns also on taxis.) BAAAH TECHNICAL


As starting point, one of the first impressive differences is found when the data is grouped hourly. The distribution of the pickups was quite different as one can visualize in the figure 1. 

<img src="{{< baseurl >}}/images/hourly_distributions.png" alt="Figure 1 - Hourly Pick-Up Distribution">

To comment what happened in the figure is needed to remind to the reader how Uber works. Basically, the driver chooses when to work. Therefore, is not strange to visualize a decrease in pickups between 22:00 and 4:00, probably most of the drivers are resting. Something similar can be observed between 8:00 and 14:00. Even though in this window, taxis increase the pickups, that is probably due to the decrease of uber drivers working. These hours are not considered peak hour so that uber drivers do not see them as interesting. However, after 14:00, uber pickups start to increase till reaching its maximum at 17:00h. That phenomenon is caused, mostly, by the taxis shift change which happens at 16:00h.


When the data is grouped by day of the week it is find something as in the figure 2.

<img src="{{< baseurl >}}/images/day_distribution.png" alt="Figure 2 - Pick-Up Distribution by day of the Week">

From these distributions, it can be observed that the busiest day is Thursday for taxis and Ubers. However, seems that Uber drivers get a little bit lazier on Sunday and Monday while those though taxi drivers do not seem to rest too much, being their pickups distribution almost the same from day to day.

After reading the previous analysis, the following cannot be other than group the pickups by month obtaining the following figure. 


<img src="{{< baseurl >}}/images/monthly_distribution.png" alt="Figure 3 - Monthly Pick-Up Distribution">



If it would have been possible to also obtain data along a few years, the phenomena presented here would be more noticeable. Since, the increase of Uber and decrease of the taxis during these months is not caused because uber cars could have better air conditioner which supports the summer increase theory. What happens here is the constant decrease of the traditional taxi demand and increase in demand of other ride-hailing companies.

To change a bit from those series of time distributions in bar figures, the distributions in the next figure are described with lines which can be visualize even showing several of them. Additionally, the figures are interactive. Being possible to select the distributions that one would like to visualize.

<iframe src = {{< baseurl >}}/html/Lineplot_taxi.html style="width: 616px; height: 900px;" frameborder="0" scrolling="no" onload="resizeIframe(this)" alt="Figure 4 - Hourly Distributions by Day Taxis"> </iframe>

<iframe src = {{< baseurl >}}/html/Lineplot_uber.html style="width: 616px; height: 900px;" frameborder="0" scrolling="no" onload="resizeIframe(this)"alt="Figure 5 - Hourly Distributions by Day Uber"> </iframe>


(The purpose of this figures is to pinpoint the changes between the hourly distribution on different days. The big difference can be seen between weekdays and weekend days. On weekends the peek between 8:00 and 9:00 disappear and the peek at 19:00 decrease a bit. However, the demand of transport increase on the nights from Friday to Saturday and Saturday to Sunday increase since the people go and return from the party areas.) maybe to the general taxi part.


 The distributions follow the rules highlighted in the previous analysis. Both have an increase in demand on Friday and Saturday nights and decrease around 8:00. However, Sundays change a bit on the uber distribution. It can be seen an increase in the hours which was said before that were not interesting for drivers. Between 10:00 and 16:00.

After a lot of time series analysis, it is TIME to pass to geographical data. And the first thing that was done is plotting the coordinates of every pickup of Uber and Taxis defining the density of point with intensity of colour. The result was the following.






