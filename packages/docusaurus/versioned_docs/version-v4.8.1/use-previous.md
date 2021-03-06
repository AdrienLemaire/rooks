---
id: use-previous
title: use-previous
sidebar_label: use-previous
---

   

## About

Access the previous value of a variable with this React hook
<br/>

## Installation

    npm install --save @rooks/use-previous

## Importing the hook

```javascript
import usePrevious from "@rooks/use-previous";
```

## Usage

```jsx
function Demo() {
  const myInput = useInput("hello world");
  const previousValue = usePrevious(myInput.value);
  return (
    <div>
      <div>
        <input {...myInput} />
      </div>
      <p>
        Current value is <b>{myInput.value}</b>
      </p>
      <p>
        Previous value was <b>{previousValue || "-"}</b>
      </p>
    </div>
  );
}

render(<Demo />);
```

## Arguments

| Argument | Type | Description                                        |
| -------- | ---- | -------------------------------------------------- |
| value    | any  | The variable whose previous value should be stored |

## Gif

[![Image from Gyazo](https://i.gyazo.com/9913f58e1959ed60fb590cb280639d88.gif)](https://gyazo.com/9913f58e1959ed60fb590cb280639d88)


## Join Bhargav's discord server
You can click on the floating discord icon at the bottom right of the screen and talk to us in our server.

    