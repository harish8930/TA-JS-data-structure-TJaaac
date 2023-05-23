let character = {
}
undefined
character.["character name"] = "Arya"
VM310:1 Uncaught SyntaxError: Unexpected token '['
character ["character name"] = "Arya"
'Arya'
let age = 20
undefined
age
20
character.age = ["character age"]
['character age']
character ["character age"]  =22
22
character ["surname"] = "stark"
'stark'
character.title = "lady of winterfell"
'lady of winterfell'
character.greet = function greet(){
      alert("I am " + character.characterName + " and my title is " + character.title);
} greet();
VM1063:3 Uncaught SyntaxError: Unexpected identifier 'greet'
character.greet = function greet(){
      alert("I am " + character.characterName + " and my title is " + character.title);
} 
ƒ greet(){
      alert("I am " + character.characterName + " and my title is " + character.title);
}
character.greet
ƒ greet(){
      alert("I am " + character.characterName + " and my title is " + character.title);
}
character.greet = function() {
  alert(`I am ${this.characterName} and my title is ${this.title}`);
};
ƒ () {
  alert(`I am ${this.characterName} and my title is ${this.title}`);
}
charcter.greet =  function() {
  alert(`I am ${this.characterName} and my title is ${this.title}`);
};
VM1211:1 Uncaught ReferenceError: charcter is not defined
    at <anonymous>:1:1
(anonymous) @ VM1211:1
character.greet = character.greet = function() {
  alert(`I am ${this.characterName} and my title is ${this.title}`);
};
ƒ () {
  alert(`I am ${this.characterName} and my title is ${this.title}`);
}
character.greet();
undefined
character.isadult = "true"
'true'
character.isfemale = "true"
'true'
character
{character name: 'Arya', age: Array(1), character age: 22, surname: 'stark', title: 'lady of winterfell', …}age: ['character age']character age: 22character name: "Arya"greet: ƒ ()isadult: "true"isfemale: "true"surname: "stark"title: "lady of winterfell"[[Prototype]]: Object
delete character.isadult
true
character.greet();
undefined
character.greet = function (){
    alert(`she is ${this.["character name"] } and her title is${this.title}`);
VM1983:2 Uncaught SyntaxError: Unexpected token '['
character.greet = function (){
    alert(`she is ${this.["character name"] } and her title is${this.title}`)}
VM1992:2 Uncaught SyntaxError: Unexpected token '['
character.greet = function (){
    alert(`she is ${this.character name } and her title is${this.title}`);}
VM2009:2 Uncaught SyntaxError: Missing } in template expression
character.greet = function (){
    alert(`she is ${this."character name" } and her title is${this.title}`);}
VM2032:2 Uncaught SyntaxError: Unexpected string
character ["character name'] = "charactername"
VM2246:1 Uncaught SyntaxError: Unexpected identifier 'charactername'
character.charactername  =  "Arya"
'Arya'
character.greet = function (){
    alert(`she is ${this.charactername} and her title is${this.title}`);}
ƒ (){
    alert(`she is ${this.charactername} and her title is${this.title}`);}
character.greet();
undefined
character.isadult = if(age>18) {
VM2570:1 Uncaught SyntaxError: Unexpected token 'if'
character.isadult = if(age>18) { alert("true");} else{alert("false")}
VM2687:1 Uncaught SyntaxError: Unexpected token 'if'
character.isadult = function(){
    if(age>18){
        alert("true")}else{
        alert("false")}
}




    
ƒ (){
    if(age>18){
        alert("true")}else{
        alert("false")}
}
charcter.isadult();
VM3002:1 Uncaught ReferenceError: charcter is not defined
    at <anonymous>:1:1
(anonymous) @ VM3002:1
character.isadult();
