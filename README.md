# Background of Path Planning to Aviation Engineering

It is the Homepage for Group 14 of AAe1001.

We should finish before 1/12/2024.


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
    <ol>
      <li><a href="#Introduction">Introduction<a/></li>
      <li><a href="#Task 1">Task 1<a/></li>
      <li><a href="#Cost of 3 scenario">Cost of 3 scenario</a></li>
      <li><a href="#Task 2">Task 2<a/></li>
      <li><a href="#Task 3">Task 3<a/></li>
      <li><a href="#Additional Task 1">Additional Task 1<a/></li>
      <li><a href="#Additional Task 2">Additional Task 2<a/></li>
      <!--<li><a href="#Additional Task 3">Additional Task 3<a/></li>-->
    </ol>
</details>

<a id="Introduction"></a>
## Introduction
Path Planning to Aviation Engineering is about designing better air routes to reduce fuel consumption, increase efficiency, and ultimately increase the airline's ability to make money. 

<a id="Task 1"></a>
## Task 1
For task 1, we are required to: <br>
<ul>
<li> Find an appropriate aircraft model that achieve minimum cost for each scenario for the challenge assigned to your group. <br> </li>
</ul>

<!--![Task 1.gif](https://github.com/Leaf-Joy/AAE1001-Group14/blob/main/Photos/Task%201.gif?raw=true) <br>-->
<p align="center">
  <img src="https://github.com/Leaf-Joy/AAE1001-Group14/blob/main/Photos/Task%201.gif?raw=true" alt="Task 1.gif" width="90%" height="90%"> <br>
  <img src="https://github.com/Leaf-Joy/AAE1001-Group14/blob/main/Photos/Task%201%20output.png?raw=true" alt="Task 1 output.png"> <br>
</p>
First, we modify the A* code by adjusting borders, obstacles, starting & ending point, and cost-intensive areas. Then we can find the shortest path and the shortest time to reach the ending point from the starting point. <br>
<p align="center">
  <img src="https://github.com/Leaf-Joy/AAE1001-Group14/blob/main/Photos/Cost%20formula.png?raw=true)" alt="Cost formula.png"> <br>
  <img src="https://github.com/Leaf-Joy/AAE1001-Group14/blob/main/Photos/Task%201%20scenarios.png?raw=true" alt="Task 1 scenarios.png" wdith="1137" height="347"> <br>
</p>
<!--![Cost formula.png](https://github.com/Leaf-Joy/AAE1001-Group14/blob/main/Photos/Cost%20formula.png?raw=true) <br>
![Task 1 scenrios.png](https://github.com/Leaf-Joy/AAE1001-Group14/blob/main/Photos/Task%201%20scenarios.png?raw=true) <br>-->
After finding the time, we calculate the cost of 3 aircrafts based on this formula in 3 different scenarios. <br>

<!-- Cost of 3 scenario -->
<a id="Cost of 3 scenario"></a>
## Cost of 3 scenarios
<table style="width: 100%" border="1">
      <tbody>
        <tr>
          <td><br>
          </td>
          <td>scenario 1</td>
          <td>scenario 2</td>
          <td>scenario 3</td>
        </tr>
        <tr>
          <td>A321</td>
          <td>80664.78199526577</td>
          <td>38651.84154413771</td>
          <td>93392.7503747729</td>
        </tr>
        <tr>
          <td>A330-900neo</td>
          <td>94516.06151080105</td>
          <td>54319.666004656065</td>
          <td>92937.6516749357</td>
        </tr>
        <tr>
          <td>A350-900</td>
          <td>97911.9406095872</td>
          <td>49770.00548336953</td>
          <td>94129.60386034427</td>
        </tr>
      </tbody>
    </table>

The aircraft type to achieve minimum cost :<br> 
Scenario 1 : A321<br>
Scenario 2 : A321<br>
Scenario 3 : A330-900neo<br>


<a id="Task 2"></a>
## Task 2
For task 2, we are required to: <br>
<ul>
<li> Design a new cost area (jet stream) that can reduce the cost of the route. <br> </li>
</ul>

<!--![Task 2.gif](https://github.com/Leaf-Joy/AAE1001-Group14/blob/main/Photos/Task%202.gif?raw=true) <br>-->
<p align="center">
  <img src="https://github.com/Leaf-Joy/AAE1001-Group14/blob/main/Photos/Task%202.gif?raw=true" alt="Task 2.gif" width="90%" height="90%"> <br>
  <img src="https://github.com/Leaf-Joy/AAE1001-Group14/blob/main/Photos/Task%202%20output.png?raw=true" alt="Task 2 output.png"> <br>
</p>
We modify the code so that jet stream is added from (-12,5) to (60,10), in which the new cost equals to 0.95 times the original cost. <br>

<a id="Task 3"></a>
## Task 3
For task 3, we are required to: <br>
<ul>
<li> Design a new aircraft model that achieve minimum cost for the challenge assigned to your group. <br> </li>
</ul>

Name of aircraft: Cloud Cruiser - 777 <br>
Passenger capacity: 449 <br>
Engine count: 4 <br>

<p align="center">
  <img src="https://github.com/Leaf-Joy/AAE1001-Group14/blob/main/Photos/Task%203%20example.png?raw=true" alt="Task 3 example.png" width="707" height="441"> <br>
</p>
We calculate the cost based on different passenger capacity of the aircraft model. Then, we find that when passenger capacity is 449, the cost is the lowest. <br>


<a id="Additional Task 1"></a>
## Task A1
For task A1, we are required to: <br>
<ul>
<li>Add one checkpoint for each cost ontensive area (two in total). <br> </li> 
<li>Reach all checkpoints before arriving at the destination. <br> </li> 
</ul>

![This is an image](https://raw.githubusercontent.com/Leaf-Joy/AAE1001-Group14/refs/heads/main/Photos/TastA1.gif) <br>
We link the original starting point (starting point 0) to the new end point 1 created and set the position of end point 1 as starting point 1, then the positions of end point 1 and starting point 1 become check points 1. Then use the same logic to make checkpoint 2, but checkpoint 2 is link to the original end point. <br>


<a id="Additional Task 2"></a>
## Task A2
For task A2, we are required to modify the code so that: <be>
![This is an image](https://raw.githubusercontent.com/Leaf-Joy/AAE1001-Group14/refs/heads/main/Photos/Tast%20A2%20(1)%2000_00_00-00_00_30.gif)
![This is an image](https://raw.githubusercontent.com/Leaf-Joy/AAE1001-Group14/refs/heads/main/Photos/Tast%20A2%20(2)%2000_00_00-00_00_30.gif)
![This is an image](https://raw.githubusercontent.com/Leaf-Joy/AAE1001-Group14/refs/heads/main/Photos/Tast%20A2%20(3)%2000_00_00-00_00_30.gif)
<ul>
<li> Only the fuel-consuming area remains and generate it randomly with a fixed area (40x40) <br> </li>
<li> Diagonal movement is disabled, change parameter(s) so that the object could travel within one grid size <br> </li>
<li> Obstacles are generated randomly with reasonable density <br> </li>
<li> Destination and starting points are generated randomly with at least a 40-unit distance in-between <br> </li>
<li> Plotting of the fuel-consuming area would not cover the obstacles, and obstacles should not generate at/near the start and end point <br> </li>
</ul>


<!--
<a id="Additional Task 3"></a>
## Task A3
For task A3, we are required to: <br> 
<ul>
<li> Choose 2 more algorithms from GitHub repositories <br> </li>
<li> Modify the code so all 3 algorithms are working with the same obstacle set <br> </li>
<li> Try and compare the algorithms and conduct a discussion <br> </li>
</ul>
-->
