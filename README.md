# weather-forecast


## Objective: For the Position of Full-Stack Developer

**Requirement:** A single HTML page displaying the 5 day weather forecast for a __location of your choice__.

**Reason:**  This exercise is to help in examining my technical knowledge, reasoning and engineering principals. It should demonstrate my experience and skill using current software development technologies and methods. 


## Approaches:
After reading the Project details provided, I had few ways I could implement it. Instead of creating the product to show data for a specific choice, I have created it to reflect data according to any Zip Code being entered

### Deployment on Client Side:
*Pros: No Backend Needed*

  * Hacky Way(*Pros: No Api needed*) !!
    Use any web page url that shows the weather report, load it's content in a hidden iframe or something similar and then scraping it's html content to find the actual data and show it in the app being developed !

  * Using the OpenWeatherMap API (*Cons: Registeration Required for free subscription*)
    This was mentioned so prefering this approach.
    *  Using HTML5
    *  Using PHP
    *  Using Angular.JS v 1 
    *  Using only JavaScript: choosing React as the preferred framework for this usecase.


### Server Side Approach:
*It was mentioned to demo some Node.js exp*

#### TDD Approach, using Mocha

Choosing pure "request" Node.js module(doesn't have inbuilt Promise) for making requests and wrapping it as a Promise supported module. _Obviously using axios, it would have been simply much easier !!_
***********


### What could be done with more time ?

I believe progress/improvement to be a never ending continuous process. With time many things could be improved to a point where perfection starts seeming to be nearer.

However few of the things that currently comes to mind:

* Include test cases
* Way better UI, with featres like animation etc, for eg if it's raining, the background could have some animations that immitates the real world raining etc...
* Make it more intuitive like instead of zip code it can accept all relevent query using city name,lat-lon etc...


# Instructions
***********
~~TODO~~
