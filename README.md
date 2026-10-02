# Big title Scroll-Driven Hero Section Animation

A scroll-driven hero section where a top-view car drives across the screen as you scroll. The "WELCOME ITZFIZZ" title is revealed behind the car as it passes, and four stat blocks fade in one after another.

## Smaller heading Live demo: https://himangshu205.github.io/Scroll-Driven-Hero-Section-Animation/

## Smaller heading Features
- Car moves left to right, linked to scroll position
- Title revealed behind the car using CSS clip-path
- Road markings slide backwards to show speed
- Stats fade and float in sequentially
- Responsive layout using viewport units
- No libraries or build step, just HTML, CSS and vanilla JavaScript

### Even smaller Run locally

Download the files and open index.html in a browser.

### Even smaller How it works

The page listens to the scroll event (passive) and calculates scroll progress from 0 to 1. A requestAnimationFrame loop then updates the car position, the title's clip-path, the road markings and the stats opacity from that value.

### Even smaller Customize
Swap car.svg for your own top-view car image (facing right). Keep the <img src="..."> in index.html in sync.
Change the stat text in the .stat blocks in index.html.
