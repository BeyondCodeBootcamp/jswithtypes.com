# [jswithtypes.com](https://github.com/BeyondCodeBootcamp/jswithtypes.com)

The source of <https://jswithtypes.com>.

## Quick Start to Render

./bin/render

````mkdn
# Great Title

A great slide

---

# A Second Slide

Another great slide

---

<carousel data-line-start="1" data-slides="1-2|3|4"></carousel>

```js
let a = 1;
let b = 2;
let c = (x) => 1 + 2 + x;
c(3);
```

---

<carousel data-line-start="1" data-slides="1,3|2"></carousel>

```js
function greet() {
  return "Hello, World!";
}
```
````
