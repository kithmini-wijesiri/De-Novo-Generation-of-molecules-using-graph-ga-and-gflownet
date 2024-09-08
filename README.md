# De-Novo-Generation-of-molecules-using-graph-ga-and-gflownet

A **graph-based genetic algorithm** (GraphGA) is a variation of a genetic algorithm (GA) that operates on molecular graphs rather than traditional linear representations (like SMILES). It combines the principles of genetic algorithms—such as evolution through selection, mutation, and crossover—with the graph-based representation of molecules, where atoms are nodes and bonds are edges in a graph. 

**GFlowNet** (Generative Flow Networks) is an emerging framework designed for generating complex objects (like molecules) by learning probabilistic models of sequences of actions that construct those objects. When applied to fragment-based molecular design, GFlowNet becomes a powerful tool for efficiently navigating and constructing molecules by assembling them from smaller fragments, with the goal of optimizing certain desired properties (e.g., binding affinity, drug-likeness).

The key difference between GFlowNet and traditional generative models like GANs or VAEs is that GFlowNet explicitly models the process of constructing the object step by step, assigning probabilities to each step.
