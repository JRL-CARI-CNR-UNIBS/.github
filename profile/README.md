# Joint research Lab CARI CNR-STIIMA UNIBS-DIMI


## IK solver
Compute all the IK solutions.
- TF -> ik solution
- PoseArray -> ik_solutions
- Eigen::Affine3d -> ik_solution

_Common packages_:

- messages and services:   [ik_solver_msgs](https://github.com/JRL-CARI-CNR-UNIBS/ik_solver_msgs)

- base class for plugins, node to expose services: [ik_solver](https://github.com/JRL-CARI-CNR-UNIBS/ik_solver)

_Application-specific packages_:

- ik_solver implementation using [rosdyn](https://github.com/CNR-STIIMA-IRAS/rosdyn):  [rosdyn_ik_solver](https://github.com/JRL-CARI-CNR-UNIBS/rosdyn_ik_solver)


_Collision checking package_:

package to compute collision checking on multiple configuration

- [collision_check_server](https://github.com/JRL-CARI-CNR-UNIBS/collision_check_server)

## Help  and  Installation
read [here](https://github.com/JRL-CARI-CNR-UNIBS/installation/blob/master/README.md)
