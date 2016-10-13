Selectors
================


document.getElementById
document.getElementByTagName
document.getElementByClassName
document.querySelector
document.querySelectorAll



addEventListener is a method found on all DOM elements.
var button = document.querySelector('#big-button');
button.addEventListener('click', handleClick);

Data is either converted to or from JSON, using methods called stringify and parse respectively
JSON.stringify()
JSON.parse()


var req = new XMLHttpRequest();
req.onload = function (event) { . . . };
req.open('get', 'some-file.txt', true);
req.send();


jQuery is far and away the most popular DOM library and it is used on a huge number of websites