# Sweeft Digital Internship tasks 1 Node.js 2024

1. How to create constant variable?

- [x] const

- [ ] let

- [ ] constant

2. Which of the following statements are true?

- [x] Node.js is server-side technology

- [ ] Node.js is client-side technology

- [ ] None of them

3. What is npm?

- [x] node package manager

- [ ] node project manifest

- [ ] node project module

- [ ] node package manifest

4. What's the output?
> function getUserAge(...args) { console.log(typeof args); }
> getUserAge(33);

- [ ] number

- [x] object

- [ ] array

5. What's the output?
> function sayHi() {
> }
> return (() => 0)();
> 
> console.log(typeof sayHi());

- [x] number

- [ ] object

- [ ] function

6. What's the output?
> const set = new Set([1, 1, 2, 3, 4]);
> console.log(set);

- [x] {1, 2, 3, 4}

- [ ] {1, 1, 2, 3, 4)

- [ ] {4, 3, 2, 1}

- [ ] {2, 3, 4, 1)

7. What is the output?
> function hello(name) { return Hi there, ${name}'; }
> console.log(hello());

- [ ] Hi there,

- [x] Hi there, undefined

- [ ] Hi there, null

8. What will be the output of the following code?
> let a = 5;
> let output = (function() {
> return a;
> })();
> console.log(output);

- [ ] null

- [ ] undefined

- [x] 5

- [ ] NaN

9. What will be the output of the following code?
> let a = { foo: 5};
> let output = (function() {
> delete a.foo;
> return a.foo;
> })();
> console.log(output);

- [ ] 5

- [x] undefined

- [ ] NaN

- [ ] null

10. What will be the output of the following code?
> let text = "Hello world!";
> let result = text.slice(0, 5); console.log(result);

- [ ] ello

- [x] Hello

- [ ] world

- [ ] Hello World

11. What will be the output of the following code?
> let text1 = "my";
> let text2 = "car";
> let result = text1.concat(text2);
> console.log(result);

- [x] mycar

- [ ] car

- [ ] my

- [ ] carmy

12. Which method you can use to fetch data from a server

- [x] fetch()

- [ ] server()

- [ ] call()

- [ ] get()

13. Which method you can use to reverse array?

- [ ] arrayReverse()

- [x] reverse()

- [ ] getReverse()

- [ ] jsReverse()

14. Which method you can use to create new array?

- [x] .map()

- [ ] .createNew()

- [ ] .callNew()

- [ ] .mapNew()

15. Which method you can use to add new item at the end of an array?

- [ ] pull()

- [x] .push()

- [ ] join()

- [ ] .reverse()

16. What will be the output of the following code? 
> const countries = ["France", "Georgia", "Germany", "Italy"]; 
> console.log(countries.includes ("Italy"));

- [ ] Italy

- [ ] true

- [x] false

- [ ] 3

17. What will be the output of the following code?
> const countries ["France", "Georgia", "Germany", "Italy"]: console.log(countries.indexOf("Italy"));

- [ ] true

- [ ] false

- [x] 3

- [ ] Italy

18. What will be the output of the following code?

> const countries = ["Italy", "Germany", "Apple", "Mango"];
> const keys Object.keys(countries); console.log(keys);

- [x] ["0", "1", "2", "3"]

- [ ] 0, 1, 2, 3

- [ ] ["Italy", "Germany", "Apple", "Mango"];

- [ ] undefined

19. Which function is used to serialize an object into a JSON string in Javascript?

- [x] ~~Stringily~~ JSON.stringify() 

- [ ] Parse

- [ ] Convert

- [ ] serialize()

20. What keyword is used to declare an asynchronous function in Javascript?

- [x] ~~Async~~ async

- [ ] Await

- [ ] AyncFunction

- [ ] Sync
