# Redux_tutor
This repo teaches you the foundations of redux (no exprience required)
Also you need to understand the foundations of react js for this course


Three concepts in Redux 
Store= Holds the state of your app
Action = Describes what happen
Reducer = Ties the store and actions together (call it the binder)

Also you will come accross something that is called action creator( a function that returns an object (i.e an action) )

Three principes of Redux
First= The global state of the app is stored in an object inside a single store
Second = The only way to change the state is to dispatch an action, i.e an object that describes what happened
Third = To specify how the state tree is updated based on actions, you write pure reducers (pure reducers are pure functions that take in a state and action and return a new state)
