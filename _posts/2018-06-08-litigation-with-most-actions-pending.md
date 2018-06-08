---
layout: post
title: "May 2018 - Litigation with Most Actions Pending"
permalink: /:month-:day-:year/:title.html
description: "Top 10 cases with most actions pending as of May 15, 2018."
tags: [actions, bar]
---

<h4>Current</h4>
<canvas id="bar" width="400" height="200"></canvas>

<script>
var ctx = document.querySelector("#bar");
var myChart = new Chart(ctx, {
  type: 'bar',
  data: {
    labels: ["Xarelto", "Ethicon", "DePuy", "Taxotere", "J&J", "Testosterone", "Bair Hugger", "Oil Spill", "PPI", "Cook IVC"],
    datasets: [{
      label: 'Actions Now Pending',
      data: [21922, 13002, 9498, 8557, 6993, 6061, 4467, 4357, 4248, 4189],
      backgroundColor: 'rgba(255, 99, 132, 1)',
      borderColor: 'rgba(255, 99, 132, 1)'
    }, {
      label: 'Total Actions Historical',
      data: [23107, 39980, 9661, 8766, 7027, 7733, 4820, 6049, 4249, 4286],
      backgroundColor: 'rgba(54, 162, 235, .2)',
      borderColor: 'rgba(54, 162, 235, 1)'
    }]
  },
  options: {
    scaleShowValues: true,

    ticks: {
      autoSkip: false
    },
    scales: {
      xAxes: [{
        stacked: true,
        ticks: {
          autoSkip: false
        }
      }],
      yAxes: [{
        stacked: false
      }]
    }
  }
});
</script>

Notable change:

Boston Scientific's Pelvic Repair System case has slid out of the top 10 but still a prevalent case to watch. What climbed quickly within the recent months were Proton-Pump Inhibitor (PPI) drugs. This includes the widely popular Prilosec (omeprazole) and Nexium (esomeprazole) which allegedly is causing kidney problems.

Based on the data located <a href="http://www.jpml.uscourts.gov/sites/jpml/files/Pending_MDL_Dockets_By_Actions_Pending-May-15-2018.pdf">here.</a>

