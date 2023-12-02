# _1.Create string in java script_
```js
//double quotes ""

let name="Muhammadullo";
console.log(name)

//single qoutes ''

let surname='Nastulloev';
console.log(surname)


//Bickticks 
//1
let name=`Muhammadullo`
console.log(name)
//2
let name=`Muhammadullo ${"Nastulloev"}`
console.log(name) //Muhammadullo Nastulloev

```


# _2.JavaScript string merthods_
> ## _CharAt()-The charAt() method returns the character at a specified index (position) in a string._

```js
//method CharAt()

let name="Mukhammadullo"
console.log(name.charAt(1)) //u

```
> ## _at-method takes an integer value and returns a new String.This method allows for positive and negative integers._
```js
//method at()

let name="Muhammadullo"
console.log(name.at(-1)) //o


```
>## _concat()-The concat() method joins two or more strings.The concat() method returns a new string._    
```js

//method concat()

let name="Muhammadullo";
let lastName="Nastulloev";

console.log(lastName.concat(name))  // Nastulloev Muhammadullo  

```
## _replace()-The replace() method returns a new string with the value(s) replaced.The replace() method does not change the original string._
```js

//method replace()

let name="Nastulloev Muhammadullo"
let result=name.replace("Muhammadullo", "Muhammad")
console.log(result) // Nastulloev Muhammad


let newStr="My name is Amir."
let result=newStr.replace("i", "o")
console.log(result) // My name os Amir.

```

>## _replaceAll()-The replaceAll() method returns a new string with all matches of a pattern replaced by   a replacement_

```js

//method-replaceAll()

let str="black yellow green red "
let result=str.replaceAll("e", "p")
console.log(result) //black ypllow grppn rpd

```

>## _split()-The split method splits a string into an array of substrings.The split() methods new array_

```js

//1
//method-split()
let str="Hello"
let result=str.split()
console.log(result) // ["Hello"]

//2
let str="Hello my name is Muhammad"
let result=str.split(" ")
console.log(result) // ["Hello" , "my" , "is" , "Muhammad"]


//3
let str="Hello my name is Muhammad"
let result=str.split(" ", 2)
console.log(result) // ["Hello" , "my"]
```
>## _substring()-The substring() method does not change the original string._
```js

//method substring()

let str="Hello my name is Tom"
let result=str.substring(5) 
console.log(result) // my name  is Tom


let str="Hello my name is Alex"
let  result=str.substring(-1)
console.log(result) // Hello my name is Alex


```
>## _slice()-This method is used to extract a portion of a string or an array.The substring method returns a new string that includes the characters from the starting index up to, but not including, the ending index.$Ru:Этот метод используется для извлечения части строки или массива.Метод slice возвращает новую строку или массив, включающий символы или элементы от начального индекса до, но не включая, конечный индекс._
```js
//method_slice(start, end)

//1
let str="Hello my name is Tom"
let result=str.slice(2, 7)
console.log(result) //name

//2

let str="Hello my name is Hamza"
let resutl=str.slice(3)
console.log(result)  //name is Hamza

```
>## _trim()-Method trim() removes whitespace from both sides of a string.The trim() method does not change the original string_
```js

//method trim()

let str="      Hello my name is Amir      "
let result=str.trim()
console.log(result) //Hello my name is Amir
console.log(str)   //      Hello my name is Amir      
```

>## _The repeat() method creates a new string by repeating the given string a specified number oftimes and returns it._
```js
//method repeat()

let str="Welcome to Softclub "
let result=str.repeat(2)
console.log(result) //Welcome to Softclub Welcome to Softclub 

```
>## _The indexOf() method returns the position of the first occurrence of a value in a string._
```js
//method indexOf()

let str="Javascript is programming language!"
let result=str.indexOf()
console.log(result)  //11

```

>## _The includes() method returns true if a string contains a specified string.Otherwise it returns false.The includes() method is case sensitive_
```js
//method includes()

//1
let str="Hello my name is Amir"
let result=str.includes("is")
console.log(result)   //true

//2
let str="Hello my name is Tom"
let result=str.includes("Jony")
console.log(result) //false

```

>## _The toLowerCase() method converts a string to lowercase letters.The toLowerCase() method does not change the original string._
```js 

//method toLowerCase()

let str="CAN YOU GIVE ME YOUR BOOK PLEASE!"
let result=str.toLowerCase()
console.log(result) //can you give me your book please!
```

>## _The toUpperCase() method converts a string to uppercase letters, using current locale.The toUpperCase() method does not change the original string._
```js
//method toUpperCase()

let str="can you give me your book please!"
let result=str.toUppeCase()
console.log(result) //CAN YOU GIVE ME YOUR BOOK PLEASE!

```

# _2.JavaScript number methods_
> _1.The Math.floor() function rounds down a number to the next smallest integer_
```js

let num=48.9
console.log(Math.floor(num)) //48
```
> _2.The Math.round() function returns the number rounded to the nearest integer_
```js

let num=3.7
console.log(Math.round(num)) // 4


let num=3.3
console.log(Math.round(num)) //3


```
> _3.The ceil() method rounds a decimal number up to the next largest integer and returns it._
```js

let num=3.2
console.log(Math.ceil(num)) //4

```
> _4.The max() method finds the maximum value among the specified values and returns it_
```js
let numbers=Math.max(12,3,2,4,6,7,1,25)
console.log(numbers) //25
```
> _5.The min() method finds the minimum value among the specified values and returns it._
```js
let numbers=Math.min(12,3,2,5,-23,6,3,8)
console.log(numbers) //-23

```
> _6.The pow() method computes the power of a number by raising the second argument to the power of the first argument_
```js
let num=Math.pow(5,2)
console.log(num) //25
```
> _7.The sqrt() method computes the square root of a specified number and returns it_
```js
let num=Math.sqrt(4)
console.log(num) //2
```
> _8.The abs() method finds the absolute value of the specified number (without any sign) and returns it._
```js
let num=Math.abs(-23)
console.log(num) //23
```
> _9.The Math.random() function returns a floating-point, pseudo-random number between 0 (inclusive) and 1 (exclusive)_
```js

let num=Math.random()*10
console.log(num)  //2.342234233434341
```
> _10.The isNaN() function checks if a value is NaN (Not-a-Number) or not._
```js
let num=10;
console.log(isNaN(num)) //false
```



