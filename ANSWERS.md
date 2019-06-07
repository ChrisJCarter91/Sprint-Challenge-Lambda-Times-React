- [ ] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

PropTypes tell us what type of data a React component requires in order to render properly. Example, we can set a proptype to a 'string' so someone doesn't try to pass an array in.

- [ ] Describe a life-cycle event in React?

The 3 phases in a React Component's lifecycle are mounting, updating, and unmounting, and this is the order React renders.

The mounting phase is where the component is built from the ground up. Render method is invoked. componentWillMount is this phase, followed by componentDidMount.

- [ ] Explain the details of a Higher Order Component?

HOC's hurt my brain, but are essentially higher order functions that take in a component and returns a component Source. This allows shared functionality between components. We used this for a login component. 

- [ ] What are three different ways to style components in React? Explain some of the benefits of each.

Libraries like React/ReactStrap - quick and easy but uses a lot of !important elements

styled-components - keeps styling on 1 page and allows writing css on js page, but gets cluttered like combining a js and CSS page. 

Importing styles like tailwind css. 
