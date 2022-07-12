# Brachiation Via Trajectory Optimization

**Version 1.0.0**

## [Video Link](https://www.youtube.com/watch?v=3BG0AfvlN64)
[Paper](/BattleMonkey6832000.pdf)

---

## Information

1) ***Summary*** </br>

    -- The following files are from the one month final project from the 2022 version of Underactuated Robotics at MIT <br/>
    -- Everything is a work in progress, it was open ended research with many paths for future exploration <br/>
    -- Used Compass Gait Limit Cycles notebook as an outline for doing trajectory optimization with drake<br/>
    -- The two contributers agreed on the modelling and overall project direction, 
    but two slightly different representations of the problem were pursued. 
    The first is an in-depth look at the horizontal monkey bars problem, consisting of all files besides varying_bar_height.ipynb. 
    The other is an exploration into solving the problem of bars of varying heights, and also comparing to the double pendulum along the way. <br/>

---

2) ***Files*** </br>

    -- battle_monkey_urdf: the process of creating a proper monkey urdf <br/>
    -- wrist_shoulder_act.ipynb: work done wiht the actuators in the wrong place. <br/>
    -- double_shoulder_act.ipynb: work done with the two actuators on the shoulders <br/>
    -- upside_down_walking.ipynb: simulating upside down walking to use as a comparison with what is actually found with optimized brachiation. <br/>
    -- varying_bar_height.ipynb: A long file, consisting of a different urdf process, and work swinging on bars of different angles than purely horizontal. <br/>

---



## Contributers
**Russ Tedrake** Proided ipynb notebooks for homework assignments which were heavily referenced, and some code was copied. </br>
**Kaleb Blake** Partner in this project, who contributed all the files besides varying_bar_height.ipynb</br>
**Myself** Wrote varying_bar_height.ipynb


---

## License and copyright

***MIT License:***
Copyright (c) 2022 John Flynn

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
