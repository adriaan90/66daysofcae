# **Tuning fork benchmark**

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)


[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


Solution to the tuning fork example as found on [CoFEA](https://cofea.readthedocs.io/en/latest/) website using multiple FEA solvers.

# **Summary of problem**
The tuning fork is used as a benchmark test for modal analysis.

Information, dimensions, geometry files and solutions can be found on [CoFEA](https://cofea.readthedocs.io/en/latest/). Here follows a summary:

## **Tuning fork information**
Material properties are:
- E = 2.07E11 N/m^3
- poisson ratio = 0.33
- density = 7829 kg/m^3

## **Mode analysis**
| Modes | Frequency (Hz) |
|-------|----------------|
| 1     | 441.7          |
| 2     | 679.2          |
| 3     | 1691.8         |
| 4     | 1831.2         |
| 5     | 2787.6         |

# **What solvers are included**
- Salome Meca 
- Ansys (to be added)
- Elmer (to be added)
- CalculiX (to be added)

# **How to Contribute**

1. Clone repo and create a new branch: `$ git checkout https://github.com/adriaan90/66daysofcae.git -b name_for_new_branch`.
2. Make changes and test
3. Submit Pull Request with comprehensive description of changes
