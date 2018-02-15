---
layout: post
title: "January 2018 - Docket Type"
permalink: /:month-:day-:year/:title.html
description: "Bar chart displaying the MDL Statistics Report by docket type."
tags: [docket, bar]
---

<canvas id="bar" width="400" height="200"></canvas>


<script>
var ctx = document.querySelector("#bar");
var myChart = new Chart(ctx, {
  type: 'bar',
  data: {
    labels: ["Air Disaster", "Antitrust", "Common Disaster", "Contract", "Employment Practices", "Intellectual Property", "Miscellaneous", "Products Liability", "Sales Practices", "Securities"],
    datasets: [{
      label: '# of Filings',
      data: [3, 51, 2, 5, 3, 8, 39, 70, 30, 9],
      backgroundColor: [
        'rgba(255, 99, 132, 0.2)',
        'rgba(54, 162, 235, 0.2)',
        'rgba(255, 206, 86, 0.2)',
        'rgba(75, 192, 192, 0.2)',
        'rgba(153, 102, 255, 0.2)',
        'rgba(255, 159, 64, 0.2)',
        'rgba(30, 144, 64, 0.2)',
        'rgba(250, 128, 114, 0.2)',
        'rgba(238, 130, 238, 0.2)',
        'rgba(112, 128, 144, 0.2)'
      ],
      borderColor: [
        'rgba(255, 99, 132, 1)',
        'rgba(54, 162, 235, 1)',
        'rgba(255, 206, 86, 1)',
        'rgba(75, 192, 192, 1)',
        'rgba(153, 102, 255, 1)',
        'rgba(255, 159, 64, 1)',
        'rgba(30, 144, 64, 1)',
        'rgba(250, 128, 114, 1)',
        'rgba(238, 130, 238, 1)',
        'rgba(112, 128, 144, 1)'
      ],
      borderWidth: 1
    }]
  },
  options: {
    scales: {
      yAxes: [{
        ticks: {
          beginAtZero: true
        }
      }]
    }
  }
}); 
</script>

<br>
<p><strong>Products liability</strong> is sitting comfortably as the docket type with most filings and is primarily made up of pharmaceutical and medical device companies. This category is often associated with all the commercials being aired during Judge Judy and People's Court. It's interesting to look at what doesn't fall under any of the other categories and is slotted as "miscellaneous." A fair amount of these unique filings appear to be surrounding the <a href="https://en.wikipedia.org/wiki/Telephone_Consumer_Protection_Act_of_1991">Telephone Consumer Protection Act (TCPA)</a> and data breaches which we saw way too much of in 2017. The prevalent filings listed here include Yahoo, Equifax, and Ashley Madison.</p> 

<p>The second largest category <strong>Antitrust</strong> doesn't seem to stick to any one industry nor have any allegiances and can exist anywhere ranging from vitamins, shipping, computer parts, and merchant fees.</p>

<p>Keep in mind, many of these filings started over a decade ago with filing dates as early as 1991 with Asbestos or in 2001 with Enron's Securities, Derivative & "ERISA" Litigation.</p>
<p>Based on the data located <a href="http://www.jpml.uscourts.gov/sites/jpml/files/Pending_MDL_Dockets_By_Type-January-16-2018.pdf">here.</a>
</p>

