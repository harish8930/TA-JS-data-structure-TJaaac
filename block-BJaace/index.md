let color = []
undefined
typeof color
'object'
let colors = ["orange", "red" , "black" , "green", "yellow"]
undefined
console.log(colors(0))
VM405:1 Uncaught TypeError: colors is not a function
    at <anonymous>:1:13
(anonymous) @ VM405:1
console.log(colors[0])
VM505:1 orange
undefined
console.log(colors[2])
VM597:1 black
undefined
console.log(colors-length)
VM729:1 NaN
undefined
console.log(colors[4])
VM840:1 yellow
undefined
colors[0] = "black"
'black'
colors[4] = "ultraviolet"
'ultraviolet'
colors
(5) ['black', 'red', 'black', 'green', 'ultraviolet']0: "black"1: "red"2: "black"3: "green"4: "ultraviolet"length: 5[[Prototype]]: Array(0)
let fourthcolor = []
undefined
forthcolor.push("green")
VM1412:1 Uncaught ReferenceError: forthcolor is not defined
    at <anonymous>:1:1
(anonymous) @ VM1412:1
fourthcolor.push("green")
1
colors
(5) ['black', 'red', 'black', 'green', 'ultraviolet']
fourthcolor.push(color[4])
2
fourthcolor
(2) ['green', undefined]0: "green"1: undefinedlength: 2[[Prototype]]: Array(0)
colors[colors.length] = "purple"
'purple'
colors
(6) ['black', 'red', 'black', 'green', 'ultraviolet', 'purple']0: "black"1: "red"2: "black"3: "green"4: "ultraviolet"5: "purple"length: 6[[Prototype]]: Array(0)
colors[0] = "grey"
'grey'
colors
(6) ['grey', 'red', 'black', 'green', 'ultraviolet', 'purple']0: "grey"1: "red"2: "black"3: "green"4: "ultraviolet"5: "purple"length: 6[[Prototype]]: Array(0)
delete colors[0]
true
colors
(6) [empty, 'red', 'black', 'green', 'ultraviolet', 'purple']
 delete colors[6]
true
colors
(6) [empty, 'red', 'black', 'green', 'ultraviolet', 'purple']
delete colors[5]
true
colors
(6) [empty, 'red', 'black', 'green', 'ultraviolet', empty]
delete colors[4]
true
colors
(6) [empty, 'red', 'black', 'green', empty × 2]
for( i =1; i<colors;i++){
    console.log(colors[i]) }
undefined
console.log(colors[i])
VM2544:1 red
undefined
