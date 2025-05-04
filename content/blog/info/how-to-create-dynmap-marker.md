---
title: How to create dynmap marker
description: How to create dynmap marker using sings. All available icons for markers.
date: 2025-05-04
tags:
  - Info
---

# How to create marker using sign

1. Get sign.
2. Place sign.
3. Write this text on sign:
```js
[dynmap]
icon:<your_icon>
text
text
```

## Explanation:

line 1: dynmap system value, needed to determine marker signs.

line 2: sets icon to your marker (see list below).

line 3-4: Whatever text you want to show on dynmap marker (Marker label).

Hint: To avoid `<br>` bug in marker label on map you can type `icon:<your_icon>` two times (old dynmap little buggy 🙂).
Like this:
```js
[dynmap]
icon:<your_icon>
icon:<your_icon>
text
```

## Example

{% image "./imgs/sign-marker.webp", "Sign marker example." %}

## How to remove marker

1. Break sign.

# How to use icons

Write this on sign after first line to use icon:
```js
icon:<icon_from_list_below>
```

Example:
```js
icon:beer
```

# List of all available icons

* anchor
* bank
* basket
* beer
* bighouse
* blueflag
* bomb
* bookshelf
* bricks
* bronzemedal
* bronzestar
* building
* cake
* camera
* cart
* caution
* chest
* church
* coins
* comment
* compass
* construction
* cross
* cup
* cutlery
* default
* diamond
* dog
* door
* down
* drink
* exclamation
* factory
* fire
* flower
* gear
* goldmedal
* goldstar
* greenflag
* hammer
* heart
* house
* key
* king
* left
* lightbulb
* lighthouse
* lock
* minecart
* offlineuser
* orangeflag
* pin
* pinkflag
* pirateflag
* pointdown
* pointleft
* pointright
* pointup
* portal
* purpleflag
* queen
* redflag
* right
* ruby
* scales
* shield
* sign
* silvermedal
* silverstar
* skull
* star
* sun
* temple
* theater
* tornado
* tower
* tree
* truck
* up
* walk
* warning
* world
* wrench
* yellowflag

# P.S.

Please don't spam dynmap markers. This will be considered a violation of the rules.