Given data contains molecular trajectories of a molecule. A molecular dynamics trajectory for a
set of N atoms is essentially an ordered set of 3N-dimensional vectors. We perform analytical
steps to analyze the number of phases present in the trajectory. We use dimensionality
reduction to reduce the dependent parameters from 3D to 2D. Then we use unsupervised
clustering methods to classify the datset into np.of phases.

The data file consists of 10000 snapshots of the molecule at different time. Each frame consists
of the cartesian coordinates (x, y and z) of all the constituting atoms of the molecule.
