# In your own words, explain React's Virtual DOM. What gives React its fast performance?
> React's virtual DOM is a rendered representation of the DOM, a lightweight copy of it. It does not have the DOM's ability to change what's on the screen directly, but has the same properties of the real DOM. Nothing gets drawn on screen with the Virtual DOM, thus making virtual DOM manipulation similar to editing a blueprint and much faster. The rendering that occurs with the virtual DOM also uses a method called diff that compares the virtual DOM to the now updated Version and only updates the objects that have changed on the real DOM. This results in React updating only the necessary parts of the DOM, and this is why React has a reputation for performance.

1. Virtual DOM gets updated
2. Virtual DOM compared to virtual DOM (this is not the same Virtual DOM as the new one) before changes
3.  **Only** the changed object gets updated on the real DOM.
4. Screen changes follow.

# In your own words, describe React's core concept of uni-directional data flow. Draw diagrams to illustrate. Discuss the answer with your mentor in your next session.

> Uni-directional data flow describes a single direction data can flow from parent to child. With a single direction the view or what you see on screen automatically re-renders itself as a result of state changes. A given view is linked to a state and view rendering can be done fast due to Reacts diff method. Furthermore, this unidirectional and immutable data flow allows for much easier debugging when something goes wrong, since it can be traced down to the component where the code broke. In comparison, using MVC architecture narrowing down of where and what went wrong is much more difficult due to the model being able to be mutated by any component.  
