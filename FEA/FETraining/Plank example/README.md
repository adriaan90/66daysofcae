# **Plank Example**

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)


[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


Solution to the plank example as found on [FETraining](https://www.fetraining.net/) website using multiple FEA solvers.

# **Summary of problem**
The plank model is used in the course *Introduction to Dynamics in FEA* hosted by Tony Abbey. The problem has two parts:
- Plank spanning a river
- Plank spanning a river with a lumped mass at the center.

Information, dimensions, geometry files and solutions can be found on [FETraining](https://www.fetraining.net/). Here follows a summary:

## **Plank information**
The plank is assumed to be isotropic and modelled using the thin shelled elements.
It is simply support at both ends with dimensions 3.6576m x 0.6096m x 0.0254m. Material properties are:
- E = 1.213E10 N/m^3
- poisson ratio = 0.33
- density = 498.2 kg/m^3
- lumped mass = 81.81 kg

## **Mode analysis**
| Modes | Without mass (Hz) | With mass (Hz) |
|-------|-------------------|----------------|
| 1     | 4.258             | 1.631          |
| 2     | 17.11             | 17.10          |
| 3     | 32.36             | 28.14          |
| 4     | 38.60             | 32.36          |

# **What solvers are included**
- Salome Meca 
- Ansys (to be added)
- Elmer (to be added)
- CalculiX (to be added)

# **How to Contribute**

1. Clone repo and create a new branch: `$ git checkout https://github.com/adriaan90/66daysofcae.git -b name_for_new_branch`.
2. Make changes and test
3. Submit Pull Request with comprehensive description of changes