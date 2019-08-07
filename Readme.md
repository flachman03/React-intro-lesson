React Intro Lesson

1. npx create-react-app
  a. What does this do?
  b. Why do we use this over setting up our own react application
  c. Have them download the react chrome devtools extension
2. Go through the Readme
  a. What does npm start do and how is it different from opening your javascript up on the actual DOM
3. Pull open the package.json
  a. Go through the dependancies that are installed with create-react-app
  b. Go through what scripts are set up with create-react-app
4. start the server
  a. This is the starting code you will see every time 
5. Open App.js
  a. Show that react/css is being imported
  b. App.js comes as a functional component be is usually always a class component so that it can hold state.
  c. Remove all code and replace with Hello World 
6. Show how to change a functional component into a class component
  a. Replace function with class and extends
  b. Ask what extends means and why that is important for a react class
  c. create the constructor
  d. See if anyone knows what the contructor should have if is an extension from another class
  e. add super and state to the contructor
  f. wrap the return in a render and explain why a class renders and a component only returns
    a. when a react class is called it automatically runs the render method. everything in a class must be a method.
7. Talk about fetch. what do they remember about fetching in vanilla.js.
8. Pull up pokeapi.co
9. Talk about api documentation and show them how to play with the fetch calls
10. Make a componentDidMount method and talk about how it runs after the component mounts/ some problems you may run into with this.
11. Make a fetch call to the poke api and console.log the results.
12. Talk about setting the state and how that is done when making a fetch call
13. Use the react devtools to show what is currently in state
14. It should be an object with key/value pairs with urls as the values
15. OH NO!!! Our data is trapped in another fetchCall! how dare they do this to us. 
16. You could make nested fetch calls to get at that information but instead just us the url/pokemon/1 to get bulbasaurs info
17. Replace Hello World with this.state.data.name
18. Add a console.log under the render to show how it renders first as an empty object
19. We don't want to have to manually create all the pokemon cards that we will be displaying right! 
20. Make a card container, ask whether or not they think the card container is going to need state.
21. Create a funtional CardContainer component step by step having the students walk you through its creation.
22. How do the student thnk we will bring in the CardContainer component into our app.js?
23. Import and set up the CardContainer Component
24. Use props to send the pokemon information down into the card component.
25. We will need one more component to make this all work. A Card component!
26. Will the Card component need state?
27. Walk through creating a card component
28. Import Card into CardContainer and pass down props into the Card component
29. Try to get the image to work and let it break. Take 5 min to see if anyone can figure out a way to get it to work
30. Explain conditional rendering as a solution to fix problems that can occur when rendering nested data
31. Add some css styling to the card
32. Now its time get get out next pokemon! Where are we going to put the function that will fetch us more information?
33. Does anyone have any ideas on how we might go about fetching another pokemon if this was at pokemon/1?
34. Work through setting up a function to fetch the next pokemon


