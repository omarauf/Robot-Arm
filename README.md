
# Design
![](https://raw.githubusercontent.com/omarauf/Robot-Arm/master/PIC/Robot.PNG)

The robot arm consists of 2-Link which indicate its 2-dof it’s RR. We will use Polytetrafluoroethylene (Teflon) which has 2.2 $g/cm^3$ density 

#### Properties of 1# link: 

$I$ = $\begin{pmatrix}161529.88 & -211.48 & 4671.96 \\-211.48 & 758590.39 & 6013.40 \\4671.96 & 6013.40 &  891271.09\end{pmatrix}$ $g*cm^2$

mass = 358.306058 $g$
Volume = 162866.39 $mm^3$
Length = 208 $mm$
Center of mass = 100 $mm$

#### Properties of 2# link: 

$I$ = $\begin{pmatrix}22635.48 & 562.80 & -18217.18 \\562.80 & 542088.37 & -16066.38 \\-18217.18 & -16066.38 & 552126.87\end{pmatrix}$ $g*cm^2$

mass = 308.756558 $g$
Volume = 140343.89 $mm^3$
Length = 200 $mm$
Center of mass = 73 $mm$

For the motor we will use JX RD-B7640HV-180 40KG this motor Weight around 75g and can produce torque up to 40 $$kg*cm$$ and this motor Dual shaft in each side 

![](https://raw.githubusercontent.com/omarauf/Robot-Arm/master/PIC/Motor.jpeg)

# Simulation

![](https://raw.githubusercontent.com/omarauf/Robot-Arm/master/PIC/Page%201.jpg)
![](https://raw.githubusercontent.com/omarauf/Robot-Arm/master/PIC/Page%202.jpg)
![](https://raw.githubusercontent.com/omarauf/Robot-Arm/master/PIC/Page%203.jpg)


We use these equations for simulation in MATLAB Simulink and we used acceleration control model to control the arm. 

![](https://raw.githubusercontent.com/omarauf/Robot-Arm/master/PIC/Simulation_Page.jpg)
 
