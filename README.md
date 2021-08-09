# Material-UI Demo Course

## Project Creation Steps

- [Initial Setup](#initial-setup)

### 1.) Initial Setup

    - Create a react app called material-ui-demo
    - Next delete the src folder as we won't be needing some files for the project
    - Add `index.js` and `App.jsx` files in there as we will be needing those
    - `Note: JS is standard javascript, JSX is an HTML-like syntax that you can use with React to (theoretically) make it easier and more intuitive to create React components. As the docs say, the only purpose is to make it easier to create React components... there's not much else there.`
    - Setup for `index.js` file

    ```javascript
    import React from "react";
    import ReactDOM from "react-dom";

    import App from "./App";

    ReactDOM.render(<App />, document.getElementById("root"));
    ```

    - Setup for `App.jsx` file

    ```javascript
    import React from "react";

    const App = () => {
        return (
        <div>
            <h1>Hello, world</h1>
        </div>
        );
    };

    export default App;
    ```

