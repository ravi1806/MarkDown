just use indentation for code(double tabs).

    var x = 10;
    var y = 20;
    
An inline code can be used inside single backticks like this `var x = 10`


A better way is to use backticks followed by optional language name

  ```js
    var x = 10;
    var y = 20;
  ```
  
  ```php
    $myphpvar = 10;
    echo $myphpvar;
  ```

We can use diff too. Put in the place we usually put the language name. Use - sign before line deleted and + before line added

```diff
var z = 12;
- var x = 10;
+ var x = 13;
```
