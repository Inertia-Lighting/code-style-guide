# Inertia Lighting | [Code Style Guide](../README.md) > Lua

## Code Style

### Indentation

We use 4 spaces for indentation.

Example:
```lua
function foo()
    return "bar"
end
```

### Quotation Marks

We use double quotes for strings.

Example:
```lua
local foo = "bar"
```

### Semi-colons

We don't use semi-colons in our lua.

### Trailing Commas

We use trailing commas in multi-line table literals.

Example:
```lua
local foo = {
    "bar",
}
local biff = { "buff" }
```

### Brace Style

We use braces on the same line as the method declaration.

Example:
```lua
local function someMethod(bar)
    return "bar"
end
```

### Naming Conventions

We use snake_case for variable names;  
camelCase for function / method names;  
and PascalCase for class names.

Example:
```lua
local Foo = {}
Foo.__index = Foo

local function Foo.new(bar)
    local self = {
        bar = bar,
    }
    return setmetatable(self, Foo)
end

local function Foo:outputBar()
    print(self.bar)
end

local foo = Foo.new("bar");
foo:outputBar();
```
