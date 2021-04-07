## Use of De-structuring in React

The state and props in React are always in an object format. This means that the values via key-value pair.  Because of this, these objects can be deconstructed, using the techniques we learned in the previous lessons.

```
import React from "react";

class Row extends Component {
  this.state = {
    firstName: "Yoni",
    favoriteQoute: "Your time is limited, so don't waste it living someone else's life"
  };

  render() {
    const { firstName, favoriteQoute} = this.state; // <--- deconstructing the component's state.
    return (
      <div>
        <div>
          <span>First Name: {firstName}</span>
        </div>
        <div>
          <span>Last Name: {favoriteQoute}</span>
        </div>
      </div>
    );
  }
}
```

Explanation: This is an ordinary React component. It imports the react library, contains state and has the render function. The only difference is we are deconstructing the component's state.

### Instructions:
 Below is an empty React component. Use the component to practice destructing React state. 

1. Inside the state object, add two keys and corresponding properties.  

2. Directly under the render function, destructure the state object and assign it variables. 

3. In the first div, write the first variable. Remember to wrap the variables inside curly braces. 
   
4. In the second div, write the second variable. Remember to wrap the variables inside curly braces. 

```
import React from "react";

class Row extends Component {
    this.state = {

    }
 render(){
     <div className="container">
        <div className="first"> 
        
        </div>
        <div className="second"> 
        
        </div>
     </div>
 }
}
```

