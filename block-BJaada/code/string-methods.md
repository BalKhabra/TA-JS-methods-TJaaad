Watch this video to understand what to do in this exercise block [link](https://www.youtube.com/watch?v=zGpplZj4zY0&feature=youtu.be)

#### Getting To Know String Methods

Go to this [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) and look for the name of method to learn about it.

**Write in your own way of understanding (don't copy paste)**

Only if you are done with step 1 you should go ahead.

1. Practice it by yourself in console (4-5 times to understand)
2. Data types of parameters
3. Return value type
4. Write three examples
5. In your own words and one sentence explain what this method does.

Example:

1. `charAt`

   - Parameter: (index) defaults to 0 - (number data type)
   - Return: character at specific index in the string (string data type)
   - Example:
     ```js
     let name = 'Arya Stark';
     name.charAt(2); //"y"
     let sentance = 'A quick brown fox jumped over a lazy dog';
     sentance(4); // "i"
     let houseName = 'Starks';
     houseName.charAt(0); // "S"
     ```
   - `charAt` accepts a index (number data type) and return the character on that index in the string.

2. `toUpperCase`

  Parameter: () - (string data type)
  Return: Uppercase transform for characters (string data type)
  ```js
  let sentence = 'my name is Baljit'
  console.log(sentence.toUpperCase());
  ```

3. `toLowerCase`
  Parameter: (string data type)
  Return: Lowercase transform for characters (string data type)
  ```js
  let sentence = 'my name is Baljit'
  console.log(sentence.toLowerCase());
  ```
4. `trim`

  Parameter: (string data type)
  Return: Trims any space that surrpunds the string value 
  ```js
  let sentence = '    My name is Baljit    '
  console.log(sentence.trim());
  ```
5. `trimEnd`

  Parameter: (string data type)
  Return: Trims any space at the end of the string value 
  ```js
  let sentence = 'My name is Baljit    '
  console.log(sentence.trimEnd());
  ```

6. `trimStart`
  Parameter: (string data type)
  Return: Trims any space at the start of the string value 
  ```js
  let sentence = '    My name is Baljit'
  console.log(sentence.trimStart());
  ```

7. `concat`
  Parameter: (string data type)
  Return: Concatenates the argument and returns a string
  ```js
  let str1 = 'My name is'
  let str2 = 'Baljit'
  console.log(sentence.concat('', str2));
  ```
8. `endsWith`

  Parameter: Returns a true or false value depending on what character the strings ends with.(string data type)
  Return: 
  ```js
  let sentence = 'My name is Baljit    '
  console.log(sentence.endsWith('Baljit', 17));
  ```

9. `includes`
  Parameter: Finds matching strings in another string\
  Return: True or false based on results
  ```js
  let sentence = 'My name is Baljit'
  let word = 'Baljit'
  console.log(`The word "${word}" ${sentence.includes(word) ? 'is' : 'is not'} in the sentence`);
  ```
10. `indexOf`
  Parameter: Uses two arguments, one to searched string then returns first index of specified string; second returns first index of greater or equal to specified number
  Return: The found specified string value
  ```js
  let sentence = 'My name is Baljit'
  let word = 'Baljit'
  console.log(`The word "${word}" ${sentence.indexOf(word) ? 'is' : 'is not'} in the sentence`);
  ```
11. `lastIndexOf`
  Parameter: Uses two arguments, one to search string then returns last index of specified string; second returns last index of greater or equal to specified number
  Return: The found specified string value
  ```js
  let sentence = 'My name is Baljit'
  let word = 'Baljit'
  console.log(`The word "${word}" ${sentence.indexOf(word) ? 'is' : 'is not'} in the sentence`);
  ```
12. `padEnd`
  Parameter: pads the string with given string to reach a specific string length
  Return: The specified length and string value at end
  ```js
  let sentence = 'My name is Baljit'
  console.log(sentence.padEnd(25, '.'));
  ```
13. `padStart`
  Parameter: pads the string with given string to reach a specific string length
  Return: The specified length and string value at start
  ```js
  let sentence = 'My name is Baljit'
  console.log(sentence.padStart(25, '.'));
  ```
14. `repeat`
  Parameter: makes a specific number of copies as specified by string
  Return: Copies or repeats certain amount
  ```js
  let sentence = 'My name is Baljit'
  console.log(`My name is "Baljit" : ${sentence.repeat(3)}`);
  ```
15. `replace`
  Parameter: replaces with the given strong value
  Return: returns the new string value
  ```js
  let sentence = 'My name is Baljit'
  console.log(sentence.replace('Baljit', 'Ben'));
  ```
16. `slice`
  Parameter: removes a section of the strong
  Return: extracts and returns new string without chanigng original
  ```js
  let sentence = 'My name is Baljit'
  console.log(sentence.slice(25));
  ```
17. `split`

    Parameter:
    seperator - optional - (string data type)
    limit - optional - (number data type)
    return - an array of strings

    Example:
    ```js
    let username = "John Snow";
    username.split('');
    username.split('o');
    username.split('o', 4);
    username.split('', 4);
    ```
    Split accepts two optional parameter seperator and limits and returns array of strings

18. `substring`
  Parameter: (string data type)
  Return: part of string between beginning and end 
  ```js
  let sentence = 'My name is Baljit'
  console.log(sentence.substring(25, '.'));
  ```