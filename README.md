# Recipe Page

A recipe card built with semantic HTML and CSS — featuring an ingredients list, step-by-step instructions, a nutrition table, and a continuously animated gradient border.

## Features

- Semantic HTML structure using `<article>`, `<section>`, `<ul>`, `<ol>`
- Real `<table>` markup for the nutrition breakdown, not styled `<div>`s pretending to be one
- A rotating conic-gradient border wrapped around the whole card, built with a `::before` pseudo-element
- Fully responsive spacing using `rem` units throughout

## Tech Stack

- HTML5
- CSS3

## Getting Started

Clone the repo and open it in your browser:

```bash
git clone https://github.com/waqasahmiii/recipe-page.git
cd recipe-page
```

Then just open `index.html` — no build step required.

## What I practiced

- Choosing semantic tags over generic `<div>`s
- Structuring `<table>` markup correctly (`<tr>` / `<td>`, not `<ul>` pretending to be a table)
- Layering a `::before` pseudo-element behind content using `position: relative` + `z-index`
- Preventing layout overflow with `box-sizing: border-box`

## Status

Second project in my self-taught frontend roadmap, built after a Personal Profile Page. More projects to follow.
