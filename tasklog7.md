# Login Counter Component

This commit introduces a simple login counter component using React's useState hook.  The component renders a button that increments a counter each time it's clicked, displaying the current count on the button itself. This is a new component, unrelated to the previous `test` component.

**Code:**

```jsx
import React from "react";
import { useState } from "react";
export default function Login() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <button onClick={() => setCount(count + 1)}>{count}</button>
    </div>
  );
}
```