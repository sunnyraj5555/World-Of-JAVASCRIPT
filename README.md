# World-Of-JAVASCRIPT
- This README is going to be best for learning javascript.

### Why javascript ?
- javaScript improves the user experience of the web page by converting it from a static page into a interactive one.

```OR ```

- Javascript adds behaviour to a web page 

## console.log()
- To print hellow world using console
```
    console.log('Hello World');
```

# SECTION 1: VALUES AND VARIABLES 
- Lets take a example:
```
    var MyName = 'Sunny Raj'
``` 
- From the above exapmle: 
- ```var``` is a statement which declares a variable in javaScript.
- ```MyName``` is a variavle name.
- ```'Sunny Raj'``` is the value.
- Variables are containers for storing information. Creating a variable in JavaScript is called "declaring" a variable: ```var MyName```; 

#### RULES FRO GIVING VARIABLE NAME
- The first character must be a letter or an underscore```_``` or Dollar```$```. 
```
    var MyName = 'Sunny Raj';
    var $MyName = 'Sunny Raj';
    var _MyName = 'Sunny Raj';
```    
- You cant use a number as the first character ```var 1MyName = 'Sunny Raj';``` 
- The rest variable name can include any letters, any number, or the underscore. 
```
    var _1My__Name = 'Sunny Raj';
```
- Cant use any other character, including spaces 
```
    var _MyName% = 'Sunny Raj';
    var  My Name= 'Sunny Raj';
    ( Not Correct Declaration)
```
- Variable name are case sensitive:  ``` myname ``` AND ```MyName``` are NOT same.
- No Limit to the length of variable name.
- You can't use Javascript reserved words as a variable name. 

#### DATA TYPE (PRIMITIVE)
- Undefined:  ```var IamStandby;```
- Boolean:  ```var IamRaj = true;```
- Number:  ```var MyAge = 20;```
- String:  ```var MyName = 'Sunny Raj;'```
- Bigint: ?
- Symbol:

## typeof()
- To find the datatype of the variable.
```
    console.log(typeof(MyName));
```
```
    OUTPUT: string
```

Q1. What is difference between ```null``` and ```undefined``` ?
- ```var IamUseless = null;``` : variable Defined and given value null.
- ```var IamStandBy;``` : No value Given

Q2. What is NaN ?
- NaN stands for **Not-A-Number**.
- If We subtract two string we get NaN: 
```
     console.log("Sunny" - "Raj");
```
```
     OUTPUT: NaN
```
- NaN is a property of the global object.
- In other words, it is a variable in global scope.

## isNaN()
- This return true if the 
```
var MyPhoneNumber = 987654321;
var MyName = "Sunny Raj";
console.log(isNaN(MyPhoneNumber));   OUTPUT:false
console.log(isNaN(MyName));          OUTPUT:true
```

#### EXPRESSION AND OPERATOR
```
    Expression -> (Operand + Operator)
    Expression -> (4 + 67)
```
- Where ```4,67``` are operand and ```(+)``` is operator.
- There are following type of Operators:
```
    1. Assignment Operator
    2. Comparision Operator
    3. Logical Operator
    4. String Operator
    5. Conditional (ternary) Operator
    6. Increament & Decrement Operator
```

#### ASSIGNMENT OPERATOR
- An assignment operator assigns a value to its left operand. Based on the value of its right operand.
- The simple assignment operator is equal ```(=)```.
```var x =5;
   var y =5;
```

