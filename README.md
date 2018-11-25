# ts-snippets README
This extension will provide you with the most common language constructs for TypeScript and hopefully make you more productive.

## Features

- `ts-class`, creates a class including a constructor with 
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
```
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