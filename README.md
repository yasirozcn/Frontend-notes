Q1 - What is JSX?
A1- JSX stands for JavaScript XML and it is an XML-like syntax extension to ECMAScript. Basically it just provides the syntactic sugar for the React.createElement(type, props, ...children) function, giving us expressiveness of JavaScript along with HTML like template syntax.

In the example below, the text inside <h1> tag is returned as JavaScript function to the render function.

```jsx
render() {
  return <h1>Hello, world!</h1>;
}
```

- JSX is not a string or HTML. It is a syntax extension to JavaScript.
- JSX code gets compiled into JavaScript code.
- JSX makes the code more readable and easier to understand.
- JSX is a syntax extension to JavaScript.
