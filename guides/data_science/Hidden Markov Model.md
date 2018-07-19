# Hidden Markov Model (HMM)

Hidden Markov Model is a statistical model which generates models based on a set of input sequence.These sets of input sequence are called as states represented as s1,s2,s3.....sn.
Each state is associated with a probability distribution .

In HMM the system being modelled is assumed to be a Markov chain with unobserved hidden states. In simpler Markov models like a Markov chain the state is directly visible to the observer and thus the state transition probabilities are the only parameters. In a hidden markov model the state is not directly visible but the output dependent on the state is visible .Each state has a probability distribution over the possible output tokens therefore the sequence of tokens generated gives some information about the sequence of states .The adjective hidden refers to the state sequence through which the model passes,not to the parameters of the model,the model is still referred to a hidden markov model even if these parameters are known exactly.Hidden markov models are specially known for their application in speech,gesture,handwriting recoginition etc. A hidden markov model can be considered as a generalization of a hidden model where the hidden variables which control the mixture component to be selected for each observation are related to a markov process rather than independent of each other.Hidden markov models have been generalized to pairwise markov models and triplet markov models which allow consideration of more complex data structures.

The requirement for HMM is Markov Property Satisfaction. Markov property is a property which is memory less. It is called memory less because Markov model considers only one state at a time.This model is a relatively simple way to model sequential data. A hidden Markov model implies that the Markov Model underlying the data is hidden or unknown to you. More specifically, you only know observational data and not information about the states. In other words, there’s a specific type of model that produces the data (a Markov Model) but you don’t know what processes are producing it. You basically use your knowledge of Markov Models to make an educated guess about the model’s structure.
