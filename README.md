
### Custom Hook
Create a custom hook that allows you to fetch the `movies` from the `Lord of the rings api`.


## Brief
You're creating a fan review website for the Lord of the rings and need movie details. To do 
that, you need to make requests to the Api on multiple pages, so having a reusable hook would 
be helpful. your assignment is to create a custom hook that you can use on any page to request 
movie info from the Api.


## To Do
* Create a new hook
* Create a new request
* Create request states
* Publish to npm
* Create an example


## Level 1
To build a custom hook, the first thing you need is a file that exports a custom function. you 
can do this manually or you can start entire project automatically by using the use custom hook 
starter template.

With the skeleton of a hook, the main purpose will be to fetch data from the Api. set up a request 
mechanism using the browser fetch Api or your favourite request library.


## Level 2
Part of a good request Api is the ability to understand where the request is at during each part of 
its lifecycle. This includes stages like ". loading, success, and failed.

Using React state, configure a variable that you can return from the custom hook to let the component 
know what stage the request is at in its lifecycle.

## Level 3
Ultimately a custom hook is created to be used. publish the new hook to npm(`npmjs.com`) and set a new 
project using the custom hook package. for an advanced feature, add the ability for people to review 
each movie!.


