# test-image
A standard image to test requests with
<br>
##Installation
npm install test-image
<br>
##Usage Example
`const image = require('test-image')

console.log(image) // http://imgur.com/a/EXsAJ

fetch(image)
.then(response => response.blob())
.then((myBlob) => {
	const img = document.querySelector('img')
	img.src = URL.createObjectURL(myBlob)
})`

