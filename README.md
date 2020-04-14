
## lab5:
## lab6:
## lab7:https://repl.it/@RazanAlQuran/301-CC07-map
## LAB8:https://repl.it/@RazanAlQuran/301-CC08-filter

## LAB9:https://repl.it/@RazanAlQuran/301-CC09-reduce
people = [
    {name: 'Mary', gender: 'girl'},
    {name: 'Paul', gender: 'boy'},
    {name: 'John', gender: 'boy'},
    {name: 'Lisa', gender: 'girl'},
    {name: 'Bill', gender: 'boy'},
    {name: 'Maklatura', gender: 'girl'}
]

var numBoys = people.reduce(function(n, person) {
    return n + (person.gender == 'boy');
}, 0);

console.log(numBoys);// its will return the number of the boy in this people array
result is :: //3

## LAB9:https://repl.it/@RazanAlQuran/301-CC09-reduce

