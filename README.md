# Companion

A standalone Tamagotchi-style virtual companion built with pure HTML, CSS, and JavaScript.

Hatch a pet, care for its needs, watch it explore its habitat, and see it grow and evolve throughout its life.

## Features

* Egg incubation and hatching
* Baby → Juvenile → Adult → Elder lifecycle
* Species-specific evolution and lifespan
* Autonomous movement
* Feed, play, and pet interactions
* Fullness, happiness, and energy stats
* Persistent progress using `localStorage`
* Installable as a PWA

## Pets

| Pet           | Lifespan | Likes                     | Main Trait                             |
| ------------- | -------: | ------------------------- | -------------------------------------- |
| **Luma Fox**  |  24 days | Chase games, night lights | Stronger play, slower loneliness       |
| **Mossling**  |  30 days | Snacks, quiet corners     | Better feeding, slower hunger          |
| **Byte Cat**  |  22 days | Head pats, puzzles        | Stronger affection and play            |
| **Spark Bot** |  18 days | Games, recharging         | Stronger play and energy recovery      |
| **Moon Bun**  |  27 days | Affection, naps           | Stronger affection and energy recovery |

Each pet evolves when it reaches adulthood and eventually progresses into its elder stage.

## Running

Open `glance-companion.html` in a modern browser. No dependencies, frameworks, accounts, or backend are required.

For PWA installation, serve the app over **HTTPS** or **localhost**.

All companion data is stored locally in the browser using `localStorage`.
