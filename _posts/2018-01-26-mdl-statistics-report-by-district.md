---
layout: post
title: "January 2018 - District"
permalink: /:month-:day-:year/:title.html
description: "Doughnut chart displaying the MDL Statistics Report by district."
tags: [district, doughnut]
---

<canvas id="doughnut" width="400" height="200"></canvas>


<script>
let randomValue = () => Math.floor(Math.random() * 255);
let data = [2, 2, 8, 21, 4, 1, 2, 8, 1, 3, 1, 4, 1, 5, 1, 11, 1, 3, 1, 2, 1, 2, 5, 1, 12, 4, 2, 11, 4, 3, 2, 17, 1, 2, 5, 22, 4, 3, 1, 2, 1, 13, 1, 2, 1, 4, 2, 2, 1, 1, 6];
let colors = [];
for (let i = 0; i < data.length; i++) {
  colors.push(`rgb(${randomValue()}, ${randomValue()}, ${randomValue()})`,);
};
var ctx = document.querySelector("#doughnut");
var myBubbleChart = new Chart(ctx,{
    type: 'doughnut',
    data: {
      datasets: [{
        data: data,
        backgroundColor: colors
    }],
    labels: [
      'ALN',
      'AZ',
      'CAC',
      'CAN',
      'CAS',
      'CO',
      'CT',
      'DC',
      'DE',
      'FLM',
      'FLN',
      'FLS',
      'GAM',
      'ILC',
      'ILN',
      'INN',
      'KS',
      'KYE',
      'KYW',
      'LAE',
      'LAW',
      'MA',
      'MD',
      'MIE',
      'MN',
      'MOE',
      'MOW',
      'NH',
      'NJ',
      'NM',
      'NV',
      'NYE',
      'NYS',
      'OHN',
      'OHS',
      'OKN',
      'OKW',
      'OR',
      'PAE',
      'RI',
      'SC',
      'TNW',
      'TXN',
      'TXS',
      'VAE',
      'WVN',
      'WVS'
    ]
  }
});

</script>

<br>
<p>You can strike districts to remove them from the chart. There are <em>a lot</em> of districts so this is rather squished. Advised to breaking it out by federal circuits instead.</p>
<p>Based on the data located <a href="http://www.jpml.uscourts.gov/sites/jpml/files/Pending_MDL_Dockets_By_District-January-16-2018.pdf">here.</a>
</p>
