---
layout: post
title:  "Day 6 - JavaScript - hoisting, event bubbling, prototype etc."
date:   2018-10-29 14:00:00
categories: [learn, 30dayschallenge]
---

#### Hoisting
That's mean that JS engine moves all variables to beginning of the lexical scope.

**Example:**

```javascript
function hoisting() { console.log(x); // undefined - that's mean that variable x aleready exists! 
  if (true) {
    var x = 1;
  }
console.log(x); // 1
}
```

JS engine transform above code:

```javascript
function hoisting() { 
var x; //JS moves variables declaration to begining
console.log(x); 
  if (true) {
    var x = 1;
  }
console.log(x);
```
**More informations and examples**
[MDN web docs](https://developer.mozilla.org/pl/docs/Glossary/Hoisting)

## Tips

**Good practice - declare all variables on the beginning of the code**

## Event bubbling

Event Bubbling is the event starts from the deepest element or target element to its parents, then all its ancestors which are on the way to bottom to top.

![Event bubbling](/assets/event_bubbling.png)

*Source [javascript.info](https://javascript.info/bubbling-and-capturing)*

**More informations**
[Medium](https://medium.com/@vsvaibhav2016/event-bubbling-and-event-capturing-in-javascript-6ff38bec30e)
[javascript.info](https://javascript.info/bubbling-and-capturing)

## Prototype

