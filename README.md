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

### RULES FRO GIVING VARIABLE NAME
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
    var  My Name= 'Sunny Raj';  ---> WRONG VARIABLE NAME
```
- Variable name are case sensitive:  ``` myname ``` AND ```MyName``` are NOT same.
- No Limit to the length of variable name ( That dont mean you use a long variable name, it should be meaningfull).
- You can't use Javascript reserved words as a variable name. 

# SECTION 2: DATA TYPE (PRIMITIVE)
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

# SECTION 3: EXPRESSION AND OPERATOR
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

### ASSIGNMENT OPERATOR
- An assignment operator assigns a value to its left operand. Based on the value of its right operand.
- The simple assignment operator is equal ```(=)```.
```
    var x =5;
    var y =5;
```

### COMPARISON OPERATOR

####  Equal (==)
```
    var a = 30;
    var b = 10;
    console.log(a==b); // false
```    
#### Not equal (!=)
```
    var a = 30;
    var b = 10;
    console.log(a!=b); // true
```  
#### Graeter than (>)
```
    var a = 30;
    var b = 10;
    console.log(a>b);  // true
```  
#### Graeater than and equal to (>=)
```
    var a = 30;
    var b = 10;
    console.log(a>=b); // true
```  
#### less than (<)
```
    var a = 30;
    var b = 10;
    console.log(a<b);  // false
```  
#### Less tahn equal to (<=)
```
    var a = 30;
    var b = 10;
    console.log(a<=b); // false
```

### LOGICAL OPERATOR

#### Logical AND (&&) 
- It is also known as ```Logical Conjuction```.
- Is true if and only if  all of its operands are true
```
var a = 30;
var b = -20;
console.log(a > b && b > -56 && b < 0);
```
#### Logical OR (||) 
- It is also known as ```Logical Disjunction```.
- Is true if and only if one or more of its operands are true
```
var a = 30;
var b = -20;
console.log(a > b || b > 0 || a < 0);
```
#### Logical NOT (!) 
- It is also known as ```Logical complement, Negation```.
- Takes truth to falsity and vice versa.
```
var a = 30;
var b = -20;
console.log(!(a>0 || b<0));
console.log(!true);
console.log(!false);
```

### STRING OPERATOR
### CONDITIONAL (TERNARY) OPERATOR ``` ( ) ? :```
```
        var age = 17;
        console.log((age >18) ? "VOTE" : " Cant VOTE");
```
### STRING CONCATINATION OPERATOR
- The concatination operator ```(+)``` concatenates two string values together.
returning another string that is union of the two optand strings.
```
        console.log('Hello World');          // Hello World
        console.log('Hello'+'World');        // HelloWorld
        console.log('Hello '+'World');       // Hello World   ---> Giving space inside the quotes
        console.log('Hello'      + 'World'); // HelloWorld    ---> Giving space outside the quotes 

        var MyName = 'Sunny';
        console.log(MyName + 'Raj');        // SunnyRaj
```
### INCREMENT & DECREMENT OPERATOR
```
        var num = 5;
        var newnum = num++ + 5;
        console.log(num);
        console.log(newnum);
```
### EXPONENTIAL OPERATOR
- The Operator ```(**)``` is To the power operator.
- Below are some example:
```
(5**6) ---> 5*5*5*5*5*5
```
- EXPLAINATION: Now ```5**6``` is spell as ```5 to the power 6``` (i.e 5*5*5*5*5*5).
```
console.log(2**3);      OUTPUT:8
console.log(3**3);      OUTPUT:27
```
- EXPLAINATION: Now ```2**3```(i.e 2*2*2) will give output as ```8``` & For ```3**3```(i.e 3*3*3) the output will be ```27```.
Q1. What will be the output of ```(2** -1)```?
- 
# SECTION 4: CONTROL STATEMENT & LOOPS
### IF...ELSE
```
            var age = 18;
            if(age >= 18){
                console.log("Vote");
            } else {
                console.log("Cant Vote");
            }
```  

### NESTED IF...ELSE
### SWITCH STATEMENT
```
var area = "circle"
var PI = 3.142, l=5, b=4, r=3;
if(area = "circle"){
    console.log("the area of the circle is:" + PI*r**2);
} else if(area = "triangle"){
    console.log("the area of the triangle is:" + (l+b)/2);
} else if(area = "rectangle"){  
     console.log("the area of the rectangle is:" + (l*b));
} else{  
    console.log("Please enter a valid shape");
}    
```    


