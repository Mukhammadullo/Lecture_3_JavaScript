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

let name="Muhammadullo"
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
//method_slice()

let str="Hello my name is Tom"
let result=str.slice(2, 7)
console.log(result) //name


```
## _trim()-Method trim() removes whitespace from both sides of a string.The trim() method does not change the original string_
```js

//method trim()

let str="      Hello my name is Amir      "
let result=str.trim()
console.log(result) //Hello my name is Amir
console.log(str)   //      Hello my name is Amir      
```





