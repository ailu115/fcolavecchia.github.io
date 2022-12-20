---
layout: post
title: F# Fundamentals
categories: 
- Programming
tags:
- fsharp
---

In math, functions are ubiquitous. Let us assume that $x$ is an real number, and define the function 

$$
f(x) = x + 1
$$

that is, the function that returns the value $$x$$ plus one. The input set (which is called the _domain_ of the function in math) is the set of all real values, $\mathbb{R}$, while the output set (the _codomain_ in math) is also $\mathbb{R}$. Using the _arrow_ notation, the complete definition of the function would be

$$
f: \mathbb{R} \rightarrow \mathbb{R} \; ; \;  x \mapsto x + 1 
$$

Or in english, $f$ is a function from $\mathbb{R}$ to $\mathbb{R}$ such that $f$ of $x$ is $x + 1$.
 
```fsharp
let a = 1.0 + 3.0 // floats 
let s = "this is a string" 
let l = [1 ; 2 ; 3] // A list of integers 
let m = ("Messi",10) // A tuple of a string and a number 
let t = true // A bool 
``` 
 
A table

| Lic. Plate | Color         | 
| :----------: |:-------------:|
| ABC 124 | black |
| DEF 350 | red   |
| QRZ 441 | black |
| JPG 255 | white | 