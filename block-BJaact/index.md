let person = {
  firstName: 'John',
  lastName: 'Doe',
  address: {
    street: 'North 1st',
    city: 'San Jose',
    state: 'CA',
    country: 'USA',
  },
};

let personTwo = { ...person };

person.firstName = 'Arya';
person.city = 'Navada';


'Navada'
console.log(personTwo.firstName)
VM38:1 John
undefined
console.log(person.firstName);
VM42:1 Arya
undefined
console.log(personTwo.lastName);
VM46:1 Doe
undefined
console.log(person.firstName === personTwo.firstName);
VM50:1 false
undefined
console.log(person == personTwo);
VM54:1 false
undefined
console.log(person === personTwo);
VM58:1 false
undefined
console.log(person.address === personTwo.address);
VM62:1 true
undefined
console.log(personTwo.address.city);
VM66:1 San Jose
undefined
console.log(person.address.city); 
VM70:1 San Jose
undefined
console.log(person.address.city == personTwo.address.city)
VM74:1 true
undefined
let person = {
  firstName: 'John',
  lastName: 'Doe',
  address: {
    street: 'North 1st',
    city: 'San Jose',
    state: 'CA',
    country: 'USA',
  },
};

let personTwo = { ...person, address: { ...person.address } };

person.firstName = 'Arya';
person.city = 'Navada';

'Navada'
console.log(personTwo.firstName);
VM82:1 John
undefined
console.log(person.firstName)
VM86:1 Arya
undefined
console.log(personTwo.lastName);
VM90:1 Doe
undefined
console.log(person.firstName === personTwo.firstName);
VM94:1 false
undefined
console.log(person == personTwo);
VM98:1 false
undefined
console.log(person.address === personTwo.address);
VM102:1 false
undefined
console.log(personTwo.address.city);
VM106:1 San Jose
undefined
console.log(person.address.city);
VM110:1 San Jose
undefined
console.log(person.address.city == personTwo.address.city);
VM114:1 true
undefined
let blogs = [
  {
    id: 1,
    title: 'Post #1',
    body: 'My first blog post',
  },
  {
    id: 2,
    title: 'Post #2',
    body: 'My second blog post',
  },
  {
    id: 3,
    title: 'Post #3',
    body: 'My third blog post',
  },
];
undefined
let clonedblogs = {...blogs}
undefined
clonedblogs
{0: {…}, 1: {…}, 2: {…}}0: {id: 1, title: 'Post #1', body: 'My first blog post'}1: {id: 2, title: 'Post #2', body: 'My second blog post'}2: {id: 3, title: 'Post #3', body: 'My third blog post'}[[Prototype]]: Object
var questions = [
  {
    prompt: 'Why is the sky blue?',
    responses: [
      'Because the color blue was on sale at Wallmart',
      'Because blue is the prettiest color',
      'Because the air molecules difract blue light more than any other color',
    ],
  },
  {
    prompt: 'Why are leaves usually green?',
    responses: [
      'So green caterpillars can hide better.',
      'Because leaves can more easily make energy with green light',
      "Because leaves absorb red and blue light so it's green that is reflected",
    ],
  },
];
undefined
let questionvariable = {...question}
VM309:1 Uncaught ReferenceError: question is not defined
    at <anonymous>:1:24
(anonymous) @ VM309:1
let questionvariable = {...questions}
undefined
qusetionvariable
VM501:1 Uncaught ReferenceError: qusetionvariable is not defined
    at <anonymous>:1:1
(anonymous) @ VM501:1
questionvariable
{0: {…}, 1: {…}}
