# Table of Contents
- [General info](#desc)
- [Run](#run)
- [Prerequisites](#pre)

<a name="desc"></a>
# General info
F1-race simulation
- 14 F1 drivers - with randomly given skill, decreasing fuel condition, overtaking AI and obviously desire of winning the race
- 3 pitstops - with 3 engineers in each, unfortunately each pitstop can handle any driver
- 9 engineers - with randomly given skill, their job is changing wheels and refueling
- 2 storekeepers - with randomly given skill, their job is recycling used wheels and supplying fuel to the pitstop

<a name="run"></a>
# Run

```
$ mkdir build && cd build
$ cmake ..
$ make
$ ./f1-race
```
<a name="pre"></a>
# Prerequisites
- [ncurses](https://en.wikipedia.org/wiki/Ncurses)
- [compiler with c++17 support](https://gcc.gnu.org/)



