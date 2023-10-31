#React Counter Exercise#

Objective: 
Create a simple counter application in React. The application will have a button to increment a counter and display the current count.

Instructions:
Single Component Counter
Start by creating a new React application.
Within the App component, initialize the state with a count property set to 0.
Render a button with the label "Increment".
When the button is clicked, the count state should increase by 1.
Display the current count value on the screen.

Splitting into Sub-components

Refactor your application to have three components: App, CounterButton, and CounterDisplay.

App Component:
This will be your main container component.
Initialize the state with a count property set to 0.
Pass down the necessary state and functions as props to the child components.

CounterButton Component:
This component will only render the "Increment" button.
When the button is clicked, it should notify the App component to increase the count.
CounterDisplay Component:
This component will be responsible for displaying the current count value.
It will receive the count value as a prop from the App component and display it.

Bonus:
Add a "Decrement" button to decrease the count.
Ensure the count never goes below 0.




