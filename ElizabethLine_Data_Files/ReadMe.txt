Passenger Demand Data:

This file contains the **randomly generated passenger demand data** used for the London Elizabeth Line case study.

To incorporate passenger-oriented evaluation into the proposed framework, passenger demand parameters for each train-course sequence were randomly generated following the approach introduced by Zhang et al. [1].

Data Structure

| Column     | Description                      |
| ---------- | -------------------------------- |
| `course`   | Train-course identifier          |
| `sequence` | Sequence identifier              |
| `off`      | Number of passengers getting off |
| `on`       | Number of passengers getting on  |
| `total`    | Total passenger demand           |

The dataset is provided as the passenger demand input for the computational experiments of the proposed framework.

Timetable Data

The timetable and operational data for the London Elizabeth Line case study were obtained from the Railway Applications Section (RAS) [2] problem data.

Detailed information and descriptions of the RAS problem data, including the timetable and other model inputs, are provided in the RAS_PSC_problem_description_v24.pdf file included in this repository.


Reference

[1] Zhang, C., Gao, Y., Cacchiani, V., Yang, L., and Gao, Z., “Train rescheduling for large-scale disruptions in a large-scale railway network”, Transportation Research Part B: Methodological, Vol. 174,  pp. 102786, 2023.

[2] RAS, “informs railway-applications,” 2022; https://connect.informs.org/railway-applications/new-item3/problem-repository16.