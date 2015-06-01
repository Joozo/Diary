```html
.parent {
    width: 200px;
    height: 200px;
    background-color: black;
}
.child {
    position: relative;
    height: 100px;
    width: 100px;
    top: 50%;
    left: 50%;
    background-color:red;
    -webkit-transform: translateX(-50%) translateY(-50%);
    -moz-transform: translateX(-50%) translateY(-50%);
    -o-transform: translateX(-50%) translateY(-50%);
    -ms-transform: translateX(-50%) translateY(-50%);
    transform: translateX(-50%) translateY(-50%);
}
```
