# Objectives
###### Define what the DOM is
###### Understand why DOM Manipulation is awesome
###### List a few examples of sites that use JS to manipulate the DOM
###### Understand the SELECT, then MANIPULATE workflow



## EXAMPLES OF USABILITY: 

* Games 
* Scrolling Effects
* Dropdown menus
* Form Validations
* Interactivity
* Animations


Websites to mess around with: 
patatap.com 

The Dom 
1. Document Object Model 
The Document Object Model is the interface between your Javascript and HTML+CSS

Special javascript objects that we can use to i
interact with our html and css 


 
![DOM](.. ⁨Desktop⁩⁨/first-app⁩ ▸ ⁨js-dom-manipulation⁩)

![DOM](../dektop/)

type in GOogle Chrome Console. 
document 
#document 
console.dir(document); 


The Process: Select an element and then manipulate. 


Select an element and then MANIPULATE: 
Select the <h1> and save to a variable 

var h1 = document.querySelector("h1"); 

h1.style.color ="pink"; 



document.url; 
document.head; 
document.body; 
document.links; 

Methods
The document comes with a bunch of methods for selecting elements.  We're going to learn about the following 5:

document.getElementById()
document.getElementsByClassName()
document.getElementsByTagName()
document.querySelector()
document.querySelectorAll()