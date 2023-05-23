let students ={
}
undefined
students.studentname = "Harish"
'Harish'
console.log(student.studentname)
VM363:1 Uncaught ReferenceError: student is not defined
    at <anonymous>:1:13
(anonymous) @ VM363:1
console.log(students.studentname)
VM376:1 Harish
undefined
students.batch = 16
16
console.log(students.batch)
VM551:1 16
undefined
students.isadult = "true"
'true'
console.log(students.isadult)
VM756:1 true
undefined
student[42] = "the answer to the meaninng of life"
VM897:1 Uncaught ReferenceError: student is not defined
    at <anonymous>:1:1
(anonymous) @ VM897:1
students[42] = "the answer to the meaninng of life"
'the answer to the meaninng of life'
console.log([42])
VM992:1 [42]
undefined
console.log(students[42])
VM1104:1 the answer to the meaninng of life
undefined
students
{42: 'the answer to the meaninng of life', studentname: 'Harish', batch: 16, isadult: 'true'}42: "the answer to the meaninng of life"batch: 16isadult: "true"studentname: "Harish"[[Prototype]]: Object
students
{42: 'the answer to the meaninng of life', studentname: 'Harish', batch: 16, isadult: 'true'}42: "the answer to the meaninng of life"batch: 16isadult: "true"studentname: "Harish"[[Prototype]]: Object
delete students.isadult
true
students
{42: 'the answer to the meaninng of life', studentname: 'Harish', batch: 16}42: "the answer to the meaninng of life"batch: 16studentname: "Harish"[[Prototype]]: Object
students.batch = 17
17
console.log(students.batch)
VM1448:1 17
undefined
