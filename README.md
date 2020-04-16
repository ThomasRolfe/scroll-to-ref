# Scroll To Ref

Basic helper function for scrolling to an element in a React application

Import the function and use as a handler

```
import ScrollToRef from "ScrollToRef";

const app = () => {
const myElement = React.createRef();

    return (
        <button onClick={() => {ScrollToRef(myElement)}}>
            Scroll to my element
        </button>


        <div ref={myElement}>
        </div>
    )

}
```

Accepts a second argument of yOffset. This is an optional pixel value to offset the scroll position.
