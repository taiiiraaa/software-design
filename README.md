# software-design

### Law of Demeter: 
- You should only need to tell objects what you want them to do; do not ask them questions about their state, make a decision, and then tell them what to do
- As the caller, you should not be making decisions based on the state of the called object that result in you then changing the state of the object. The logic you are implementing is probably the called object's responsibility, not yours. For you to make decisions outside the object violates its encapsulation.
  - Object A can call a method of object B.
  - Object A should not call object B, in order to call a method of object C.
  
Analogy, when one wants a dog to walk, one does not command the dog's legs to walk directly; instead one commands the dog which then commands its own legs. 


### Stateless Services
- To Do

### Thread
- Smallest sequence of programmed instructions that can be managed independently and executed.
- Many threads can exist within one process, executing concurrently and sharing resources such as memory. While different processes do not share these resources.
