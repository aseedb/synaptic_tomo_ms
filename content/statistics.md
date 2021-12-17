##number of connectors per SV
### SNAP-25
|   group | distance   | mean     | count    | std | sem      |
|----|----------|----------|-----|----------|----------|
| 4E | 45       | 1.414634 | 41  | 1.224247 | 0.191195 |
|    | 75       | 1.031250 | 32  | 1.121185 | 0.198199 |
|    | 150      | 1.826772 | 127 | 2.012242 | 0.178558 |
|    | 250      | 1.686131 | 137 | 1.935549 | 0.165365 |
|    | 450      | 1.386047 | 215 | 1.749443 | 0.119311 |
|    | 900      | 1.427273 | 220 | 1.792725 | 0.120866 |
| 4K | 45       | 1.823529 | 17  | 2.214591 | 0.537117 |
|    | 75       | 0.444444 | 18  | 0.783823 | 0.184749 |
|    | 150      | 1.622222 | 90  | 1.732555 | 0.182627 |
|    | 250      | 1.500000 | 106 | 1.747106 | 0.169694 |
|    | 450      | 2.575419 | 179 | 2.759795 | 0.206277 |
|    | 900      | 2.355191 | 183 | 2.054093 | 0.151843 |
| WT | 45       | 1.951220 | 41  | 2.407812 | 0.376037 |
|    | 75       | 1.400000 | 10  | 1.505545 | 0.476095 |
|    | 150      | 2.392000 | 125 | 2.636273 | 0.235795 |
|    | 250      | 3.234310 | 239 | 3.309573 | 0.214078 |
|    | 450      | 2.819578 | 521 | 2.871960 | 0.125823 |
|    | 900      | 2.801115 | 538 | 2.886983 | 0.124467 |
### Time resolved
|      group       |   distance                 |   mean   | count |    std   |    sem   |
|-------------|--------------------|:--------:|:-----:|:--------:|:--------:|
| spray_ctrl  | 45                 | 1.632812 | 128   | 1.515646 | 0.133965 |
|             | 75                 | 1.752475 | 101   | 2.021910 | 0.201188 |
|             | 150                | 2.568129 | 433   | 1.946174 | 0.093527 |
|             | 250                | 2.779439 | 535   | 2.255237 | 0.097502 |
| spray_early | 45                 | 2.241935 | 62    | 2.609475 | 0.331404 |
|             | 75                 | 2.300000 | 40    | 2.053140 | 0.324630 |
|             | 150                | 3.340782 | 179   | 2.415089 | 0.180512 |
|             | 250                | 3.311787 | 263   | 2.041958 | 0.125913 |
| spray_late  | 45                 | 1.121212 | 66    | 1.234319 | 0.151934 |
|             | 75                 | 1.850000 | 60    | 1.792877 | 0.231459 |
|             | 150                | 3.172662 | 278   | 2.354589 | 0.141219 |
|             | 250                | 2.838710 | 403   | 2.338578 | 0.116493 |
### significances
#### SNAP
|                                         |
|-----------------------------------------|
| WT proximal --> distal 1 : p = 0.32     |
| WT proximal --> distal 2 : p = 0.0043   |
| 4K proximal --> intermediate : p =0.023 |
| intermediate WT --> 4K : p = 0.082      |
| distal 1 WT --> 4K. p=0.011             |
| distal 1 WT --> 4E. p=0.057             |
| distal 2 WT --> 4K. p=0.0000000….       |
| distal 2 WT --> 4E. p=0.00000002        |
#### TimeRes
|                                                   |
|---------------------------------------------------|
| spray_ctrl proximal --> distal 1: p = 0.00000004  |
| spray_ctrl proximal --> distal 2: p = 0.0000000…. |
| early proximal --> distal 1: p = 0.0044           |
| early proximal --> distal 2 : p = 0.0034          |
| late proximal --> distal 1: p = 0.000000000..     |
| late proximal --> distal 2: p = 0.000000000..     |
| proximal ctrl --> early p = 0.09                  |
| proximal ctrl --> late. p = 0.013                 |
| distal 1 ctrl --> early. p = 0.0002               |
| distal 1 ctrl --> late. p = 0.0004                |
| distal 2 ctrl --> early. p = 0.0009               |
| distal 2 ctrl --> late. p = 0.69                  | 

