# React Form
An exemple of registration form in React with 4 labels: name, e-mail, password and phone number.

## Install
npx create-react-app form

## Download the code
https://github.com/IngridRadu/Form

## Quick Look
App Component
 ```
 import React from "react";
import Form from "./Components/FormControlled/Form";

const App = () => {
  return (
    <div className="container">
      <section className="form">
        <Form />
      </section>
      <section className="image">
        <img
          src={require("/Users/Lenovo/jsx/form/src/undraw_My_password_re_ydq7.png")}
          alt="woman showing empty input on a form"
        />
      </section>
    </div>
  );
};

export default App;
```



