### majorana-repo
Repo created to post codes developed during my monograph as a requirement to bachelor degree in Physics

# Outline
Motivated by new methods of quantum computation we tried to study a hybrid system based on a semiconductor-supercondutor junction (SNS). 
Specifically, we studied a state that emerges on the edges of the proposed system, called Majorana Bound States (MBS), as proposed by Kitaev (2001).

## The Code
The code was developed in two phases: Kitaev toy model (2001) and a nanowire model as proposed by lutchyn (2011). 
Inside the notebooks of each code is a brief description of the matematical model.

### Kitaev Toy Model

The model is considered only a toy because it make assumptions that are not trivial from the experiemntal perspective. 
Kitaev considers a 1D wire with a uniform distribution of fermions fixed in fermionic sites - for the tight-binding model. Kitaev also make the fermionic sites coupled by p-type superconducting interaction.

This code is modeled directly from the tight-binding formalism of the Kitaev model, using the majorana operators as way to index the coefficients. 
With this, a matrix of the hamiltonian is filled and diagonalized to extract the eigenvalues - and to find the Majorana Zero Modes/Bound States!

### Nanowire Model

For the nanowire model we worked with de reciprocal space to better unsderstand the role of each phenomena added as we progress from the toy model to the nanowire model.