### significances for fractions  of connected vesicles per distance group (Figure 5 C/D) 
#### SNAP
|         |                         |              WT             |         |                         |              4E             |         |                         |              4K             |         |
|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:-------:|
|         | number of connected SVs | number of non connected SVs | p-value | number of connected SVs | number of non connected SVs | p-value | number of connected SVs | number of non connected SVs | p-value |
|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:-------:|
|   0-45  |            23           |              18             |    1    |            28           |              13             |    1    |            9            |              8              |    1    |
|  45-75  |            6            |              4              |   0.89  |            19           |              13             |   0.59  |            6            |              12             |   0.4   |
|  75-150 |            87           |              38             |   0.16  |            89           |              38             |   0.98  |            58           |              32             |   0.53  |
| 150-250 |           184           |              55             |  0.008  |            88           |              49             |   0.77  |            69           |              37             |   0.49  |
| 250-450 |           399           |             122             |  0.0063 |           126           |              89             |   0.32  |           124           |              55             |   0.27  |
| 450-900 |           369           |             169             |   0.14  |           124           |              96             |   0.21  |           146           |              37             |  0.026  |


|         |                         |              WT             |         |                         |              4E             |           |                         |              4K             |         |
|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:---------:|:-----------------------:|:---------------------------:|:-------:|
|         | number of connected SVs | number of non connected SVs | p-value | number of connected SVs | number of non connected SVs |  p-value  | number of connected SVs | number of non connected SVs | p-value |
|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:---------:|:-----------------------:|:---------------------------:|:-------:|
|   0-45  |            23           |              18             |    1    |            28           |              13             |    0.36   |            9            |              8              |   0.94  |
|  45-75  |            6            |              4              |    1    |            19           |              13             |    0.74   |            6            |              12             |   0.33  |
|  75-150 |            87           |              38             |    1    |            89           |              38             |    0.96   |            58           |              32             |   0.52  |
| 150-250 |           184           |              55             |    1    |            88           |              49             |   0.011   |            69           |              37             |   0.03  |
| 250-450 |           399           |             122             |    1    |           126           |              89             | 0.0000015 |           124           |              55             |   0.06  |
| 450-900 |           369           |             169             |    1    |           124           |              96             |   0.0018  |           146           |              37             |  0.005  |

#### TimeRes
|         |                         |         spay control        |         |                         |         spray early         |         |                         |          spray late         |           |
|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:---------:|
|         | number of connected SVs | number of non connected SVs | p-value | number of connected SVs | number of non connected SVs | p-value | number of connected SVs | number of non connected SVs |  p-value  |
|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:---------:|
|   0-45  |            63           |              27             |    1    |            32           |              13             |    1    |            20           |              18             |     1     |
|  45-75  |            46           |              22             |   0.89  |            16           |              6              |   0.88  |            32           |              14             |   0.172   |
|  75-150 |           323           |              61             |  0.0032 |           129           |              23             |   0.06  |           213           |              32             | 0.0000008 |
| 150-250 |           483           |              71             | 0.00005 |           258           |              23             | 0.00011 |           333           |              57             | 0.0000013 |


|         |                         |         spay control        |         |                         |         spray early         |         |                         |          spray late         |         |
|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:-------:|
|         | number of connected SVs | number of non connected SVs | p-value | number of connected SVs | number of non connected SVs | p-value | number of connected SVs | number of non connected SVs | p-value |
|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:-------:|:-----------------------:|:---------------------------:|:-------:|
|   0-45  |            63           |              27             |    1    |            32           |              13             |   0.95  |            20           |              18             |   0.09  |
|  45-75  |            46           |              22             |    1    |            16           |              6              |   0.86  |            32           |              14             |   0.99  |
|  75-150 |           323           |              61             |    1    |           129           |              23             |   0.93  |           213           |              32             |   0.39  |
| 150-250 |           483           |              71             |    1    |           258           |              23             |   0.06  |           333           |              57             |   0.48  |
|         |                         |                             |         |                         |                             |         |                         |                             |         |
|         |                         |                             |         |                         |                             |         |                         |                             |         |