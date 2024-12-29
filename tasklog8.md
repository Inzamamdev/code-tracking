# Counter Component

This commit introduces a simple counter component implemented using React's useState hook.  The component renders a button that increments a counter value on each click. The counter value is displayed on the button itself.

**Previous Code (test.js):**
The previous code (`test.js`) is unrelated and not relevant to this change. It was a simple component rendering "test New".

**Current Code (Counter.js):**
```javascript
import React from "react";
import { useState } from "react";
export default function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <button onClick={() => setCount(count + 1)}>{count}</button>
    </div>
  );
}
```