# AI
Am just learning some niche AI stuff.

---

## [AutoGrad](https://www.youtube.com/watch?v=VMj-3S1tku0)
 - [ ] Implement variable containing value that can be combined with other values using:
   - [ ] Addition
   - [ ] Subtraction
   - [ ] Multiplication
   - [ ] Division
   - [ ] Power
 - [ ] Also implement following operations on variables to create expressios:
   - [ ] tanh
   - [ ] exp
   - [ ] negation
   - [ ] ReLu
 - [ ] Add visualizer for variables and expressions.
 - [ ] Implement computation of gradients of direct expression children.
 - [ ] Use chain rule to combine direct gradients through expression.
 - [ ] Backpropagation should generate gradint function.
 - [ ] Use toposort to correctly traverse graph.
 - [ ] Fix issue if we combine two same values (e.g., a + a), thus accumulate gradients.
 - [ ] Implement neuron - inputs x, weights w, and bias b.
 - [ ] Randomly initialize neuron values.
 - [ ] Create neuron layer - array of neurons.
 - [ ] Create MLP - structure holding multople neuron layers with input and output layer.
 - [ ] Implement loss function - compute squared error from output.
 - [ ] Run backward propagation of gradient on loss function.
 - [ ] Iterate over all parameters and slightly shift them using negative loss gradient.
 - [ ] Implement learning:
   - [ ] Compute loss
   - [ ] Restore grads so next batch don't accumulate previous itrations gradients.
   - [ ] Backward gradient propagation.
   - [ ] Update graph using negative loss gradient.
 - [ ] Implement batch learning - use sampled batches from training data.
