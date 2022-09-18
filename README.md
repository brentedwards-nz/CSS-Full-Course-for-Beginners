# CSS-Full-Course-for-Beginners
CSS Full Course for Beginners

https://www.youtube.com/watch?v=n4R2E7O-Ngo

## Chapter 1
### Style Sheets

#### External
``
    <link rel="stylesheet" href="css/style.css">
``

#### Internal
```
    <style>
        p {
            color: limegreen;
        }
    </style>
``` 

#### Inline
```
<p style="color:red">I am red</p>
```

## Chapter 1
### Selectors

- remember last rule wins unless specificity overrides

#### reset 
* {
    font-family: Arial;
}

#### element
```
p {
    color: purple;
}
```

#### class
```
.grey {
    color: grey;
}
```

#### id
```
#second {
    color: pink;
}
```

#### div or h2
div, h2 {
    color: blue;
}

#### div and h2 (nested)
div h2 {
    color: silver;
}
