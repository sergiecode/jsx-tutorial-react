![JSX en React](https://github.com/sergiecode/jsx-tutorial-react/blob/master/01.jpg?raw=true)
![JSX en react](https://github.com/sergiecode/jsx-tutorial-react/blob/master/02.jpg?raw=true)
![JSX en react](https://github.com/sergiecode/jsx-tutorial-react/blob/master/03.jpg?raw=true)

# JSX en React.js

## ¿Qué es JSX?

JSX (JavaScript XML) es una extensión de sintaxis utilizada en React.js para definir componentes de interfaz de usuario. En lugar de escribir elementos HTML directamente en el código, JSX permite combinar HTML y JavaScript de una manera declarativa y más intuitiva.

## ¿Cómo se usa JSX en React.js?

A continuación se muestra un ejemplo de cómo se utiliza JSX en React.js:
```
    // En lugar de escribir elementos HTML en su código, puede usar JSX para definir componentes de React. Por ejemplo, en lugar de escribir:
    
    const element = document.createElement("div");
    element.innerText = "Hello, world!";
    
    // Con JSX, puedes escribir:
    
    const element = <div>Hello, world!</div>;
```

La sintaxis de JSX es similar a HTML, lo que facilita la creación de elementos de interfaz de usuario. Sin embargo, JSX también permite el uso de expresiones de JavaScript dentro de llaves {}. Por ejemplo:
```
    const user = "Sergie Code";
    const element = <div>Hello, {user}!</div>;
```
En este caso, la variable `user` se interpola dentro del componente JSX, lo que permite mostrar contenido dinámico.

JSX facilita la creación y manipulación de componentes de React de manera más intuitiva y legible. Al utilizar JSX, puedes aprovechar todas las capacidades de JavaScript para crear interfaces de usuario interactivas y personalizadas.
