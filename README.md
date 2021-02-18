 
# Sorting nertwork in TL-V with visualization

Sort a set of numbers, provided in a 1-dimensional array.
The sorting network is a pipeline (though not using a TLV pipeline because stages are replicas).
Each pipeline stage has a copy of the array and performs one sorting step.
A sorting step involves sorting adjacent pairs of numbers.
In even stages, natural pairs are compared ((0,1), (2,3), ...); on odd ((0), (1,2), (3,4), ...).
