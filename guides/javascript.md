# Inertia Lighting | Code Style Guide | JavaScript

## Code Style

### Indentation
We use 4 spaces for indentation.  
Example:
```js
function foo() {
    return 'bar';
}
```

### Quotation Marks
We use single quotes for strings and graves for template literals.  
Example:
```js
const foo = 'bar';
const bar = `${foo}`;
```

### Semi-colons
We use semi-colons in our javascript.  
Example:
```js
doSomething();
doSomethingElse();
```

### Trailing Commas
We use trailing commas in multi-line array / object literals.  
Example:
```js
const foo = [
    'bar',
];
const bar = [ 'baz' ];
```

### Naming Conventions
We use snake_case for variable names;  
camelCase for function / method names;  
and PascalCase for class names.  
Example:
```js
class Foo {
    constructor(bar) {
        this.bar = bar;
    }

    outputBar() {
        console.log(this.bar);
    }
}

const foo = new Foo('bar');
foo.outputBar();
```
