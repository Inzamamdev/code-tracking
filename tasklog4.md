# Counter Component

This commit introduces a simple counter component implemented using React's functional component and useState hook. The component renders a button that increments a counter value upon each click.  The counter value is displayed on the button itself.

**Previous Code (Irrelevant):** The previous code (`test.js`) is unrelated and does not need to be referenced here.

**Current Code:**
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