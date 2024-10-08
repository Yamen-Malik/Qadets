# Development-of-Novel-Quantum-Algorithms
Womanium Quantum+AI 2024 Projects

**Please review the participation guidelines [here](https://github.com/womanium-quantum/Quantum-AI-2024) before starting the project.**

_**Do NOT delete/ edit the format of this read.me file.**_

_**Include all necessary information only as per the given format.**_

## Project Information:

### Team Size:
  - Maximum team size = 3
  - While individual participation is also welcome, we highly recommend team participation :)

### Eligibility:
  - All nationalities, genders, and age groups are welcome to participate in the projects.
  - All team participants must be enrolled in Womanium Quantum+AI 2024.
  - Everyone is eligible to participate in this project and win Womanium grants.
  - All successful project submissions earn the Womanium Project Certificate.
  - Best participants win Womanium QSL fellowships with Classiq. Please review the eligibility criteria for QSL fellowships in the project description below.

### Project Description:
  - Click [here](https://drive.google.com/file/d/1PGNUShboB4ik_JHZGcIPTh3KYi-aajzp/view?usp=sharing) to view the project description.

## Project Submission:
All information in this section will be considered for project submission and judging.

Ensure your repository is public and submitted by **August 9, 2024, 23:59pm US ET**.

Ensure your repository does not contain any personal or team tokens/access information to access backends. Ensure your repository does not contain any third-party intellectual property (logos, company names, copied literature, or code). Any resources used must be open source or appropriately referenced.

### Team Information:
Team Member 1:
 - Full Name: Yamen Ghozlan
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx): WQ24-ymI9KFvPVUtaaE8


Team Member 2:
 - Full Name: Onyinyechukwu Joseph Ezuma
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx): WQ24-PSuSutfiEod6UJV


Team Member 3:
 - Full Name: Murshed SK
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx): WQ24-C2cpbdhbJn4yHXr



### Project Solution:
_Include a comprehensive summary of all important information about your project solution here._
All necessary code files and any additional information required to judge your project solution should be included in the repository.

Our project goal was to create a quantum circuit that simulates Trotterized time evolution in a 2D transverse-field Ising model system, and mitigate noise in the system with Zero Noise Extrapolation (ZNE).

The project includes multiple files showing the steps of the implementation, starting with a toy problem with only 4 qubits, all the way up to a scalable implementation that can run with a variable number of qubits and evolution steps, including a polynomial ZNE and exponential ZNE models.

The solution includes an implementation of a simple noise simulation technique that's required to simulate the noise that would be present in a quantum processor, when using a simulator.


**Repository Structure:**

    ├── Notebooks       <- Jupyter notebooks of the steps of implementing the problem.
    |   ├── 1 toy problem.ipynb               <- Jupyter notebook containing basic implementation of the toy problem.
    |   ├── 2 expandable toy problem.ipynb    <- Jupyter notebook expanding of the implementation of the toy problem.
    |   ├── 3 solution 2 layers.ipynb         <- Jupyter notebook containing and scalable version of the problem.
    |   └── 4 final solution.ipynb            <- Jupyter notebook containing the final implementation including noise mitigation.
    ├── Test Results    <- CSV files that maintains a small testing sample showing the effect of noise mitigation.
    |   ├── test1.csv                         <- Holds results of running the first test from step 4 notebook.
    |   └── test2.csv                         <- Holds results of running the second test from step 4 notebook.
    ├── Classiq's Files <- Classiq formatted files such as QProg and QMod.
    |   ├── QPrograms      <- Holds QProg files of different steps of the project.
    |       ├── 4 Qubit Toy Problem Model.qprog                 <- Basic circuit of the toy problem.
    |       ├── 16 Qubit Model.qprog                            <- 16 Qubit circuit as an expansion of the toy problem.
    |       ├── Expandable Toy Problem Model.qprog              <- The resulting circuit of the scalable problem.
    |       ├── Multiple Trotter Steps Model.qprog              <- Circuit with multiple Trotter steps.
    |       └── Pauli Linblad Noise Model on Toy Problem.qprog  <- [Extra] a circuit implementation of Pauli Linblad Noise Model.
    |   └── QModels      <- Holds QMod files of different steps of the implementation.
    |       ├──  1 toy problem.qmod                             <- Basic implementation of the toy problem.
    |       ├──  2 expandable toy problem.qmod                  <- Expanding of the implementation of the toy problem.
    |       ├──  3 solution 2 layers.qmod                       <- Containing and scalable version of the problem.
    |       └──  4 final solution.qmod                          <- Containing the final implementation including noise mitigation.
    └────


### Project Presentation Deck:
_Link a 5min. presentation recording or deck here._

[Presentation](https://docs.google.com/presentation/d/1SoQNyLU56uhwORmT4s8IuVS5dB01WVR3p9xGnzoCA5E/edit?usp=sharing)

