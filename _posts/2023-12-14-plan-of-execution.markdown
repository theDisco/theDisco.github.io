---
layout: post
title: "Metropolis - plan of execution"
date: 2023-12-14 08:20:00 +0100
categories: metropolis
---

I am working on a side project called [kinderkiez][kinderkiez] which leverages the capabilities of OpenStreetMaps, and allows users to select any place in the world and print it on a play mat. By using a custom style developed by a book illustrator, it primarily aims at parents with young children to educate them about their environment in a playful way.

Some time ago we decided that we wanted to add a new product to our shop. We call it Metropolis. The difference between Metropolis and Kinderkiez is first and foremost in the area it covers and customization options that we offer to the user. Kinderkiez is more about the cutout of the user's neighborhood. That means we try to be very accurate in the details we display on the map, and we include many details like shops, street names, parks, etc.

Metropolis covers larger areas and currently we only cover cities. It highlights the points of interest that are specific to the city and only includes those, which are easily recognisable. Metropolis was designed once and is offered "as is" to the customers. We want to change that. We believe in customisable, unique and beautiful products and we want to offer an editor to Metropolis buyers as well. Because of the fundamental differences between kinderkiez and Metropolis, we cannot leverage OpenStreetMaps anymore and we need to build our own editor.

## What's next

The scope of the project is pretty clear, but at the moment vaguely defined. I need to build an editor that will allow users to change the default design of Metropolis. That means I need to implement a similar editor to the one we offer to our users for designing a Kinderkiez. Users should be able to switch between different cities, different playmat sizes, move the icons around, and add new ones. Users need to be able to save the design to work on it at a later point as well as be able to order it through our shop.

In the next step I will concentrate on specifying the criteria necessary for choosing the correct stack for this project. I will also come up with some more accurate user stories and how they fit into this stack.

[kinderkiez]: https://kinderkiez.net
