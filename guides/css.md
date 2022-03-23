# Inertia Lighting | [Code Style Guide](../README.md) > CSS

## Code Style

### Indentation

We use 4 spaces for indentation.

Example:
```css
.thing {
    --property: 'value';
}
```

### Quotation Marks

We use single quotes for strings, values, and attributes.

Example:
```css
.foo {
    font-family: 'Open Sans';
}
```

### Brace Style

We use braces on the same line as the selector declaration.

Example:
```css
.foo {
    --property: 'value';
}
```

### Naming Conventions

We use snake_case for ids;  
and kebab-case for tags, attributes, and classes.

Example:
```css
#foo_bar {
    --property: 'value';
}
.foo-bar {
    --property: 'value';
}
my-thing[data-cool-stuff='enabled'] {
    --property: 'value';
}
```
