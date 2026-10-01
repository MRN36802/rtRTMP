=Tehran Metro Line 1 Data

This folder contains the timetable and passenger demand data used for the Tehran Metro Line 1 case study.

Data Files

1. Timetable Data

The timetable data for both directions of Tehran Metro Line 1 were obtained from information published by the Tehran Urban and Suburban Railway Operation Company (Metro) [1].

The Excel file contains timetable data for:

* `Kahrizak_Tajrish`: Timetable from Kahrizak to Tajrish
* `Tajrish_Kahrizak`: Timetable from Tajrish to Kahrizak

2. Passenger Demand Data

A separate file contains the passenger demand data generated for the Tehran Metro Line 1 case study.

The passenger demand parameters were randomly generated following the approach introduced by Zhang et al. [2].

Data Structure

| Column     | Description                      |
| ---------- | -------------------------------- |
| `course`   | Train-course identifier          |
| `sequence` | Sequence identifier              |
| `off`      | Number of passengers getting off |
| `on`       | Number of passengers getting on  |
| `total`    | Total passenger demand           |


Reference

[1] Tehran Urban and Suburban Railway,” 2025; https://metro.tehran.ir/.

[2] Zhang, C., Gao, Y., Cacchiani, V., Yang, L., and Gao, Z., “Train rescheduling for large-scale disruptions in a large-scale railway network”, Transportation Research Part B: Methodological, Vol. 174,  pp. 102786, 2023.
