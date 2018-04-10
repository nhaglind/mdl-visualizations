---
layout: post
title: "February 2018 - Litigation with Most Actions Pending"
permalink: /:month-:day-:year/:title.html
description: "Top 10 cases with most actions pending as of February 15, 2018."
tags: [actions, bar]
---

<h4>Current</h4>
<canvas id="bar" width="400" height="200"></canvas>

<h4>Prior Month</h4>
<canvas id="bar-2" width="400" height="200"></canvas>

<script>
var ctx = document.querySelector("#bar");
var myChart = new Chart(ctx, {
  type: 'bar',
  data: {
    labels: ["Xarelto", "Ethicon", "DePuy", "Boston Scientific", "Testosterone", "Talcum Powder", "Taxotere", "Oil Spill", "Bair Hugger", "Cook IVC"],
    datasets: [{
      label: 'Actions Now Pending',
      data: [20379, 13673, 9414, 6444, 6194, 5679, 4361, 4272, 3758, 3522],
      backgroundColor: 'rgba(255, 99, 132, 1)',
      borderColor: 'rgba(255, 99, 132, 1)'
    }, {
      label: 'Total Actions Historical',
      data: [21469, 39730, 9565, 25432, 7643, 5986, 6049, 4510, 3834, 3621],
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


<script>
var ctx = document.querySelector("#bar-2");
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

<br>
<p>Not a ton of movement, but Taxotere has jumped up and had a fair amount of additional actions this month pushing it above Oil Spill by the Oil Rig "Deepwater Horizon" in the Gulf of Mexico.</p>

<p>What I failed to mention previously, inferior vena cava filters (IVC) is a bit stronger than this displays because not only does Cook Medical make these devices, so does Bard which would have come in the 11<sup>th </sup> position with 3,522 actions pending. A total of <Strong>7,280 actions across the filters</strong> giving it the fourth position ahead of Boston Sci.</p>

<p>These are early year movements, but a number of bellwether cases are to take place in the coming months that should have significant impacts on future numbers.</p>

Based on the data located <a href="http://www.jpml.uscourts.gov/sites/jpml/files/Pending_MDL_Dockets_By_Actions_Pending-February-15-2018.pdf">here.</a>

