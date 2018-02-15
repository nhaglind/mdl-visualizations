---
layout: post
title: "January 2018 - Litigation with Most Actions Pending"
permalink: /:month-:day-:year/:title.html
description: "Top 10 cases with most actions pending as of January 16, 2018."
tags: [actions, bar]
---

<canvas id="bar" width="400" height="200"></canvas>


<script>
var ctx = document.querySelector("#bar");
var myChart = new Chart(ctx, {
  type: 'bar',
  data: {
    labels: ["Xarelto", "Ethicon", "DePuy", "Boston Scientific", "Testosterone", "Talcum Powder", "Oil Spill", "Bair Hugger ", "Taxotere", "Cook IVC"],
    datasets: [{
      label: 'Actions Now Pending',
      data: [19779, 13825, 9313, 6450, 6152, 5117, 4360, 4215, 4132, 3636],
      backgroundColor: 'rgba(255, 99, 132, 1)',
      borderColor: 'rgba(255, 99, 132, 1)'
    }, {
      label: 'Total Actions Historical',
      data: [20801, 39638, 9461, 25393, 7583, 5132, 6048, 4414, 4239, 3698],
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
        stacked: true
      }],
      yAxes: [{
        stacked: false
      }]
    }
  }
});
</script>

<br>
<p>Currently we're seeing the popular blood thinner Xarelto continue to be the center of attention in these product liability cases so it's no surprise that it's at the top of the list with <strong>19,779 actions now pending</strong>.</p>

<p>Ethicon's Pelvic Repair System (historically) is holding the most actions of these 10, but what's not included here (due to only have 295 pending actions) is the forever lasting Asbestos litigation that has had <strong>192,084 total actions</strong> which is significantly higher than anything else that is on the report.</p>
Based on the data located <a href="http://www.jpml.uscourts.gov/sites/jpml/files/Pending_MDL_Dockets_By_Actions_Pending-January-16-2018.pdf">here.</a>

