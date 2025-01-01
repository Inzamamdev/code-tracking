# Test Component with Counter

This commit introduces a simple counter to the `Test` component.  The counter is implemented using React's `useState` hook.  The component renders a button that increments the counter on each click and displays the current counter value.

**Previous Code:**
The previous code was identical to the current code.

**Current Code:**
```javascript
import { useState } from "react";
export default function Test() {
  const [counter, SetCounter] = useState(0);

  return (
    <div>
      <h1>Test</h1>
      <button onClick={() => SetCounter(counter + 1)}>Click me</button>
      <h1>{counter}</h1>
    </div>
  );
}
```