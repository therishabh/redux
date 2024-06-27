# Redux
Redux is a predictable state container for javascript apps.
<br/>
Manage the state of your application in a predictable way, redux can help you.

#### Three Core Concepts:
- A store that holds the state of your application.
- An action that describes the changes in the state of the application.
- A reducer which actually carries out the state transition depending on the action.

### Three Principles
**First Principle**
"The state of your whole application is stored in an object tree within a single store"<br/>
Maintain our application state in a single object which would be managed by the Redux store<br/>
<br/>

**Second Principle**
"The only way to change the state is to emit an action, an object describing what happened" <br/>
To update the state of your app, you need to let Redux know about that with an action Not allowed to directly update the state object<br/>
<br/>

**Third Principle**
"To specify how the state tree is transformed by actions, you write pure reducers" <br/>
Reducer - (previousState, action) => newstate<br/>
<br/>

<img width="939" alt="Screenshot 2024-06-27 at 4 43 59 PM" src="https://github.com/therishabh/redux/assets/7955435/1b9e7370-e246-4822-aafe-5d30b495ff6a">

### Actions
The only way your application can interact with the store Carry some information from your app to the redux store<br/>
Plain JavaScript objects<br/>
Have a 'type' property that indicates the type of action being performed<br/>
The 'type' property is typically defined as string constants<br/>
Action is a object with a type property and an action creator is a function that returns an action.<br/>
<br/>

### Reducers
Specify how the app's state changes in response to actions sent to the store <br/>
Function that accepts state and action as arguments, and returns the next state of the application<br/>
(previousState, action) => newState<br/>
<br/>


