# Javascript-exercises-beginners
![Alt javascript](http://www.purelogics.net/blog/wp-content/uploads/2019/01/javascript.png)
This a repository for JavaScript questions to get you comfortable answering interview questions for junior role
___
## Task 1
Implement a **pangram** check function.
### Definition:
  A **pangram** or holoalphabetic sentence is a sentence using every letter of a given alphabet at least once.[Read more](https://en.wikipedia.org/wiki/Pangram)  
  
  example: _"The quick brown fox jumps over the lazy dog"_

```javascript
  console.log(isPangram("The quick brown fox jumps over the lazy dog")) // true
  console.log(isPangram("This sentence is not a pangram")) // false
```
### Hints:
1. Spaces and Capitalisation in the sentences
2. ```.split() .join() .sort() .toLowerCase()```
3. ```const alphabet= 'abcdefghijklmnopqrstuvwxyz'```

## Task 2
Implement a **palindrom** check function 
### Definition:
A **palindrom** is a word, number, phrase, or other sequence of characters which reads the same backward as forward [Read more](https://en.wikipedia.org/w/index.php?search=Palindrome&title=Special:Search&profile=advanced&fulltext=1&ns0=1)

  example: __madam__ or __racecar__
  
  ```JavaScript
    console.log(isPalindrome("racecar") //true
    console.log(isPalindrome("avocado") //false
   ```

   ### Hints
   1. This can be a single word or a sentence, they may contain capital letters and lowercases
   2. ``` .split() .reverse() .toLowerCase()```

## Task 3
** for loop** comprehension
This is to test your understanding of for loop
```javascript 
  //Given array numbers =[1,2,3,4,5,6,7,8,9]
  //Using only for loop print number from the last number to the first in the array
  //Should print this in the console 9 8 7 6 5 4 3 2 1
```
## Task 4
### High order functions
using **every** check if evry person in the array is over age( 18 and above) or use **some** to check if the array contains anyone under age

using **filter** go through the array of random people and return people whose age is over 18 only and store them in a __const__ variable **overAge**

using **map** change every person.drinks property in **overAge** to true and console log to check your answer

using **findIndex** return the index of the oldest person and their name and age

 using **reduce** Calculate the average age of the array elements
 
 using **forEach** print everyone's name and city they are from
 
```javascript
  let people=[
    {
        name: "Didier",
        age: 26,
        city: "Sydney",
        drinks: false
    },
    {
        name: "Hermes",
        age: 27,
        city: "Napoli",
        drinks: false
    },
    {
        name: "Abi",
        age: 30,
        city: "Orange",
        drinks: false
    
    },
    {
        name: "Mathis",
        age:5,
        city: "Los Angeles",
        drinks: false
    },
    {
        name: "kai",
        age: 17,
        city: "Atlantis",
        drinks: false
    },
    {
        name: "Jack",
        age: 40,
        city: "Liverpool",
        drinks: false
    }
]
```
###### to be continued, I will keep updating this reo for better and more challenging questions

# everyone is welcome to contribute
