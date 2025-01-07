# Counter Component

This commit introduces a simple counter component built using React's useState hook.  The component renders a button; each click increments an internal counter state variable.  There's no visual feedback of the counter's value, only the button itself.

**Previous Code (Test Component):** The previous code simply rendered a div with the text 'Test'. This is unrelated to the current commit and serves as a reference to previous commit.

**Current Code:**
```javascript
import { useState } from "react";

export default function Counter() {
  const [count, setCount] = useState(0);

  return <button onClick={() => setCount(count + 1)}></button>;
}
```