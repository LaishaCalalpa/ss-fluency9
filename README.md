# Directions
Today is going to consist of both JavaScript and Python! We'll start with JavaScript high order functions for the first half.
You'll be fetching data from the JSONPlaceholder API [https://jsonplaceholder.typicode.com/] and manipulating that data according to the directions, using the appropriate high order functions. Then we'll do the same functions in Python, with list comprehensions! We'll talk about the code to fetch data in Python when the time comes. **Don't forget that forEach exists, and you should be using it over for loops! If you want, you also have the option to use find() - look at the documentation to see what it can do!**


1. Write a function, `sentenceMaker`, that returns an array of users, formatted as follows: '(name) lives in (address). They work
in (company), and you can reach him by emailing them at (email).'

2. Write a function, `livesInApt`, that returns an array of objects of users. Each property should be the name of the user, and its value should be a boolean, true if they live in an apartment and false if they do not. Here's an example:
```
[{Martha: true}, {Peter: false}, {Sasha: false}, {...}]
```

3. Write a function, `companySlogan`, that returns an array of objects of companies. Each property should be the company name, and its value should be that company's slogan. If the company doesn't have a slogan, give it a value of your choosing!
```
[{Johnson's: 'A family company'}, {McDonald's: 'I'm lovin' it}, {Tungsten's Shop: 'Sorry, no slogan here!'}, {...}]
```

4. Write a function, `whatDoYouDo`, that returns an object of users with an explanation of their work. Each property should be
the name of the person, and its value should be formatted as such: 'Hi! I work at (company), where we (description of job).'

5. Write a function, `findByID`, that takes in a number ID and returns a todo object based on its ID.

6. Write a functon, `completed`, that returns an array of objects that finds the todos that have been completed. The completed
tasks should be the only ones in that array!

7. Write a function, `pleaseComplete`, that returns a string with an array of task names on it. It should be formatted as follows:
```
Hey, you still have (number of incomplete tasks) tasks left to do. Complete the following: [(task title), (task title), (...)]
```

8. Write a function, `findUserIDPosts`, that takes in a user ID and returns an array of that user's posts.

9. Write a function, `hasEst`, that checks if some of the posts that have the word 'est' in them and return true or false.

10. Write a function, `bodyLength`, that returns an array of all the lengths of the comment bodies only if the title is longer
than 20 characters. 

## Python

Take a look at this article here [https://code.tutsplus.com/articles/how-to-use-restful-web-apis-in-python--cms-29493] for more
information about Python fetching. Only read the GET request portion! When you're fininshed, we'll try it together and do the 
same functions!
