# Notas de Aula

[Curso JavaScript Udemy](https://www.udemy.com/the-complete-javascript-course/)


# Seção 1

##Introdução

## Seção 2

console.log( x1,x2,..., xn)
### Variables

- var

### Data Types

- string
- float
- boolean
- undefined
- null

### Variable Mutation and Type Coercion



### Basic Operations

-typeof

### Operator Precedent

[Tabela Precedentes](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)

x = x *2;
x *= 2;
x = x + 4;
x += 4;
X = X + 1;
x++

### If / Else Statements

if ( <condition>) {
    <true>;
} else [If] {
    <false>;
} else [if] { 

}

### Boolean Operators

AND (&&) => true if ALL are true
OR (||)  => true if ONE is true
NOT (!)  => inverts true/false


### Ternary Operators and Switch Statements

? => then 
: => else
age >= 18 ? console.log(firstName + 'drinks beer.') : console.log(firstName + 'drink Jucie.');

**Write var**
var drink = age >= 18 ? 'beer' : 'juice';

### Switch Statement

switch(job) {
    case 'teacher' :
        console.log(firstName + 'teaches kids how to code.');
        break;
    case 'driver' :
        console.log(firstName + 'drives an ubber in Lisbon.');
        break;
    case 'designer' :
        console.log(firstName + 'designe beautiful things.');
        break;
    default :
        console.log(firstName + 'does something else.');
}


age = 1
switch(true) {
    case age< 13: 
        console.log( 'is a boy.');
        break;
    case age >=13 & age <20: 
        console.log( 'is a teenager.');
    break;
    case age >=20 & age <30:
        console.log('is a young man.');
        break;
    default:
    console.log('is a man.');
}

### Truthy and Falsy Values and Equality Operators

Falsy: undefined, null, o, '', NaN

Truthy values: NOT falsy values

var height;

if (heigth){
    console.log('Variable is defined');
} else {
    console.log('Variable has NOT been defined');
}

**if not defined is false else true (not falsy)**

