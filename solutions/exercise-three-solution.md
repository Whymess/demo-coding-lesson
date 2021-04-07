
1. Inside the state object, add two keys and corresponding properties.  

2. Directly under the render function, destructure the state object and assign it variables. 

3. In the first div, write the first variable. Remember to wrap the variables inside curly braces. 
   
4. In the second div, write the second variable. Remember to wrap the variables inside curly braces. 

```
import React from "react";

class Row extends Component {
    this.state = {
        firstName: "Jonathan",
        lastName: "messing"
    }
 render(){
     let {firstName, lastName} = this.state
     <div className="container">
        <div className="first"> 
                {firstName}
        </div>
        <div className="second"> 
                  {lastName}
        </div>
     </div>
 }
}