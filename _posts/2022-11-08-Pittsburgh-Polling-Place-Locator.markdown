---
layout: post
title:  "Pittsburgh Polling Place Locator"
date:   2022-11-08 12:00:00 -0500
categories: work
tags: work, GIS, elections
---
*this post was written in January 2023 and backdated to indicate the actual date of the event*

I serve as a Judge of Elections for Pittsburgh's 11th Ward, 11th Dirstrict, in Highland Park. The polling place for my district is located in the same room as 4 other polling places. Every single election, people come in, and not knowing which table they're supposed to be at, usually have to stop at 3 or 4 before they get to the right one. Of course, some of them aren't even in the right building, and we have to send them down the street after they've spend 20 minutes in the frustrating process of having each table check for their name. Several voters have given up at this point and resigned to not vote in that election. 

Surely it doesn't need to be this hard? So the second election I worked, I brought a map I made in ArcGIS, with labels for the ward and district numbers, and some nearby locations I thought would work as points of interest to orient it.
![Photo of the first map design](/assets/FirstWorstMap.png)
Quickly, I learned this wasn't going to work, as folks still couldn't find their houses on the map, and it just changed the issue to "okay, which side of this road do you live on?". Still not terribly helpful.
For the next election, one of the other poll workers wrote in by hand osme additional street names, which helped, but only marginally so, and the maps were starting to get beat up after a few uses.
Ahead of the November 2022 general, and with a bit more GIS experience under my belt, I decided to take another crack at it, asked for a list of polling place locations from the county, geocoded them onto a map of the voting districts, and hosted them in a searchable webapp through ArcGIS's instant apps. With a little bit of tweaking and some fine-tuning, I managed to get it all up and running, with address search enabled. It didn't meet all my dreams, but it was good enough for a pilot run.
![Polling Place Locator App](/assets/LocatorApp.png)
I went to the election with the app in hand, and after testing it with the first few voters that came in, shared it with the other 4 judges in the room. The more tech-savvy loved it, and while the others weren't as willing to use it, they still thought it was valuable (many of them just sent lost voters over to me!). Over the course of the day, I used it to locate the polling places for at least 30 voters with confidence, and the ones that did have to go to another building got a slip of paper with the address, an exepected but invaluable benefit. [Check out the Polling Place locator here!](http://arcg.is/15rbHn) *note: locations have not been updated since the November 2022 election, but will be before the May primaries*