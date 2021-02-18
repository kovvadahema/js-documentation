# js-documentation

### Functions
function without parameters
```javascript
function addition(){
var a=10
var b=20
var c=30
}

addition()
30
```

function with parameters
```javascprit
function addition(a,b){
    return (a+b)
}

addition(1,3)
```
Anonymous functions

```javascrip
   var substraction=function(a,b){
    return (a-b)
}
undefined
substraction(1,3)
```
Arrow function
```javascrip
var mul=(a,b)=>{
      return (a*b)
}
mul(1,4)
```
### High order fuction (HOF)
*A function accept another function as an argument.*

```javascript
arr.map((item,index)=>{
        console.log(item+" is having index of :"+index)
})


