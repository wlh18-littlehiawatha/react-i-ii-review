### Remember

Answer these on your own, then compare answers as a group

1.  What is React?
      React is a javascript library that also pushes the border of a framwork.
      a javascript library that can be used to build user interfaces???

2.  What is create-react-app?
      a ________ that generates the boiler plate for a basic react _______


3.  What is Component Based Architecture?
      a plug and play sytem that allows for the easy reutilization of code blocks

4.  What is JSX?
      javascript that allows elements of html to be coded inside

5.  What is the virtual DOM?
      it is a virtual representation of the document object module that stands in between what is shown on your screen and the code. it looks for changes and then allows for just that component to be rerendered. This improves overall responsiveness and efficiency. 

      light weight copy of the dom  that listens for changes

6.  What is unidirectional (one-way) data flow?
      a concept whereby data flows in only one direction. In the case of React, data only flows down to the lowest most child and events are based back up.

      
### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop?

9.  Explain what this code does:

```jsx
import React from "react";

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

10.  Explain how data is passed from a parent component to a child component.

### Apply

Try these on your own, but work together if you start to get stuck.

11.  Use `create-react-app` to create a new React application called `student-directory`

12.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

13. What are the benefits and drawbacks of using a tool like create-react-app?

14. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

15. Compare and contrast one-way data flow with two-way data binding.
