# General Frontend Questions
## difference between throttle and debounce pattern
* write a debounce function
* write a throttle function
## how does the fetch function work
* fetch an API explains what happens
* dev tools stuff

## How does Function.prototype.bind work

## How does Functionprototype.call() and Function.prototype.apply work and when to use them

```
const debounce = (fn, delay) => {
      let timer = null;
      return function (...args) {
          const context = this;
          timer && clearTimeout(timer);
          timer = setTimeout(() => {
              fn.apply(context, args);
          }, delay);
      };
}
```

???

## What's an XMLHttpRequest?
* what's it's relation  with AJAX
* interesting back story
https://xhr.spec.whatwg.org/

## What is a REST API?



## What is the importance of schema design on contexts like GraphQL and Database design

contract between server and client
