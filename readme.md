Todos For Frontend job interview
================================

## Internet

### Browser

### HTTP network

## JavaScript

### ES6 features
 **Promise**  
- 비동기 작업의 상태 및 결과값을 나타내기 위한 객체
- 인스턴스 생성 시 콜백함수를 전달하며 해당 콜백 함수 내에서 인자로 전달된 resolve, reject함수를 각각 비동기 작업의 완료, 실패 시 실행해줌.
- resolve함수의 인자로 완료시 리턴할 값을 정해줄 수 있으며, reject의 인자로 에러를 전달
- then메서드를 통해서 작업 완료 시의 함수를 콜백으로 전달해줄 수 있음
- then메서드로 또 다른 promise반환이 가능하며 이는 then chaining을 가능케함
- catch메서드를 통해 에러를 캐치할 수 있음
  
**async/await**
- 비동기 코드를 동기코드와 유사하게 작성가능
- function 키워드 앞에 async키워드를 삽입하면 해당 함수는 비동기적으로 실행할 수 있음
- 비동기 작업 앞에 await키워드를 입력하면 해당 promise가 fulfill될 때까지 코드 진행을 멈출 수 있음
- try catch 블락을 통해 에러 핸들링
- 글로벌 스코프에서는 await키워드 사용 불가능

**iterator**
- ES6에서 추가된 *iterator protocol*을 따르는 객체  
- next메서드를 가지며 메서드 호출 시 리턴되는 객체는 최소한 done, value 2가지 property를 가져야 함
- done은 iterator가 next value를 생산할 수 있으면 false.
- iterator가 모든 sequence를 끝냈을 때 true
- 
**generator**  

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


