# Map Filter Reduce

-   To Start this lecture please fork and clone this page

-   create two files inside the folder
    -   `reduce.js`
    -   `map_reduce`
-   inside of `reduce.js` please declare an array of numbers (at least 3) and another array of numbers as strings

-   declare a function called oldSchoolReduce that takes an array an sums the total of the items it contains

-   call oldSchoolReduce with the array of numbers in it

-   place this array inside of `map_reduce.js`

    ```
        javascript
        const animals = [
            { name: 'Fluffkins', species: 'rabbit' },
            { name: 'Caro', species: 'fish' },
            { name: 'Hamilton', species: 'cat' },
            { name: 'Spock', species: 'dogs' },
            { name: 'Harold', species: 'dogs' },
            { name: 'Ursula', species: 'fish' },
            { name: 'Jimmy', species: 'emu' }
         ]

    ```

-   then inside this file declare a funciton that takes an array/itterable and returns a new array of only the items where `species === 'dog'`

-   please read the documentation on MDN for Array.prototype.map(), Array.prototype.filter(), and Array.prototype.reduce()
