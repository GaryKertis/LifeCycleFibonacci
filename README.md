# To get started

```
npm install
npm start
```

# Requirements

- We have a cool app that calculates fibonacci numbers. But some numbers are slow to calculate! We want our users to have a better experience.
- While we are calculating these numbers, we should show them a spinner icon. The icon has already been created for you.
- Using the provided `Spinner` component and your knowledge of the react component lifecycle, let's make this better!

1. When the app first loads, the user should see the spinner icon UNTIL the number is done calculating. **(Fairly Easy)**
2. When the user clicks 'get new number', the user should see the spinner icon until the number is done calculating. **(Challenging!)**
3. It's easier to do this by putting the spinner icon inside of the `App` component. But there is also way to put the spinner icon inside the `Fibonacci` component... (hint: you may need to add state to Fibonacci and pass the number being calculated as a prop.) **(Very challenging!)**
