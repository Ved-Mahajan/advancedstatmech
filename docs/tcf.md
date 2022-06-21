# Time Correlation Functions

In this section, we will look into time correlation functions.

## Equilibrium vs non equilibrium statistical mechanics

When the system is in equilibrium, it has a unique equilibrium state. For this equilibrium state, one can define a unique partition function. Using this partition function once can determine many physical quantities of the system like thermodynamic potential, density of states and so on.

However, in the case of non equilibrium case, there is no unique non-equilibrium state. Hence, once cannot define a unique partition function.

**Time correlation functions (TCF)** play the role of partition function for a non equilibrium system. TCFs arise whenever we want to analyse the statistical behavious of a time depenedent quantity, $A(t)$ measured over a long period of time.

Time average of a quantity $A(t)$ over a time period $\tau$ is defined as

$$
\langle A \rangle = \frac{1}{\tau} \int_0^{\tau} A(t)dt
$$

Fluctuation in $A(t)$ about its mean
$$
\delta A(t) = \langle A \rangle - A(t)
$$

!!! definition "Definition"
    **Time Correlation Function** of $\delta A(t)$ is defined as the time average of product of two fluctuations at two different times.

    $$
    C_{\delta A \delta A}(t) = \frac{1}{\tau} \int_0^{\tau}  ds \delta A(s)\delta A(t+s)  
    $$

