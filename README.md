# cse5004-homework-5--simulation-of-baseball-dynamics-solved
**TO GET THIS SOLUTION VISIT:** [CSE5004 Homework 5- Simulation of Baseball Dynamics Solved](https://www.ankitcodinghub.com/product/cse5004-scientific-computation-with-python-solved-5/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115378&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE5004 Homework 5- Simulation of Baseball Dynamics Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
HW5. Simulation of Baseball Dynamics

1. (Runge-Kutta Methods) Solve the initial-value problem x′ = t + 2xt with x(0) = 0 on the interval [0,2] using the Runge-Kutta formulas.

(1) Find x(t) using the second-order Runge-Kutta method with h = 0.01.

(2) Find x(t) using the fourth-order Runge-Kutta method with h = 0.01.

(3) Compare the solutions in (1) and (2) with the true solution: 1) and discuss order of accuracy for two Runge-Kutta methods.

(4) Discuss the effect of the step size h on the solutions by using the fourth-order Runge-Kutta method.

Hint: Compare the errors at t = 2 between the numerical and true solution for the different step sizes h = 0.01,0.05,0.1.

(1)

(2)

(3)

) (4)

(5)

(6)

where vx,vy,vz are the velocity vector components of the baseball, is the speed of the baseball. B is a dimensionless quantity that specifies the magnitude of the Magnus force, ω is the rotation rate of the baseball and ϕ describes the direction of ω, relative to z axis. g is the gravitational acceleration (g = 9.81m/s2). Note that B = 4.1 × 10−4 and ω = 1800rpm. The drag force on the ball F(V ) is assumed as:

. (7)

(1) Make a code for solving the above six equations using the fourth-order Runge-Kutta method. Appropriate initial conditions at t = 0 are x(0) = 0,y(0) = 0,z(0) = h,vx = v0 cosθ,vy = 0,vz = v0 sinθ where v0 is the initial speed of the pitch, θ is the elevation angle of the pitch and h is the vertical displacement from the ground to ball release point. You need to solve the equations until the baseball reaches to the catcher x(t) = 18.39m. Provide a detailed procedure for making a code.

Figure 1: (a) Physics of baseball and (b) rotation direction for four pitches

(2) Solve the equations for four pitches shown in Figure 1(b) and plot trajectories of the baseball for each pitches. Typical elevation angle is θ = 1◦, the initial speeds of the fastball and others are v0 = 40m/s and v0 = 30m/s, respectively. Rotation directions ( and 135◦ for the fastball, curveball, slider and screwball, respectively. Note that h = 1.7m.
