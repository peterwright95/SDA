---
date: 2021-05-13T11:00:59-04:00
description: "How did the Covid Pandemic impact the use of Taxis?"
featured_image: "/images/taxi-covid.jpeg"
title: "Taxis during the Covid Pandemic"
---

COVID-19 has been the greatest sanitary crisis of our era and the biggest source of
scepticism towards public transport. While it is uncertain when the disease reached United
States population for the first time, it was clear that it was already spreading in the very first
weeks of March 2020. On March 1st, the first case of COVID-19 in New York City was
confirmed. Two weeks later, on March 12th all gatherings of more than 500 people were shut
down and from this day schools and workplaces followed. By the end of the month NYC was
under complete lockdown.

<script>
  function resizeIframe(obj) {
    obj.style.height = obj.contentWindow.document.documentElement.scrollHeight + 'px';
  }
</script>

<script>
  img {
  width: auto;
  height: 100%;
  max-height: 20vh;
}
</script>

<script type="application/javascript">

function resizeIFrameToFitContent( iFrame ) {

    iFrame.width  = iFrame.contentWindow.document.body.scrollWidth - 5px;
    iFrame.height = iFrame.contentWindow.document.body.scrollHeight - 5px;
    iFrame.display = block;
}

</script>

<div style="text-align: center;">
<iframe src = "{{< baseurl >}}/html/pickupsdrop.html" > </iframe>
</div>

During the first week of March all activities continued normally. It is after the lockdown when,
as a consequence of the lockdown we consequently see a drastic drop in taxi pickups. In the
few first months of the pandemic taxi usage was limited and the little activity registered
corresponds to these exceptions. Nevertheless, the taxi usage kept following a weekly
seasonal behaviour, reaching minimums on Sundays.

<div style="text-align: center;">
<iframe src = {{< baseurl >}}/html/dailycovid.html onload="resizeIFrameToFitContent(this)" title="Figure 2"> </iframe>
</div>

We can observe a similar behaviour if we take a look at the number of passengers per trip
evolution. The most common one has always been 1 passenger trips. After the lockdown,
the overall number of daily trips dropped and it is curious how multi-passenger trips were
specially affected. The number of daily trips with 2 or more passengers dropped to near 0 for
all the pandemic, remaining 1 passenger trips as the most common.
After summer, the number of COVIS19 cases severely decreased and as the pandemic
slowed down the number of individual taxi pickups increased. Specially the trips with 2
passengers started increasing noticeably again. It looked like the population was relaxing
their scepticism towards sharing close up spaces.

<div style="text-align: center;">
<iframe src = {{< baseurl >}}/html/passengers.html onload="resizeIFrameToFitContent(this)" title="Figure 3"> </iframe>
</div>

Another interesting consequence of the COVID-19 crisis can be observed in the taxi trip
distances. It was common among the NYC citizens to use taxis as a regular way of transport
for everyday commuting. After the COVID-19 lockdown the public became more aware of
the danger of unnecessary exposure, therefore using taxis only for the most necessary trips.
This translated into an increase of the mean trip distances per day, especially during May,
when NYC registered one of its highest peaks in COVID-19 confirmed cases. Two other
noticeable spikes can also be seen at the end of the year, around Thanksgiving (26
November) and Christmas (24 December).

<div style="text-align: center;">
<iframe src = {{< baseurl >}}/html/tripdistance.html onload="resizeIFrameToFitContent(this)" title="Figure 4"> </iframe>
</div>

The COVID-19 pandemic not only affected to the usage of public transport but also had
important effects in the overall activity around New York City.

<div style="text-align: center;">
<iframe src = {{< baseurl >}}/html/NYC_map_joined.html style="width: 1000px; height: 1000px; left.-140px;" frameborder="0" scrolling="no" onload="resizeIFrameToFitContent(this)" alt="Figure 5"> </iframe>
</div>

Taxi is a form of transport typically used by enterprise workers, with above average salaries.
As the economic crisis and increased unemployment came along the pandemic the taxi
range of usage throughout the city changed too. Manhattan remained as the most busy
region in New York city while the surrounding taxi activity declined. This effect was
particularly surprising in the airport areas. Being a common destination for taxi trips, when
the flights shut down during the pandemic it was evident the number of taxi pickups in
airports would drop to almost zero.







