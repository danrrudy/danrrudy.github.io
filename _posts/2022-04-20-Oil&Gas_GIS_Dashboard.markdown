---
layout: post
title:  "Oil & Gas GIS Dashboard"
date:   2022-04-20 11:51:59 -0500
categories: jekyll update
---

*this post was written in January 2023 and backdated to indicate the actual date of the event*

The University of Pittsburgh hosts an innovative course taught by [Dr. Jeffrey Wheeler, Teaching Professor of Mathematics](https://sites.pitt.edu/~jwheeler/), *Mathematical Problems in Business, Industry, and Government*. I was fortunate enough to take the course in my last semester of Undergrad, and worked with a small team of students on a semester-long project. We were tasked with analyzing the viability of a Oil & Gas drilling company expanding into the solar market, but were left to explore the methods and specific goals ourselves. 

We started with the existing work of a previous year's project which analyzed extraction decline curves, to make a mathematical model for future output projections. They had a database of drilling sites with an array of data for each location: owner, license expiration, status, etc. We spent some time looking at this data and other considerations like Pittsburgh's general gloominess as factors for solar installations. An engineer on our team also found some valuable information on landslide incedence, which would have to be a major practical consideration for any large installations. 

All this together led us to an objective: Predict optimal locations for solar installations in the company's operating territory. I was also in an applied GIS course at the time, and saw an opportunity to combine the tools from that course with this project. I found Digital Elevation Models hosted by NASA covering the territory we were interested in, and ran ESRI's pre-built solar irradiane model on them. Each file took appx. two hours to run on my machine, but in the end we compiled a solar irradiance model covering Southwestern and Northeastern PA, giving a visual indication of the best areas purely based on average solar irradiance.

We combined this map with the drilling locations in PA, rendered as a heatmap, and basic depth/height isoline maps of the marcellus shale deposit. I integrated these into [a mobile app](https://pitt.maps.arcgis.com/apps/instant/lookup/index.html?appid=5f3df8583d41423997f89c86ed6f3b38), which we presented to to the client, along with the other research we had compiled. The app only had basic functionality due to our time constraints, but we are hopeful that a future group will continue the work. The client was very happy with our results, and committed support to the University's Math department as a result.

You can find our research poster below, which was presented to the Allegheny Mountain Section of the American Mathematical Association and the University of Pittsburgh Math department.

<object data="/assets/BIG_Gas_to_Solar_2022_Poster.pdf" width="100%" type='application/pdf'></object>