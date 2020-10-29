# AIFriendly-exoplanets
:ringed_planet:AIFriendly learned the period based on the values for radio and the mass of the associated star

---

<h2><p align="center">1) Stating the problem</p></h2>
Kepler's third law states a mass-dependent proportionality between the orbital radius and the orbital period: <br>
<i>(left)</i>Newton's equation for the gravitational pull and the radial acceleration, <i>(middle)</i> rearrangement of the factors and <i>(right)</i> Kepler's law.
<img src="images/equation.png">

<h2><p align="center">2) A database with values for mass, orbital period and orbital radius for a few thousand exoplanets</p></h2>
[The Exoplanets Database](http://exoplanets.org/) provides ~400 parameters for ~5k exoplanets. The three parameters we are interested in (radius, period and mass) are present in the list of parameters.<br>
<i>A reduced version was used by filtering based on keeping only planets that weren't vettoed by the organization, thus the remaining dataset was then of 2.5k planets.</i><br>
<img src="images/perfect_line.png">

<h2><p align="center">3) </p></h2>
<i>1.8k planets were used for training<br>
0.4k planets were used for validation<br>
0.4k planets were used for testing<br></i>
<img src="images/training.png">

<b>THE RESULTS</b><br>
AI-Friendly was an excellent regressor. 
There might be a lot of ways to formulate a classification problem; we should pick one and show that AI-Friendly can do that too.
As the regression problem was solved, we have absolute certainty the classification will be solved too.
<img src="./images/result.png">
