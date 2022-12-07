# IK solver
Compute all the IK solutions.
- TF -> ik solution
- PoseArray -> ik_solutions
- Eigen::Affine3d -> ik_solution

## Common packages:

- messages and services:   [ik_solver_msgs](https://github.com/JRL-CARI-CNR-UNIBS/ik_solver_msgs)

- base class for plugins, node to expose services: [ik_solver](https://github.com/JRL-CARI-CNR-UNIBS/ik_solver)

## Application-specific packages:

- ik_solver implementation using [rosdyn](https://github.com/CNR-STIIMA-IRAS/rosdyn):  [rosdyn_ik_solver](https://github.com/JRL-CARI-CNR-UNIBS/rosdyn_ik_solver)

- implementation for Universal Robot (using [ur_kinematics](https://github.com/ros-industrial/universal_robot)): [ur_ik_solver](https://github.com/JRL-CARI-CNR-UNIBS/ur_ik_solver)

- implementation for robot mounted on positioners: [robot_on_guide_ik_solver](https://github.com/JRL-CARI-CNR-UNIBS/robot_on_guide_ik_solver)




## Collision checking package:

package to compute collision checking on multiple configuration

- [collision_check_server](https://github.com/JRL-CARI-CNR-UNIBS/collision_check_server)
