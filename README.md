This is a city-building simulator created during my second semester of studies, built with Swing.
The game features a randomly generated map that you can navigate using the arrow keys.

# Features

## Build
Plan the layout of residential, commercial and industrial zones with your mouse.

Once areas get access to roads, water and electricity,
buildings start to emerge and new residents start to move in.

*put gif of gameplay here*

## Keep your citizens happy
Track the happiness of your citizens to understand why the population isn't growing despite available housing.

Improve living conditions by placing special buildings like fire stations, schools or hospitals.

*put image of statistics here*

## Plan your budget
Monitor your budget to avoid overspending.

You can also check whether water or electricity production meets demand to
avoid overspending on maintenance of unnecessary infrastructure.
Regularly check if the cost of living in your city overwhelms your citizens' as it affects their well-being.

<sup>(or just raise taxes while ignoring their suffering)</sup>

## Manage infrastructure capacity
Water and electricity flows through your city via pipes and wires.

Plan your infrastructure carefully to ensure that all areas receive sufficent resources before they get used up by other buildings.

*put gif of clogged pipe here*

## Randomly generated terrain
Before the game starts, the terrain is procedurally generated based on the [Perlin noise](https://en.wikipedia.org/wiki/Perlin_noise) algorithm.

Terrain determines where buildings can be placed, as some areas can be flooded and therefore... unsuitable.

## Modifiability
The game can be extended by modifying some files, allowing you to customize gameplay behavior.
These files include:
- `spritemap.png`
- `infrastructure.json`

These files define building behavior and are loaded during application startup.
