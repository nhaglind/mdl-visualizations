---
layout: post
title: "March 2018 - Litigation with Most Actions Pending"
permalink: /:month-:day-:year/:title.html
description: "Top 10 cases with most actions pending as of March 15, 2018."
tags: [actions, bar]
---

<h4>Current</h4>
<canvas id="bar" width="400" height="200"></canvas>

<script>
var ctx = document.querySelector("#bar");
var myChart = new Chart(ctx, {
  type: 'bar',
  data: {
    labels: ["Xarelto", "Ethicon", "DePuy", "Taxotere", "J&J", "Testosterone", "Boston Scientific", "Oil Spill", "Bair Hugger", "Cook IVC"],
    datasets: [{
      label: 'Actions Now Pending',
      data: [20371, 13652, 9448, 6994, 6559, 6226, 6216, 4360, 4308, 3826],
      backgroundColor: 'rgba(255, 99, 132, 1)',
      borderColor: 'rgba(255, 99, 132, 1)'
    }, {
      label: 'Total Actions Historical',
      data: [21469, 39774, 9602, 7165, 6585, 7675, 25485, 6049, 4606, 3914],
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





Based on the data located <a href="http://www.jpml.uscourts.gov/sites/jpml/files/Pending_MDL_Dockets_By_Actions_Pending-March-15-2018.pdf">here.</a>

