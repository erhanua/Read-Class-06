# Read-Class-06

>JavaScript Object Basics
 

### 1-How would you describe an object to a non-technical friend you grew up with?
Think of an ID card. On this card, you have your name, surname, date of birth, and a photo. The ID card brings together information that identifies you.

In programming, we can think of this ID card as an "object". Your name is one property of the object; your surname is another property; your date of birth and photo are other properties.

In this way, an object is like an ID card that brings together different pieces of information or properties that define a particular thing.

### 2-What are some advantages to creating object literals?
The advantages of using object literals to create objects include convenience, flexibility in declaration, and less code during declaration. You can drop an object literal anywhere in your program with no previous setup and it’ll work, which can be very handy! 
### 3-How do objects differ from arrays?
Arrays are best to use when the elements are numbers. Objects are best to use when the elements' strings (text). The data inside an array is known as Elements. The data inside objects are known as Properties which consists of a key and a value.
### 4-Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
**Dot Notation Property Accessor**
The Dot Notation approach involves using a dot or period (.) and a key to access a property. Here's the syntax:
```javascript
object.key
You have the dot then the key of the property you want to access. This expression will return the value of the property. Let's see an example:

const obj = {
  name: "deeecode",
  age: 80,
  language: "javascript",
}
```
```javascript
const target = obj.name
// deeecode
```
By using dot and the name key, .name, we get "deeecode" which is the value of the name property.

You can also use this notation to modify an existing property:
```javascript
const obj = {
  name: "deeecode",
  age: 80,
  language: "javascript",
}

obj.age = 100
```
```javascript
console.log(obj)
// {
//   name: "deeecode",
//   age: 100,
//   language: "javascript"
// }
```
Here, we modify the age property.

Also, you can add a new property using this approach:
```javascript
const obj = {
  name: "deeecode",
  age: 80,
  language: "javascript",
}

obj.location = "Mercury"
```

```javascript
console.log(obj)
// {
//   name: "deeecode",
//   age: 80,
//   language: "javascript",
//   location: "Mercury"
// }
```
**Bracket Notation Property Accessor**
The Bracket Notation approach involves using square brackets, in which you have an expression that evaluates to a value. That value serves as a key for accessing the property. Here's the syntax:

object[expression]
The expression within the brackets evaluates to a key for the property you want to access, and this expression will return the value of the property. Let's see an example:
```javascript
const obj = {
  name: "deeecode",
  age: 80,
  language: "javascript",
}

const target = obj["name"]
// deeecode
```


By using square brackets and a "name" string expression, ["name"], we get "deeecode" which is the value of the name property.

You can also use this approach to modify an existing property:
```javascript
const obj = {
  name: "deeecode",
  age: 80,
  language: "javascript",
}

obj["age"] = 100
```
```javascript
console.log(obj)
// {
//   name: "deeecode",
//   age: 100,
//   language: "javascript"
// }
```
Here, we modify the age property using an "age" string expression.

And, you can add a new property using square brackets:
```javascriprt
const obj = {
  name: "deeecode",
  age: 80,
  language: "javascript",
}

obj["location"] = "Mercury"
```

```javascript
console.log(obj)
// {
//   name: "deeecode",
//   age: 80,
//   language: "javascript",
//   location: "Mercury"
// }
```
### 5- Evaluate the code below. What does the term this refer to and what is the advantage to using this?
In the context of the humanAge method, the term this refers to the dog object itself. When the humanAge method is called on the dog object, this will point to the dog object, allowing you to access its properties (name, age, etc.).


### 1-What is the DOM?
DOM (Document Object Model) is a programming interface for web documents. It represents the structure of a document as a tree of objects. Each object corresponds to a part of the document, such as an element or an attribute. The DOM provides a way for programs to manipulate the structure, style, and content of web documents.
### 2-Briefly describe the relationship between the DOM and JavaScript.
the DOM represents the structure and content of a web document, while JavaScript provides the means to interact with and modify the DOM dynamically, creating interactive and dynamic web experiences.

