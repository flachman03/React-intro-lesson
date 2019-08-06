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
  


