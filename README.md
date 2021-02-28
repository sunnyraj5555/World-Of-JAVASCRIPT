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
- Bigint:
- Symbol:

## typeof()
- To find the datatype of the variable.
```
    console.log(typeof(MyName));
```
```
    OUTPUT: string
```
