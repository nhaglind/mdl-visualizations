---
layout: post
title: "January 2019 - Litigation with Most Actions Pending"
permalink: /:month-:day-:year/:title.html
description: "Top 10 cases with most actions pending as of December 17, 2018."
tags: [actions, bar]
---

<h4>Current</h4>
<canvas id="bar" width="400" height="200"></canvas>

<script>
var ctx = document.querySelector("#bar");
var myChart = new Chart(ctx, {
  type: 'bar',
  data: {

    labels: ["Xarelto", "Ethicon", "Boston Scientific", "J&J",  "Taxotere", "DePuy", "Testosterone", "Bard Pelvic",  "Cook IVC", "Bair Hugger"],
    datasets: [{
      label: 'Actions Now Pending',
      data: [23213, 17034, 12255, 10137, 10000, 9797, 5767, 5463, 5017, 4978],
      backgroundColor: 'rgba(255, 99, 132, 1)',
      borderColor: 'rgba(255, 99, 132, 1)'
    }, {
      label: 'Total Actions Historical',
      data: [25219, 40618, 26026, 10267, 10949, 10024, 7846, 5632, 5294, 5507],
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

It's been a few months and as we've crossed over into the new year it's appropriate to close out 2018. <em>JPML's latest report at the time of of this posting is from Dec. 17 2018</em>. A significant movement in position is the J&J Talcum Powder litigation, especially after a $4.69B verdict was upheld alleging the products contained asbestos.

Based on the data located <a href="https://www.jpml.uscourts.gov/sites/jpml/files/Pending_MDL_Dockets_By_Actions_Pending-December-17-2018.pdf">here.</a>

