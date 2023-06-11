# Design

In order to design this around ECS, I want to define as many entities, components, and systems as I can.

## Utility

* Timer component + aspect
* Random component + aspect

## Player+Zombie Related

* Health component
* Heal aspect
* Damage aspect
* Death aspect

## Player-only Related

* Backpack component
* Backpack aspect
* Building aspect
* Upgrade component + aspect
* Shooting aspect

## World Related

* Building grid component + aspect
* Event timer component + aspect (random events)
* Map event component
* Map Indicator aspect
* chunk difficulty component + aspect
* Zombie spawner component+aspect (regards to: radius of player, etc)

## Zombie-only Related

* Dropped Items component/aspect
* Model + animation component/aspect