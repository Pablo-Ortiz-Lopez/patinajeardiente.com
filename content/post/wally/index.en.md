---
title: "Where is Marc?"
description: "Free Giveaway with a Cash Prize"
slug: where-is-marc
date: 2023-08-22
image: cover4.jpg
categories:
    - "Where is Marc?"
tags:
    - prize
    - where-is-marc
---

During the period leading up to the giveaway, Marc will be rollerblading dressed as Wally through the streets of Barcelona.

## How to Participate

- Find Marc rollerblading dressed as Wally and take a photo of him.
- Upload the photo to your Instastory.
- Tag `@patinajeardiente` in the photo.
- Make sure to follow `@patinajeardiente` on Instagram.

### Important!

- Keep the photo on your Instastory for 24 hours.
- If you have a private Instagram account, you must send a screenshot of the Instastory to `@patinajeardiente`. If you don't do this, you won't be able to participate in the giveaway.

## Live Streaming and Giveaway

- The giveaway will be livestreamed on Twitch on the account `patinajeardiente` and it will take place on Saturday, September 16th at 8:00 PM.
- The giveaway consists of a virtual marble racing tournament with elimination rounds, culminating in a single winner!

## Winner Selection

- Once the giveaway concludes, if the winner doesn't respond within 24 hours:
  - The prize will be passed to the second-place finisher in the race.
  - If the second-place finisher also doesn't respond within 24 hours, the prize will be passed to the third-place finisher.
  - If none of the top three respond, the prize will be rolled over to the next giveaway.

Don't miss out on this unique opportunity! Hit the streets, find Marc, and you could be the lucky winner of the cash prize. Follow `@patinajeardiente` for more details and stay tuned to our social media!

## Gráfico Interactivo

```{html}
<div id="grafico_interactivo"></div>

<script src="https://cdn.jsdelivr.net/npm/apexcharts"></script>
<script>
var options = {
  chart: {
    type: 'line',
    height: 350
  },
  series: [
    {
      name: 'Marc',
      data: [
        {x: '2024-04-01', y: 10},
        {x: '2024-04-15', y: 30}
      ]
    },
    {
      name: 'Maria',
      data: [
        {x: '2024-04-01', y: 15},
        {x: '2024-04-15', y: 45}
      ]
    }
  ],
  xaxis: {
    type: 'datetime',
    labels: {
      datetimeUTC: false,
      datetimeFormatter: {
        year: 'yyyy',
        month: 'MM',
        day: 'dd',
        hour: 'HH',
        minute: 'mm',
      }
    }
  },
  legend: {
    onItemClick: {
      toggleDataSeries: true
    },
    labels: {
      useSeriesColors: true
    }
  }
};

var chart = new ApexCharts(document.querySelector("#grafico_interactivo"), options);
chart.render();
</script>