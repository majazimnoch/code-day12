# Subtle effect on scroll with JS
## Intro
This is the twelfth project of my 30-day coding challenge. The project includes following tech stuff: HTML, CSS, JavaScript.

## Idea
The idea was to make a page with three section. When a user scrolls down the page, we can see the sections smoothly sliding frm left to the center of the page.

## Breaking down the code
The JS code utilizes the Intersection Observer API to monitor the visibility of elements with the "hidden" class on the webpage. When an element becomes visible in the viewport, the observer triggers a callback function that adds the "show" class to the element, revealing it with a sliding animation. Conversely, when an element is no longer in the viewport, the "show" class is removed, hiding the element. The code selects all elements with the "hidden" class, iterates through them, and applies the Intersection Observer to each, enabling dynamic visibility changes based on their intersection with the viewport. 
The Intersection Observer is a JavaScript API that provides a way to asynchronously observe changes in the intersection of a target element with an ancestor element or the document's viewport. Shortly, it's like a spy that watches whether these hidden elements are visible in the viewport. 

## Demo
Click <a href="https://teal-chimera-e4ca1d.netlify.app/">here </a>.