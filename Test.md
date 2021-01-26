Example:

```typescript
var shape = {
    name: "rectangle",
    popup: function() {
 
        console.log('This inside popup(): ' + this.name);
 
        setTimeout(function() {
            console.log('This inside setTimeout(): ' + this.name);
            console.log("I'm a " + this.name + "!");
        }, 3000);
 
    }
};
 
shape.popup();
```

wolfram:

```mathematica
Manipulate[
 Plot[Sin[a x + b], {x, 0, 6}], {{a, 2, "Multiplier"}, 1, 
  4}, {{b, 0, "Phase Parameter"}, 0, 10}]
```


