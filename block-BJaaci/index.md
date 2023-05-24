movies[0].title
'Game Night'
console.log(movies[0].title)
VM266:1 Game Night
undefined
console.log(movies[2].title)
VM379:1 Hannah
undefined
console.log(movies[1].title)
VM522:1 Area X: Annihilation
undefined
console.log(movies[0].year)
VM663:1 2018
undefined
console.log(movies[0].actors)
VM837:1 (3) ['Rachel McAdams', 'Jesse Plemons', 'Jason Bateman']
undefined
console.log(movies[0].actor[0])
VM979:1 Uncaught TypeError: Cannot read properties of undefined (reading '0')
    at <anonymous>:1:28
(anonymous) @ VM979:1
console.log(movies[0].actors[0])
VM991:1 Rachel McAdams
undefined
console.log(movies[1].actor[1])
VM1143:1 Uncaught TypeError: Cannot read properties of undefined (reading '1')
    at <anonymous>:1:28
(anonymous) @ VM1143:1
console.log(movies[1].actors[1])
VM1156:1 Jennifer Jason Leigh
undefined
console.log(movies[2].actors[2])
VM1326:1 Phanie Van Vyve
undefined
console.log(movies[0].genre.length)
VM1556:1 Uncaught TypeError: Cannot read properties of undefined (reading 'length')
    at <anonymous>:1:29
(anonymous) @ VM1556:1
console.log(movies[0].genres.length)
VM1785:1 3
undefined
console.log(movies[0].genres.length-1)
VM1805:1 2
undefined
console.log(movies[0].genres]
VM2117:1 Uncaught SyntaxError: missing ) after argument list
