# Inertia Lighting | Code Style Guide | Lua

## Code Style

### Indentation
We use 4 spaces for indentation.  
Example:
```lua
function foo()
    return 'bar'
end
```

### Quotation Marks
We use single quotes for strings.  
Example:
```lua
local foo = 'bar'
```

### Semi-colons
We don't use semi-colons in our lua.

### Trailing Commas
We use trailing commas in multi-line table literals.  
Example:
```lua
local foo = {
    'bar',
}
local bar = { 'baz' }
```

### Naming Conventions
We use snake_case for variable names;  
camelCase for function / method names;  
and PascalCase for class names.  
Example:
```lua
local Foo = {}
Foo.__index = Foo

function Foo.new(bar)
    local self = {
        bar = bar,
    }
    return setmetatable(self, Foo)
end

function Foo:outputBar()
    print(self.bar)
end

local foo = Foo.new('bar');
foo.outputBar();
```
