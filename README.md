id-generator
Id-generator is a function, that create random id. You can choose id length.

Installation
Use the package manager to install id-generator.

yarn add @dmkmrv/id-generator
Usage
const randomId = require('@dmkmrv/id-generator')

console.log(randomId(10))
# return random id length 10 char

console.log(randomId(20))
# return random id length 20 char
License
ISC