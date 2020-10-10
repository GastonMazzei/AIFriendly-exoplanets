# AIFriendly-exoplanets
AIFriendly learns the period based on the values for radio and the mass of the associated star

<b>STATING THE PROBLEM</b>
<i>The "famous" Kepler's third law states a proportionality that is actually mass-dependant.<br>
If we don't include the mass for each planet then it won't be able to plot them all in a line because the log/log plot would require a different offset for each point (refer to the ending)</i>
<img src="images/equation">

<b>THE DATABASE</b><br>
<i><a link="http://exoplanets.org/">The Exoplanets Database (Harvard?)</a> has info about ~400 parameters for ~5k exoplanets.<br>
Not all of them are physical tho. We filtered it and kept the onse that weren't vettoed by the organization AND also had info about the associated star's mass.<br>
The remaining dataset was then of 2.5k planets.</i>
<img src="images/perfect_line">


<b>AI-FRIENDLY WAS USED AS A REGRESSOR</b><br>
<i>1.8k planets were used for training<br>
0.4k planets were used for validation<br>
0.4k planets were used for testing<br></i>
<img src="images/training">

<b>THE RESULTS</b><br>
AI-Friendly was an excellent regressor. 
There might be a lot of ways to formulate a classification problem; we should pick one and show that AI-Friendly can do that too.
As the regression problem was solved, we have absolute certainty the classification will be solved too.
<img src="./images/result">