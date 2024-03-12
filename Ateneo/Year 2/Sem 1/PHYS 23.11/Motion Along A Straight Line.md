mechanics: relationships among force, matter, and motion
kinematics: mechanics that describe motion
dynamics: motion and its causes

velocity and accelerations: both vectors

## 2.1 Displacement, Time, and Average Velocity
Average x velocity: $$v_{av-x}=\frac{x_2-x_1}{t_2-t_1}=\frac{\Delta x}{\Delta t}$$
![[Pasted image 20230813143329.png]]
* average x velocity does not provide information about what happens in between the points of interest

## 2.2 Instantaneous Velocity
* instantaneous velocity: velocity at a specific instant of time or point along a path
Instantaneous x velocity: $$v_x=\lim_{\Delta t \to 0}{\frac{\Delta x}{\Delta t}}=\frac{dx}{dt}$$
![[Pasted image 20230813152500.png]]
x speed: $$v=\frac{d}{t}=\frac{distance}{time}$$

## 2.3 Average and Instantaneous Acceleration
average x acceleration: $$a_{av-x}=\frac{v_{2x}-v_{1x}}{t_2-t_1}=\frac{\Delta v}{\Delta t}$$
velocity: position changes with time
acceleration: velocity changes with time
instantaneous acceleration: $$a_x=\lim_{\Delta t \to 0}{\frac{\Delta v_x}{\Delta t}}=\frac{dv_x}{dt}$$ alternative definition: $$a_x=\frac{dv_x}{dt}=\frac{d}{dt}\left(\frac{dx}{dt}\right)=\frac{d^2x}{dt^2}$$![[Pasted image 20230813162817.png]]
![[Pasted image 20230813162949.png]]

## 2.4 Motion with Constant Acceleration
$$v_x=v_{0x}+a_xt\text{\quad (constant acceleration only)}$$
$$x=x_0+v_{0x}t+\frac{1}{2}a_xt^2\text{\quad (constant acceleration only)}$$
area under $v_x–t$ graph: $$x-x_0=v_{0x}t+\frac{1}{2}a_xt^2\text{\quad (constant acceleration only)}$$
$$v_x^2=v_{0x}^2+2a_x(x-x_0)\text{\quad (constant acceleration only)}$$
$$x-x_0=\left(\frac{v_{0x}+v_x}{2} \right)t\text{\quad (constant acceleration only)}$$

equation | includes quantities
-- | --
$v_x=v_{0x}+a_xt\text{\quad (constant acceleration only)}$ | $t\;\;\;v_x\;a_x$
$x=x_0+v_{0x}t+\frac{1}{2}a_xt^2\text{\quad (constant acceleration only)}$ | $t\;x\;\;\;a_x$
$v_x^2=v_{0x}^2+2a_x(x-x_0)\text{\quad (constant acceleration only)}$ | $\;\;\;x\;v_x\;a_x$
$x-x_0=\left(\frac{v_{0x}+v_x}{2} \right)t\text{\quad (constant acceleration only)}$ | $t\;x\;v_x$

## 2.5 Freely Falling Bodies
free fall: idealized motion where the acceleration is constant
$g=9.8\;m/s^2$
g is always position (magnitude of a vector quantity)

## 2.6 Velocity and Position by Integration
$$v_x=v_{0x}+\int_0^ta_xdt$$
$$x=x_0+\int_0^tv_xdt$$

## Summary
### Straight-line motion, average and instantaneous x-velocity
describe position with coordinate axis
$$\text{average x–velocity:\quad}v_{av–x}=\frac{x_2-x_1}{t_2-t_1}=\frac{\Delta x}{\Delta t}$$
$$\text{instantaneous x–velocity: \quad}v_x=\lim_{\Delta t \to 0}\frac{\Delta x}{\Delta t}=\frac{dx}{dt}$$
![[Pasted image 20230813193202.png]]

### Average and instantaneous x-acceleration
$$\text{average x–acceleration:\quad}a_{av–x}=\frac{v_{2x}-v_{1x}}{t_2-t_1}=\frac{\Delta v_x}{\Delta t}$$
$$\text{instantaneous x–acceleration:\quad}a_x=\lim_{\Delta t \to 0}\frac{\Delta v_x}{\Delta t}=\frac{dv_x}{dt}$$
![[Pasted image 20230813194936.png]]

### Straight-line motion with constant acceleration
constant x-acceleration only:
$$v_x=v_{0x}+a_xt$$
$$x=x_0+v_{0x}t+\frac{1}{2}a_xt^2$$
$$v_x^2=v_{0x}^2+2a_x(x-x_0)$$
$$x-x_0=\left(\frac{v_{0x}+v_x}{2}\right)t$$
### Freely falling bodies
free fall: case of motion with constant acceleration
magnitude due to gravity is a positive quantity $g=9.80\;m/s^2$
acceleration of a body in free fall is always downward
![[Pasted image 20230813195741.png]]

### Straight-line motion with varying acceleration
find velocity and position as functions of time by integration when acceleration is not a constant but a function of time
$$v_x=v_{0x}+\int_0^ta_xdt$$
$$x=x_0+\int_0^tv_xdt$$
![[Pasted image 20230813200410.png]]