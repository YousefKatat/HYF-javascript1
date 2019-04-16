

 ## Exercises

 ### 1

```js

{   // 1
  function f(param_1, param_2, param_3) {
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "y", arg_2 = "x", arg_3 = "z";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "zyx", "1: return_val === " + return_val);
}
```

 ### 2

```js

{  // 2
  function f(param_1, param_2, param_3) {
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "x", arg_2 = "z", arg_3 = "y";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "yxz", "2: return_val === " + return_val);
}
```

 ### 3

```js

{  // 3
  function f(param_1, param_2, param_3) {
    var _ = param_2;
    param_2 = param_1;
    param_1 = _;
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "z", arg_2 = "x", arg_3 = "y";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "yxz", "3: return_val === " + return_val);
}
```

 ### 4

```js

{  // 4
  function f(param_1, param_2, param_3) {
    var _ = param_2;
    param_2 = param_3;
    param_3 = _;
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "y", arg_2 = "x", arg_3 = "z";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "xyz", "4: return_val === " + return_val);
}
```

 ### 5

```js

{  // 5
   function f(param_1, param_2, param_3) {
    var result = param_3 + param_1 + param_2;
    return result;
   };

   let x = "x", y = "y", z = "z";
   let return_val = f(y, z, x);

   console.assert(return_val === "xyz", "5: return_val === " + return_val);
}
```

 ### 6

```js

{  // 6
   function f(param_1, param_2, param_3) {
    var result = param_2 + param_1 + param_3;
    return result;
   };

   let x = "x", y = "y", z = "z";
   let return_val = f(z, x, y);

   console.assert(return_val === "xzy", "6: return_val === " + return_val);
}
```

 ### 7

```js

{  // 7
   function f(param_1, param_2, param_3) {
    var result = param_3 + param_1 + param_2;
    return result;
   };

   let arg_1 = "z", arg_2 = "y", arg_3 = "x";
   let return_val = f(arg_1, arg_2, arg_3);

   console.assert(return_val === "xzy", "7: return_val === " + return_val);
}
```

 ### 8

```js

{  // 8
   function f(param_1, param_2, param_3) {
    var result = param_2 + param_3 + param_1;
    return result;
   };

   let arg_1 = "z", arg_2 = "y", arg_3 = "x";
   let return_val = f(arg_1, arg_2, arg_3);

   console.assert(return_val === "yxz", "8: return_val === " + return_val);
}
```
