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
      - For interactive notebook, go tohttps://colab.research.google.com/drive/1YxV9Z6BHG0ghsUX1eXtSjnWWXJkrLoBd?usp=sharing
      - Important parameters:
        - In the first cell, we can set the desired state of the rod by modifying `des_state` whose unit is [rad, rad/s]
