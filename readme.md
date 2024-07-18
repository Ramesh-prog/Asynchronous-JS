sync in js :- 

synchronous means the code runs is a particular sequence of instance given in the program.Each instruction waits for the previous instruction to complete its execution. 

Asynchronous in JS :- 

Due to synchronous programming , sometimes important instruction get blocked due to some previous instruction, which causes a delay in the UI, Asynchronous code execution allows to executenext instruction immediately and does't block the flow.

promise :- 

- in javascript a promise is a good way to handle asynchronous operation, it is used to find out if the asynchronous operation is successfully completed or not. 
- a promise may have one of three states.
1. pending
2. fulfilled (Resolve)
3. Reject

promise(pending) -> fullfill (.then)
                 -> reject (.catch)

creating promise :- 

- to create a promise object, we use the promise() constructor.
syntax :- 

let promise = new promise(function(resolve,reject){
    // do something
})

promise()
    .then(........)
    .catch(........)

- the promise() constructor takes a function as an argument. The function also accept two function resolve() & reject().
- if the promise returns successfully, the resolve() function is called & if an  error occur, the reject() function is called. 

using a promise :- 

1. then() method : The then() method is used with the callback when the promise is sussessfully fulfilled or resolved.
2. catch() method : The catch() method is used with the callback when the promise is rejected or if an error occus. 
3. finally() method : the finally() method gets executed when the promise is either resolved successfully or rejected. 


Fetch API :- 

- API -> Application programming Interface (which is used to fetch the data)
- the fetch API provides an interface for fetching (sending / receiving) resources. 
- it uses Request and Response objects.
- The Fetch() is used to fetch a data.

syntax :- 
let promise = fetch(url, [option])

understanding some Terms :-

1. AJAX is a Asynchronous JS & XML
2. JSON is javascript Object Notation (AJAJ -> Asynchronous Javascript) & JSON
3. JSON() method : which is return a second promise that resolve with the result of parsing the response body text as json. (input is JSON & output is JS object)
