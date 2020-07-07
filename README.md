# ts-snippets README

This extension will provide you with the most common language constructs for TypeScript and hopefully make you more productive.

## Features

- `ts-class`, creates a class including a constructor with
- `ts-class-inherit`, creates a class `Shape` and a class `Movable`. `Movable` inherits from `Shape`
- `ts-class-constructor`, creates the constructor part, you fill in the parameter names, just tab between
- `ts-class-getter`, creates a getter for a property, it also creates the backing field
- `ts-class-setter`, creates a setter for a property, it also creates the backing field
- `ts-class-setter-getter`, create a setter and a getter and the backing field
- `ts-int`, creates an interface,
- `ts-int-impl`, creates an interface and class that implements the interface
- `ts-templ`, creates a template string example
- `ts-tuple`, creates a tuple example
- `ts-enum`, creates an enum example
- `ts-func`, creates a function signature as a type and assigns a function to it
- `ts-func-arrow`, creates a function signature as a type and assigns an `arrow` function to it
- `ts-union`, creates a union type and an example using it
- `ts-intersect`, creates an intersection type and a mixin function that extends your type
- `ts-decorator`, creates a decorator example
  with this one you want to create a `tsconfig.json` with the following content:

```json
{
  "compilerOptions": {
      "target": "ES5",
      "experimentalDecorators": true,
      "outFile": "app.js"
  }
}
```

and then compile it with `tsc` and serve up in either browser or terminal

## Release Notes

Let me know what features you want either on [Issues](https://github.com/softchris/ts-snippets/issues) or Twitter [Chris Noring - Twitter](https://twitter.com/chris_noring)

### 1.1.0

Added snippets for `constructor` and getters and setters

### 1.0.0

changed name to `TypeScript Snippets`. It's also pretty much feature complete.

### 0.0.5

added repository and icon

### 0.0.4

minor corrections

### 0.0.3

Adding union type, intersection type and decorator

### 0.0.2

Adding a bunch of Typescript constructs to make this extension usable

### 0.0.1

Initial release of of our extension. This gave us the `ts-class` command.

**Enjoy**

Chris Noring
[@chris_noring](https://twitter.com/chris_noring)
