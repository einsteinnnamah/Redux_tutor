# Redux_tutor
This repo teaches you the foundations of redux (no exprience required)

Three concepts in Redux <br />
<br />
Store= Holds the state of your app <br />
<br />
Action = Describes what happen <br />
<br />
Reducer = Ties the store and actions together (call it the binder😒) <br />

Also you will come accross something that is called action creator( a function that returns an object (i.e an action🙌) ) <br />

Three principes of Redux <br />
<br />
First= The global state of the app is stored in an object inside a single store <br />
<br />
Second = The only way to change the state is to dispatch an action, i.e an object that describes what happened <br />
<br />
Third = To specify how the state tree is updated based on actions, you write pure reducers (pure reducers are pure functions that take in a state and action and return a new state) <br />
