[![Build Status](https://travis-ci.org/roli93/js-pattern-matching.svg?branch=master) ]( https://travis-ci.org/roli93/js-pattern-matching)
[![Dependency Status](https://david-dm.org/roli93/js-pattern-matching.svg)](https://david-dm.org/roli93/js-pattern-matching)
[![devDependencies Status](https://david-dm.org/roli93/js-pattern-matching/dev-status.svg)](https://david-dm.org/roli93/js-pattern-matching?type=dev)

JS Pattern Matching
====================
A small library intended to provide simple Pattern Matching capabilities for JavaScript.

```javascript 
const sum = (list) =>  match (list) (
  ([x,...xs]) => x + sum(xs),
  ([]) => 0
)

console.log(sum([]));
// prints 0
console.log(sum([1,2,3]));
// prints 6
``` 


