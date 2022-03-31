# Quiz 4

1. x is the parameter, 100 is the argument.
        
2. The first is a declaration, the second an expression.
```javascript

function sayHello(name) {
return `Hey, ${name}! It's Geography Y'all`
}

console.log (sayHello("Boyd"))

var helloYall = function(name) {
return `Hey, ${name}! It's Geography Y'all`

}
console.log (helloYall("Boyd"))
```
3. Output is 9.
```javascript
var myNum = [3];
logNumsToConsole(myNum);
function logNumsToConsole(num){
        for(var i=0; i < num.length; i++){
        var squareNumValue = squareNum(num[i]);
        console.log(squareNumValue);
        }
}
function squareNum(num){
        return num * num;
}
```
4. It returns "7" because 7 is equal to, not greater than, 7.  The `else` branch is executed because 7 > "7" is not true.
5. capitalizedName only holds meaning within the function. `capitalizedName` is scoped to the function and is not globally accessible.
```javascript

var geographer = 'ptolemy';
function shoutName(geoName) {
        var capitalizedName = geoName.toUpperCase();
        console.log(capitalizedName)
};
shoutName(geographer)

```