---
layout: post
title: "October 2018 - Litigation with Most Actions Pending"
permalink: /:month-:day-:year/:title.html
description: "Top 10 cases with most actions pending as of October 15, 2018."
tags: [actions, bar]
---

<h4>Current</h4>
<canvas id="bar" width="400" height="200"></canvas>

<script>
var ctx = document.querySelector("#bar");
var myChart = new Chart(ctx, {
  type: 'bar',
  data: {

    labels: ["Xarelto", "Ethicon", "Boston Scientific", "DePuy", "Taxotere", "J&J", "Bard Pelvic", "Testosterone", "Bair Hugger",  "Cook IVC"],
    datasets: [{
      label: 'Actions Now Pending',
      data: [23057, 20060, 14908, 9730, 9693, 9473, 6057, 5783, 4934, 4710],
      backgroundColor: 'rgba(255, 99, 132, 1)',
      borderColor: 'rgba(255, 99, 132, 1)'
    }, {
      label: 'Total Actions Historical',
      data: [24770, 40533, 25898, 9936, 10125, 9519, 15713, 7787, 5405, 4979],
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

Ethicon, Inc., Pelvic Repair System Products Liability Litigation has crossed the arbitrary benchmark of 40K total actions. Judge is Joseph R. Goodwin (U.S. District Judge) and this is taking place in out of the WVS district.

It's not in the top 10 based on actions, but because it's been rampant in the news and has been one of the most exciting cases to follow I must mention the Roundup Products Liability Litigation numbers are as follows: Actions Now Pending: <strong>584</strong> Total Actions (Historical): <strong>589</strong>.

Initially, Monsanto (Bayer) was ordered to pay $289M, but that has been reduced to $78M. This was a reduction in punitive damages. 

Based on the data located <a href="http://www.jpml.uscourts.gov/sites/jpml/files/Pending_MDL_Dockets_By_Actions_Pending-October-15-2018.pdf">here.</a>

