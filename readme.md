Todos For Frontend job interview
================================

## Internet

### Browser

### HTTP network

## JavaScript

### ES6 features
- Promise
  > 
- async/await
- iterator
- generator

### Execution Context

- **Global Execution Context**: Default execution context. The code that is not inside any function is in the global execution context. It creates a global object which is a window object and sets the value of `this` to equal to the global object. There can only be one global execution context in a program.
- **Functional Execution Context**: Every time a function is invoked, a brand new execution context is created for that function. Each function has its own execution context, but it's created when the function is invoked or called.
- **Execution context looks like this**:  

    | key                 | value                                       |
    | ------------------- | ------------------------------------------- |
    | **Variable object** | {vars, function declarations, arguments...} |
    | **Scope chain**     | [Variable object + all parent scopes]       |
    | **this value**      | Context object                              |

    **Variable object**: Contains variables, parameters, arguments, function declarations
    **

### Event Loop

### Event Delegation

## React

### React Life cycles

### Class component vs Functional component

### React hooks

### Redux

## Design Patterns

### Flux pattern

### MVC pattern

## HTML, CSS

### CSS Precedence

1. !important after CSS properties.
2. Specificity of CSS rule selectors.
3. Sequence of declaration.

### CSS Specificity

1. CSS properties set on element(with style attribute).
2. Combined selectors
3. ID
4. Class
5. Attribute
6. Element
7. *(any)
8. Inherited styles

### Flex box


