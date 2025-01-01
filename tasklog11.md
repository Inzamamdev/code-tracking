# Counter Component

This commit introduces a simple counter component implemented using React's `useState` hook. 

The component renders:

* A heading with the text "Test".
* A button that increments a counter value on each click.
* A heading displaying the current value of the counter.

The counter state is initialized to 0 using `useState(0)`. The button's `onClick` handler calls `SetCounter` to update the counter state, incrementing it by 1.

```jsx
import { useState } from "react";
export default function Counter() {
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

There is no change in the functionality from the previous code