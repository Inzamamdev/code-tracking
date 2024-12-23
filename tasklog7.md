import React, { useState } from "react";

export default function Login() {
  const [counter, setCounter] = useState(0);

  return (
    <div>
      <h1>{counter}</h1>
      <button onClick={() => setCounter(counter + 1)}>Increment</button>
      <div>Hello</div>
    </div>
  );
}
