# Exercises for JS1 Lesson 4.3: Updating HTML Content Dynamically

## Exercise 1

Given the Array of objects: 
```js
const programmingLanguages = [
    { lang: "C", rank: 5 },
    { lang: "Go", rank: 7 },
    { lang: "JavaScript", rank: 2 },
    { lang: "C++", rank: 6 },
    { lang: "Swift", rank: 9 },
    { lang: "Python", rank: 1 },
    { lang: "PHP", rank: 10 },
    { lang: "Java", rank: 3 },
    { lang: "R", rank: 8 },
    { lang: "C#", rank: 4 }
];
```

a) Populate an `ul` with list items, that is given the value from the `rank` and `lang` property in each object from the Array, using a template-function: Looking like this `<li>3. C</li>` (use `${expressions}` in the list item).

b) Make a button on the page, and make an eventlistner that - when clicked - sorts the list ascending based on rank and update the list. 

## Exercise 2

Given the Array of objects: 
```js
const bigCats = {
    "felidae": [
        { "name": "Tiger", "latin": "Panthera tigris", "location": "Asia", "genus": "Panthera", "url": "https://en.wikipedia.org/wiki/Tiger"},
        { "name": "Lion", "latin": "Panthera leo", "location": "Sub-Saharan Africa, Gir Forest in India", "genus": "Panthera", "url": "https://en.wikipedia.org/wiki/Lion"},
        { "name": "Jaguar", "latin": "Panthera onca", "location": "The Americas", "genus": "Panthera", "url": "https://en.wikipedia.org/wiki/Jaguar"},
        { "name": "Leopard", "latin": "Panthera pardus", "location": "Asia, Africa", "genus": "Panthera", "url": "https://en.wikipedia.org/wiki/Leopard"},
        { "name": "Snow leopard", "latin": "Panthera uncia", "location": "Mountains of Central and South Asia", "genus": "Panthera", "url": "https://en.wikipedia.org/wiki/Snow_leopard"},
        { "name": "Cheetah", "latin": "Acinonyx jubatus", "location": "Sub-Saharan Africa and Iran", "genus": "Acinonyx", "url": "https://en.wikipedia.org/wiki/Cheetah"},
        { "name": "Cougar", "latin": "Puma concolor", "location": "North and South America", "genus": "Puma", "url": "https://en.wikipedia.org/wiki/Cougar"}
    ]
};
```

a) Populate an `ul` with list items, using a template-function, the list items should look like this: like this `<li><strong>Tiger</strong> (Panthera tigris)</li>` (use `${expressions}` in the list item).

> Tip: Look at the demo from this lesson.

Level 2: 

a) Using JS, change the mouse pointer (cursor) to a pointer.

b) Add [`data-*` attributes](https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_data_attributes) for name, location and url for all `<li>` items.

c) When an item in the list is hovered over, it should display, with the location pulled from the `data-*` attribute:

`<li>Tiger (Panthera tigris) can be found in Asia</li>`

(When no longer hovered over it should go back to the original.)

d) When an item in the list is clicked on, it should open the url from its data-url in a new window/tab.

> Tip: look at [`window.open()`](https://developer.mozilla.org/en-US/docs/Web/API/Window/open1)

e) Can you use the `window.open()` `target` attribute to make sure any given link will max open one new window/tab and just refreshes that tab/window on subsequent clicks?

> Tip: There's a reason you made the data-name attribute...


## Exercise 3

TBD