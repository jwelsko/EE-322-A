# Lab 3 - Python

## CPE 322-A
### For the following lab, we will be using the Python programming language to run a variety of python scripts using python packages such as jdcal, astral, and geopy.

#### julain.py
This script displays the current calander date, the Julian date, and the modified Julian date.

```bash
(venv) bdx@bdx-PowerEdge-R220:~/iot/lesson3$ python3 julian.py
Calendar Date: 2025-03-30
Julian Date: 2460764.5
Modified Julian Date: 60764.0
```

#### date_example.py
This script displays the date and time in a variety of formats.

```bash
(venv) bdx@bdx-PowerEdge-R220:~/iot/lesson3$ python3 date_example.py
Date: 2025-03-30
Date: 03-30-25
Day of Week: Sunday
Month: March
Year: 2025
68 days after the first day of classes
38 days before the last day of classes
```

#### datetime_example.py
This script displays a number of different date timestamp formats. 

```bash
(venv) bdx@bdx-PowerEdge-R220:~/iot/lesson3$ python3 datetime_example.py
2025-03-30 19:32:35.604894
2025-03-30 19:32:35.604930
2025-03-30 23:32:35.604941
1743377555.6049457
Sun Mar 30 19:32:35 2025
2025-03-30 19:32:35.604982
2025-03-30 23:32:35.604992
```

#### time_example.py
This script displays the current time in a variety of formats with the current time being displayed every 10 seconds.

```bash
(venv) bdx@bdx-PowerEdge-R220:~/iot/lesson3$ python3 time_example.py
Sun Mar 30 19:33:38 2025
Sun Mar 30 19:33:48 2025
Sun Mar 30 19:33:58 2025
Sun Mar 30 19:34:08 2025
Sun Mar 30 19:34:18 2025
Sun Mar 30 19:34:28 2025
Sun Mar 30 19:34:38 2025
Sun Mar 30 19:34:48 2025
Sun Mar 30 19:34:58 2025
^C
```

#### sun.py
This script displays the sunrise, sunset, and dusk times for a given location.

```bash
(venv) bdx@bdx-PowerEdge-R220:~/iot/lesson3$ python3 sun.py "New York"
Information for New York/USA

Timezone: US/Eastern
Latitude: 40.72; Longitude: -74.00

Dawn:    2025-03-30 06:14:29.498139-04:00
Sunrise: 2025-03-30 06:42:32.647804-04:00
Noon:    2025-03-30 13:00:30-04:00
Sunset:  2025-03-30 19:18:45.168595-04:00
Dusk:    2025-03-30 19:46:52.728534-04:00
```

#### moon.py
This script displays the moon phase for a given date.

```bash
(venv) bdx@bdx-PowerEdge-R220:~/iot/lesson3$ python3 moon.py
2025-03-30 Moon Phase: 1
2025-03-31 Moon Phase: 2
2025-04-01 Moon Phase: 3
2025-04-02 Moon Phase: 4
2025-04-03 Moon Phase: 5
2025-04-04 Moon Phase: 6
2025-04-05 Moon Phase: 7
2025-04-06 Moon Phase: 8
2025-04-07 Moon Phase: 9
2025-04-08 Moon Phase: 10
2025-04-09 Moon Phase: 11
2025-04-10 Moon Phase: 11
2025-04-11 Moon Phase: 12
2025-04-12 Moon Phase: 13
2025-04-13 Moon Phase: 14
2025-04-14 Moon Phase: 15
2025-04-15 Moon Phase: 16
2025-04-16 Moon Phase: 16
2025-04-17 Moon Phase: 17
2025-04-18 Moon Phase: 18
2025-04-19 Moon Phase: 19
2025-04-20 Moon Phase: 20
2025-04-21 Moon Phase: 21
2025-04-22 Moon Phase: 22
2025-04-23 Moon Phase: 23
2025-04-24 Moon Phase: 24
2025-04-25 Moon Phase: 25
2025-04-26 Moon Phase: 26
2025-04-27 Moon Phase: 27
2025-04-28 Moon Phase: 0
```

#### coordinates.py
This script displays the coordinates of a given location.

```bash
(venv) bdx@bdx-PowerEdge-R220:~/iot/lesson3$ python3 coordinates.py "Samuel C. Williams Library"
Samuel C. Williams Library, Field House Road, Uptown, Hoboken, Hudson County, New Jersey, 07030, United States
(40.74480675, -74.02532861159351)
```

#### address.py
This script displays the address of a given location from a set of coordinates.

```bash
(venv) bdx@bdx-PowerEdge-R220:~/iot/lesson3$ python3 address.py "40.74480675, -74.02532861159351"
Stevens Institute of Technology, 1, Wittpenn Walk, Uptown, Hoboken, Hudson County, New Jersey, 07030, United States
(40.744809599999996, -74.0252392276461)
```

#### cpu.py
This script displays the number of physical cores, logical CPUs, and the utilization per second as a percentage for each CPU.

```bash
(venv) bdx@bdx-PowerEdge-R220:~/iot/lesson3$ python3 cpu.py
The number of physical cores =  4
The number of logical CPUs =  8
The utilization per second as a percentage for each CPU
[0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0]
[0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0]
[1.0, 0.0, 1.0, 1.0, 1.0, 1.0, 1.0, 0.0]
[0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0]
[0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 1.0, 0.0]
[0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 1.0, 0.0]
[0.0, 0.0, 0.0, 0.0, 1.0, 0.0, 0.0, 0.0]
[0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 1.0]
[0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0]
[0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 1.0, 0.0]
```

#### battery.py
This script displays the battery status of the system.

```bash
(venv) bdx@bdx-PowerEdge-R220:~/iot/lesson3$ python3 battery.py
None
```

#### documentstats.py
This script displays the word count and the top ten words in a given document.

```bash
(venv) bdx@bdx-PowerEdge-R220:~/iot/lesson3$ python3 documentstats.py document.txt
Word Count: 1343
Top Ten Words: [('our', 26), ('their', 20), ('has', 20), ('he', 19), ('them', 15), ('these', 13), ('have', 11), ('we', 11), ('us', 11), ('people', 10)]
```