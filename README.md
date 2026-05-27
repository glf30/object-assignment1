
## Instructions

In the `main.js` file, write the following functions:

### `createUser`

* Accepts two parameters, a user's first name and last name
* Returns a user objects

```
Example:

createUser('Jerron', 'Smith') => 
{
  firstName: 'Jerron',
  lastName: 'Smith'
}
```

### `setAge`

* Accepts two parameters, a user object and an age
* Adds a new `age` field to the user
* Returns the user object

```
Example:

const user = { 
    firstName: 'Tim',
    lastName: 'Horton'
};

setAge(user, 50) => 
{
    firstName: 'Tim',
    lastName: 'Horton',
    age: 50
}
```

### `incrementAge`

* Accepts a user object
* Increments the age field by one
* Returns the user object

```
Example:

const user = { 
    firstName: 'Angela',
    lastName: 'Merkel',
    age: 66
};

incrementAge(user) =>
{ 
    firstName: 'Angela',
    lastName: 'Merkel',
    age: 67
}
```

### `fixCar`

* Accepts a car object
* Sets the `needsMaintenance` field to `false`
* Returns the car object

```
Example

const car = {
    make: 'Ford',
    model: 'Mustang',
    year: 1969,
    needsMaintenance: true
};

fixCar(car) =>
{
    make: 'Ford',
    model: 'Mustang',
    year: 1969,
    needsMaintenance: false
}
```

### `addGrades`

* Accepts two parameters, a student object and an array of grades
* Adds each new grade to the student's `grades` array
* Returns the student object

```
Example

const student = {
    name: 'Chett Tiller',
    email: 'chett.teller@nobledesktop.com',
    grades: [80, 100, 95]
};

const newGrades = [88, 70, 90];

addGrades(student, newGrades) =>
{
    name: 'Brian McClain',
    email: 'brian.mcclain@codeimmersives.com',
    grades: [80, 100, 95, 88, 70, 90]
}
```

### `getDataType`

* Accepts two parameters, an object and a key in that object
* Returns the data type of the value at that key in the object (remember, typeof!)

```
Examples

const car = {
    make: 'Ford',
    model: 'Mustang',
    year: 1969,
    needsMaitenance: false
};

getDataType(car, 'make') => 'string'

getDataType(car, 'model') => 'string'

getDataType(car, 'year') => 'number'

getDataType(car, 'needsMaitenance') => 'boolean'

```

### `addTodo`

* Accepts two parameters, an array of to-do items and a new to-do item
* Adds the new-todo item to the array
* Returns the array of to-do items

```
Example

const todos = [
    { 
        title: 'Get gas', 
        isComplete: false },
    { 
        title: 'Buy bread', 
        isComplete: true  
    }
];

const newTodo = {
    title: 'Call mom', 
    isComplete: false
};

addTodo(todos, newTodo) =>
[
    { 
        title: 'Get gas', 
        isComplete: false 
    },
    { 
        title: 'Buy bread', 
        isComplete: true  
    },
    {
        title: 'Call mom', 
        isComplete: false
    }
];
```

### `addSong`

* Accepts two parameters, a playlist object and a song object
* Updates the duration of the playlist
* Adds the song to the playlist's `songs`
* Returns the playlist object

```
Example

const playlist = {
    title: 'My jams',
    duration: 7,
    songs: [
        {
            title: 'Of Dust and Nations',
            artist: 'Thrice',
            duration: 4
        },
        {
            title: 'Living Together',
            artist: 'Circa Survive',
            duration: 3
        }
    ]
};

const newSong = {
    title: 'Old Friends',
    artist: 'Pinegrove',
    duration: 3
};

addSong(playlist, song) =>
{
    title: 'My jams',
    duration: 10,
    songs: [
        {
            title: 'Of Dust and Nations',
            artist: 'Thrice',
            duration: 4
        },
        {
            title: 'Living Together',
            artist: 'Circa Survive',
            duration: 3
        }
        {
            title: 'Old Friends',
            artist: 'Pinegrove',
            duration: 3
        }
    ]
}
```

### `updateReportCard`

* Accepts two parameters, a report card and a new grade (a number between 0 and 100)
* Updates the report card's lowest grade, highest grade, and average grade
* Adds the new grade to the report card's grades

```
Examples

const reportCard = {
    lowestGrade: 70,
    highestGrade: 96,
    averageGrade: 82,
    grades: [70, 96, 80]
};

updateReportCard(reportCard, 62) =>
{
    lowestGrade: 62,
    highestGrade: 96,
    averageGrade: 77,
    grades: [70, 96, 80, 62]
}

updateReportCard(reportCard, 100) =>
{
    lowestGrade: 70,
    highestGrade: 100,
    averageGrade: 86.5,
    grades: [70, 96, 80, 100]
}
```
