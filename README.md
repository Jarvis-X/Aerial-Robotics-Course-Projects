# Aerial-Robotics-Course-Projects
## HW1 - A point mass goes down a parabola then falls freely
  - For interactive notebook, go to https://colab.research.google.com/drive/1SNLn41Jt0Q0HoxVbntAPTlg0CzSwHGLp?usp=sharing
  
  - Important parameters:
  
    - In the first cell, we can change the friction coefficient, damping factors, mass, and even gravity. We can also choose to enable/disable the fiction and damping effects.
    - In the last cell, the variable ***sampling*** controls the ratio of visualization samplings. For example, ***sampling = 10*** means every 1 out of 10 data points are visualized.

## HW2 - position and attitude controller
  - Part a: launch a projectile on a ramp with not parallel force input
    - For interactive notebook, go to https://colab.research.google.com/drive/1HlUETEldiHSXAVo6sqwZfGaZCL3xcmWI?usp=sharing
    - Important parameters:
      - In the forth cell, we can set the relative position of the target to the end of ramp by changing `x_t` and `y_t`
  - Part b: place a rod with care
      - For interactive notebook, go to https://colab.research.google.com/drive/1YxV9Z6BHG0ghsUX1eXtSjnWWXJkrLoBd?usp=sharing
      - Important parameters:
        - In the first cell, we can set the desired state of the rod by modifying `des_state` whose unit is [rad, rad/s]

## HW4 - 2D mutirotors
  - Part a: controlling a fully-actuated rigid mutirotor system. Notebook file: CS498HW4Single.ipynb
    - For interactive notebook, go to https://colab.research.google.com/drive/11i3Ypmu5VCZX0gJVKHburbBzGW0hQmkq?usp=sharing
    - Important parameters in the first cell: 
      - inertia: `I`
      - mass `m`
      - Do we want constains? `en_constrain = False` This somehow affects the performance very badly.
      - number of motors `n`
      - position of the thrusters `p`
      - tilting angles of the propellers `alpha`
      
  - Part b: controlling a fully-actuated mutirotor system that consists of two rigid segments. Notebook file: CS498HW4DoublePen.ipynb
      - For interactive notebook, go to https://colab.research.google.com/drive/1JBnZ6BNrV6XSq7xZNsVIBRgbU44lQprr?usp=sharing
      - Important parameters:
        - In the first cell, we can set the masses of the two segments of rods by changing `m1`, `m2`; the *half length* of the rod can be changed by modifying `l`.
        - We can also change the tilting angles of the inner propellers by altering `alpha` and `beta` 
        - `en_constrain = True` gives us a peek over the effects of the limited thrusts

## HW6 - 3D magic box
  - Note the changes we made in magicbox.ttt. Notebook file: CS498HW6MagicBox.ipynb
    - For interactive notebook, go to https://colab.research.google.com/drive/1C4iBLhZsbcEgFsV4vO2uo_RFEP4m82am?usp=sharing
