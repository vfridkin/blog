---
title: 02 Window seat
author: Vlad Fridkin
date: '2018-09-20'
slug: window-seat
next: 
prev: all-aboard
categories: []
tags: []
image: img/window_seat/window_seat.jpg
authorAvatar: img/vlad.png
---

It's a lot easier driving when you're looking out the windscreen to see where you're going.  Two members of the Mathemagicians had previous experience and their advice was our windscreen. 

- Data ingestion was a challenge

- The main recurring theme of the best team projects was that they found a clear and coherent problem to solve and they focused on it

- I can’t emphasise enough how important research into the industry is

- The best pitches had strong narratives

Like Sergey Brin said after John Doerr's presentation of OKR's in 1999, “Well, we need to have some organizing principle. We don’t have one, and this might as well be it.”

That's why we had the Shark Tank at the start (see All aboard post), so we could identify the problem to solve and focus our analysis of the data towards solving that problem.  Other things we did included moving the data to an SQL database from the start, setting up a _research_ channel on Slack and assigning people to specific roles, including research, problem validation, MVP design and backend set up.

It wasn't smooth sailing, we disagreed a lot.  Some times the person with the idea, which the team chose, later argued not to use the idea.  Disagreement is a great way to dig deeper to uncover assumptions and weaknesses.

![Argument](/img/window_seat/Mocking_Bird_Argument.jpg)

Before the data was released, most of us thought it would be banking data (as ANZ was a major sponsor).  Some of us actually read through their [corporate sustainability report](http://www.anz.com/about-us/corporate-sustainability/reporting-performance/sustainability-reporting/) and started coming up with names for the Data2App.  

Lesson learned!

After the MYKI data was released, we decided our problem would be determining when and where to display digital billboards.  Our research uncovered fresh news about Adshel [installing an increasing number of digital billboards at Melbourne train stations](https://www.adshel.com.au/adshel-transforms-national-coverage-with-launch-of-metro-trains-melbourne/).  

New capabilities often bring new challenges.  With paper billboards, an advertiser may pay $6,000 (depending on location) for a month and hope for the best.  With digital billboards, an advertiser has the freedom, but also the challenge, to choose where to advertise potentially at any time.  This is the market gap we decided to take on with the MYKI data.

This focussed our analysis of the data including

- determining which mode of transport had the most people per stop at any time (trains have 188 times more than bus, or 24 times more than tram)

- choosing to focus on touch on data (representing when people are waiting in the vicinity of a billboard)

- grouping and leaving out low value card types

![Stop volumes comparison](/img/window_seat/train_stop_volume188.JPG)

Knowing the problem made developing a web app easier, leaving us plenty of energy to argue about whether to include a map :sweat_smile:.

Next stop, Data2App!















