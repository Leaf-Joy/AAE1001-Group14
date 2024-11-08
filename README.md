# Background of Path Planning to Aviation Engineering

It is the Homepage for Group 14 of AAe1001.

We should finish before 1/12/2024.


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
    <ol>
      <li><a href="#Introduction">Introduction<a/></li>
      <li><a href="#Task 1">Task 1<a/></li>
      <li><a href="#Task 2">Task 2<a/></li>
      <li><a href="#Task 3">Task 3<a/></li>
      <li><a href="#Additional Task 1">Additional Task 1<a/></li>
      <li><a href="#Additional Task 2">Additional Task 2<a/></li>
      <li><a href="#Additional Task 3">Additional Task 3<a/></li>
      <li><a href="#Cost of 3 scenario">Cost of 3 scenario</a></li>
    </ol>
</details>

<a id="Introduction"></a>
## Introduction
Path Planning to Aviation Engineering is about designing better air routes to reduce fuel consumption, increase efficiency, and ultimately increase the airline's ability to make money. 

<a id="Task 1"></a>
## Task 1
For task 1, we are required to: <br>
Find an appropriate aircraft model that achieve minimum cost for each scenario for the challenge assigned to your group. <br>


<a id="Task 2"></a>
## Task 2
For task 2, we are required to: <br>
Design a new cost area (jet stream) that can reduce the cost of the route. <br>


<a id="Task 3"></a>
## Task 3
For task 3, we are required to: <br>
Design a new Aircraft Model that achieve minimum cost for the challenge assigned to your group. <br>


<a id="Additional Task 1"></a>
## Task A1
For task A1, we are required to: <br>
<ul> <li>
Add one checkpoint for each cost ontensive area (two in total). <br>
Reach all checkpoints before arriving at the destination. <br>
</li> </ul>

![This is an image](https://raw.githubusercontent.com/Leaf-Joy/AAE1001-Group14/refs/heads/main/Photos/TastA1.gif) <br>
We link the original starting point (starting point 1) to the new end point 1 created and set the position of end point 1 as starting point 2, then the positions of end point 1 and starting point 2 become check points 1. Then use the same logic to make checkpoint 2, but checkpoint 2 is link to the original end point. <br>


<a id="Additional Task 2"></a>
## Task A2
For task A2, we are required to: <br>
Modify the code so that: <br>
-Only the fuel-consuming area remains and generate it randomly with a fixed area (40x40) <br>
-Diagonal movement is disabled, change parameter(s) so that the object could travel within one grid size <br>
-Obstacles are generated randomly with reasonable density <br>
-Destination and starting points are generated randomly with at least a 40-unit distance in-between <br>
-Plotting of the fuel-consuming area would not cover the obstacles, and obstacles should not generate at/near the start and end point <br>


<a id="Additional Task 3"></a>
## Task A3
For task A3, we are required to: <br>


<!-- Cost of 3 scenario -->
<a id="Cost of 3 scenario"></a>
## Cost of 3 scenario
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

