---
layout: post
title:  "Day 2 - CSS Grid and Flexbox"
date:   2018-10-25 12:00:00
categories: [learn, 30dayschallenge]
---
#### Grid
Grid is for multi-dimensional layouts (columns and rows).
Below basics syntax:

```
grid-column-start: 1 ;
grid-column-end 2;
grid-template-columns; 20% 20% 20%;
grid-template-rows: 20% 20% 20% 20%;
// short version
grid-column: 1 /2;
grid-template-columns: repeat(4, 20%);
grid-template-rows: repeat(4, 20%);

```

[Learn grid basics with funny editor.](http://cssgridgarden.com/#pl "Learn grid basics with funny editor.")

[ Basic concepts of grid layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout " Basic concepts of grid layout")
#### Flexbox

Flexbox should be used for one-dimensional layouts - line layouts.
Below basics syntax:

```
justify-content: center;
flex-start: //Elements justify to left side of container.
flex-end: //Elements justify to right side of container.
center: //Elements justify to center of container.

```

[Learn flexbox with funny editor.](https://flexboxfroggy.com/#pl "Learn flexbox with funny editor.")

[Basic concepts of flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox "Basic concepts of flexbox")

#### Grid vs Flexbox

![Grid vs Flexbox](/assets/grid_vs_flexbox.jpg)

*Source: *[Quora](https://www.quora.com/What-should-I-learn-for-as-a-new-developer-a-CSS-grid-layout-Module-or-Flexbox "Quora")