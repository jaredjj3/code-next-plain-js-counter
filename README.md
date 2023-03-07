# code-next-plain-js-counter

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/web-platform-2h7hzv)

In this lesson, engineers will

- build a counter component using plain JavaScript
- identify what is difficult about developing with plain JavaScript

## Counter component

### YOUR TURN

Make a counter component in plain JavaScript.

- A display that shows the user what the `count` is at. The `count` should be initialized at 0. 
- A decrement button that subtracts 1 from the current `count` and updates the display.
- An increment button that adds 1 to the current `count` and updates the display.

#### Recipes

##### Get single element matching ID

```js
const countSpan = document.getElementById('count');
```

##### Update inner text of element

```js
countSpan.innerText = 42;
```

##### Add click handler

```js
incrementButton.addEventListener('click', () => {
  console.log('increment button clicked');
});
```

### Reflection

- What was difficult about creating a counter component in plain JavaScript?
- What are the things we were responsible of keeping track of?