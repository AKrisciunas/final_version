# Program that calculates students results

Time tests were made with this computer:
* Processor	AMD Ryzen 3 5300U with Radeon Graphics, 2600 Mhz, 4 Core(s), 8 Logical Processor(s)
* Installed Physical Memory (RAM)	16.0 GB
* DISK SSD
* OS Microsoft Windows 11 Home

## Speed tests (in seconds)

### Reading data from file time
| Container | 1 000  | 10 000 | 100 000 | 1 000 000 |
| --------- | ------:| ------:| -------:| ---------:|
| vector    | 0.0017 | 0.0563 | 0.1825  | 1.8113    |
| list      | 0.0022 | 0.0198 | 0.1709  | 1.9085    |

### Student separation into 2 categories time (using average method)
| Container | 1 000  | 10 000 | 100 000 | 1 000 000 |
| --------- | ------:| ------:| -------:| ---------:|
| vector    | 0.0036 | 0.0366 | 0.4238  | 5.7179    |
| list      | 0.0034 | 0.0406 | 0.5044  | 6.3049    |

### Data output to files time
| Container | 1 000  | 10 000 | 100 000 | 1 000 000 |
| --------- | ------:| ------:| -------:| ---------:|
| vector    | 0.0035 | 0.0133 | 0.0871  | 0.7466    |
| list      | 0.0034 | 0.0113 | 0.1242  | 0.9998    |
