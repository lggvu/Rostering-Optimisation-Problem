## Problem information
This is a Mini Project associated with the course **Fundamentals of Optimisation** (HUST) guided by Dr.Pham Quang Dung, SOICT.
- There are N staffs 1,2,..., N needs to be assigned to work shifts for days 1, 2, ..., D. Each day is divided into four shifts: morning, noon, afternoon, and night.
- Each day, an staff can only work one shift at most. If you work the night shift the day before, you can rest the next day.
- Each shift in each day has at least alhpa staffs and at most beta staffs.
- F(i): list of staffs rest days i.
**Objective:** The maximum number of night shifts of any employee is minimised.
Moreoever, we need to generated larger instances of the problem, written to a file of the following format:
- Line 1: N, D, alpha, beta.
- Other lines: off days of each employee, ending with `-1`.

## Collaborators 
| Name                         | Student ID       | Mail                                      |
| :---                         |    :----:        |          :---:                             |
| Le Duc Anh Tuan              | 20204929         | tuan.lda204929@sis.hust.edu.vn            |
| Hoang Gia Nguyen             | 20204889         | nguyen.hg204889@sis.hust.edu.vn           |
| Hoang Long Vu                | 20204897         | vu.hl204897@sis.hust.edu.vn               |
| Nguyen Huu Tuan Duy          | 20204907         | duy.nht204907@sis.hust.edu.vn             |

- `Final_Code.ipynb` contains every algorithms and the process of generating, visualising and analysing the data. 
- The running time of the algorithms are tested on different number of employees (**N**) on four different time intervals (**D**): 30 days, 180 days, 365 days, and 1000 days. The running time data is written to *.csv* files in the `running_time` folder. 
- `data.txt` is the original data file provided by our Professor.
- The `python` folder contains *.py* files (which are later merged together in `Final_Code.ipynb`.)
- The `data` folder contains our generated data for each time interval (30 days, 180 days, 365 days, and 1000 days).
