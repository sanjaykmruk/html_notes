# This file contains notes from my Typescript/Angular learning 

## var vs let

### var
- `var` is function scoped
- `var` does not  hold type information
```
var i =10;
i = `a`; # will not give error
i = 20;  # is ok as well
```
  
  
  
### let  
- `let` is block scoped
- `let` hold type information of a variable and gives compilation error if you change type
```
  let i =10;
  i = `a`; # will give error
  i = 20; # is ok
```
- `let` infer the type of variable implicitly (as above) or you can set it explicitly(as below)
```
  let i:number;
  i =20; # ok
  i= "a";  # not ok
```

