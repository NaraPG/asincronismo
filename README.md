# Asynchronous

## This repository
> In this course we learned the main asynchronous concepts as they are what are callbacks, promises and async/await and made some examples.

## What is synchronous?
> Synchronous means to be in a sequence, every statement of the code gets executed one by one. So, basically a statement has to wait for the earlier statement to get executed.

## What is asynchronous?
> Using asynchronous JavaScript (such as callbacks, promises, and async/await), you can perform long network requests without blocking the main thread.

## Main Content
> - `Callback vs Promesas vs Async/Await`
> - `Callbacks`: In JavaScript, a callback is a function passed into another function as an argument to be executed later.
> - `Promises`:A promise is an object that may produce a single value some time in the future: either a resolved value, or a reason that it’s not resolved. A
> promise may be in one of 3 possible states: 
>    * Fulfilled 
>    * Rejected
>    * Pending.
> - `Async/Await`: Is the extension of promises which we get as a support in the language.
>    * `Async`: It simply allows us to write promises based code as if it was synchronous and it checks that we are not breaking the execution thread. It operates asynchronously via the event-loop.
>        ```      
>        const getData = async() => {
>        var data = "Hello World";
>        return data;
>        }
>  
>        getData().then(data => console.log(data));
>        ```
>    * `Await`: Is used to wait for the promise. It could be used within the async block only. It makes the code wait until the promise returns a result.
>        ```      
>        const getData = async() => {
>        var y = await "Hello World";
>        console.log(y);
>        }
>        console.log(1);
>        getData();
>        console.log(2);
>        ```


## Documents
> - index.js
> - challenge.js
> - fetchdata.js

## Technologies
> - JavaScript

## Run Code
> You can only run this project by file, using the extension [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) then select the code and use left click and `Run Code` . Now you'll see the code running in the terminal.

## Dependencies
> - Install [VS Code](https://code.visualstudio.com/download)
> - Install [Node.js](https://nodejs.org/en/)

_Created by Nara Peña Gámez._
