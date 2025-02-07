---
layout: post
title:  F\# types exercises
tagline: Some gentle exercises to start working with domains.
categories: 
- F# as your first functional programming language
tags:
- fsharp
---


### Coins

At some point, a customer will enter some amount of each coin to buy a product in the food vending machine. The machine receives coins of $\$$0.1, $\$$0.25 and $\$$0.5 value only. 
 - Model a type `Coins` that accounts for the number of each of the coins the machine receives. 
 - Create a function `amount` that receives a value of `Coins` and returns the amount in $\$$ that the customer introduced in the machine.

> 💡 The function `float` can be used to convert an integer value to a float type 

### Slots

The food vending machine vendor supplies the machine with different slots to accomodate products that have different sizes. The vendor provides three different sizes, single, double and triple. 
- Model the sizes of the slot in a type `SlotSize`.
- Extend the model `FoodMachineItem` to add the size of the product measured by the size of the slot it occupies.

### Coffee machine
Our vending machine client wants to add a coffee machine just beside the food vending machine, and wants us to prepare the software to manage it. As a first round conversation, we have been informed that the coffee machine will serve coffee and black tea. Sugar and cream can be added to both of them. It will also have chocolate and capucchino, with the only option to add sugar. Finally, it will also serve a healthy green or white tea that can be topped with milk only. Start modeling the coffee machine by introducing the types to describe all these beverages.


