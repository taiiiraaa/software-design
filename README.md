# software-design

Law of Demeter: 
- Caller object should only need to `tell` the callee object to do something. We shouldn't `ask` the object what it knows or what it need to do, in order to do something. 
- As the caller, you should not be making decisions based on the state of the called object that result in you then changing the state of the object. Logic you are implementing is probably the called object's responsibility, not yours. For you to make decisions outside the object violates its encapsulation.

Analogy, when one wants a dog to walk, one does not command the dog's legs to walk directly; instead one commands the dog which then commands its own legs. 
