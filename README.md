# React_API

<h2>Hooks</h2> <br/>
<a href="https://www.youtube.com/watch?v=O6P86uwfdR0&list=PLZlA0Gpn_vH8EtggFGERCwMY5u5hOjf-h"> 1. Web Dev Simplified </a> <br/>
<a href="https://www.youtube.com/watch?v=cF2lQ_gZeA8&list=PLC3y8-rFHvwisvxhZ135pogtX7_Oe3Q3A"> 2. Codevaluation </a>


<br/>
Some imp points: <br/>
- hooks not for class components, only to be used for functional components <br/>
- should be execute in the same order. You canno't put hooks inside a nested functions, if statements, loops. It should be at the top level of the function called exactly in the same order. <br/>
- Call react hooks from within React functional components and not just any regulat js function<br/>

<h3>1. Use State</h3> <br/>
<array of 2 values [(i) current value of the state value, (ii)  method capable to update the value state property(<argument to set current_value to that argument>)]> useState(<initial/default value of the state property>) <br/>
Updating state property through hooks will re-render and update the state property at all instances, updating it manually won't re-render and update all instances.  <br/>
The very first time  the component renders, a state variable is created and initialized with the default value. The default value is never used in re-renders. On call of change menthod, it will cause the component to rerender, after re-render the property will contain the updated value




