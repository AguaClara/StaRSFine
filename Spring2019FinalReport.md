# StaRS FInE, Spring 2019
#### Lily Falk, Sam Hertle, and Whitney Denison
#### May 10, 2019

## Abstract

StaRS FInE has worked to develop an improved filter technology for AguaClara outlet pipes. Filtration is the last step in an AguaClara plant. As a result, it is the last opportunity to remove particles that have slipped through all previous treatment processes.
Prior to StaRS FInE, the outtake pipes used in vertical filtration were problematic because small slits in the pipes would clog with chemical deposits. In order to clean the filters and wash away the deposits, clean water was emptied from the larger outlets to increase outflow velocity through the slots to dislodge the chemicals. In the process, clean water was wasted. StaRS FInE designed an alternative to the outtake pipes, triangular in shape, and therefore referred to as the “Christmas tree” design. The design relied on larger openings to prevent clogs, as well as the gravity exclusion principle to prevent sand from exiting the outlet pipes. The focus of StaRS FInE in the spring of 2019 was to test the three dimensional model printed in the fall of 2019 with sand to find what velocity leads to failure in the form of sand in the outlets.

## Introduction
The spring of 2019 was StaRS FInE's second semester working on recent improvements since being disbanded in the fall of 2015. The subteam was brought back in the fall of 2018 because of its continued relevance to AguaClara plants. The filter system used then became clogged throughout the day with chemical deposits, mostly from PaCl, but there was no sustainable solution to the clogging. Chemical deposits built up on the small slots of the filters, and the plant had to be temporarily shut off periodically for cleaning. During this cleaning (not to be confused with backwash, where the sand particles in the filter are cleaned), clean water would be purged to dislodge the build up on the pipes. Alternatively, buckets of acid could be poured into the filter to clean them, which was also not ideal. In both of these scenarios, the filter could not be used while it was cleaned, and clean water was wasted, whether it was being used to purge the pipe or to divert water from the filters while they were being cleaned with acid.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/Screen%20Shot%202019-05-03%20at%2012.53.21%20PM.png" width= "500"> </p>
<p align="center">
  Figure 1. The slotted pipes used for water extraction in current plants.
</p>

The team's design was intended to be attached to the outlet pipes as the current slotted pipes are. The design consists of three triangular branches that sit on top of one another, which would be extended to cover the length of the sand filters.

The goal of StaRS FInE was to develop and test an outlet system that prevented sand from escaping and did not clog with chemical deposits. Past teams failed because of issues with sand getting into their outlet pipes during filtration. The past team did develop designs that worked during backwash, however the filtration velocity was too large for the parameters of their design and the water effluent contained a significant amount of sand. Because this problem occurred at the filtration outtake, the team was very conscious of head loss and the major and minor losses coming from the outlet pipe and the design geometry.


The goals for the spring of 2019 were to test the apparatus (designed and 3D printed in the Fall 2018) with sand, discover the failure velocity for this apparatus, and make changes to the spacing of the branches and angles if necessary. The original spacing and angles were based on some of the research of Horizontal Filtration (another AguaClara subteam), the results of testing by past StaRS teams, and the library of AguaClara fluid mechanics calculations. The team also had to discover the possible modes of failure. Failure modes may be caused by flow that is too fast, which may lead to sand moving up as a solid plug or small grains of sand getting into the outlet pipe. Fall 2018's design was promising, but before it was ready to be proposed as a solution, many more tests had to be run.

Gravity exclusion is a principle that explains some interaction between sand and water that informs the research and fabrication of StaRS FInE. The idea is that for two flat surfaces (branches) creating a roof with a specific angle, if sand were to get beneath the branch, it would slide down with gravity and remain outside of the outlet. The water beneath the branches creates enough pressure that the sand remains out of the outlet pipe and in the gravity exclusion zone. This zone is formed by the sand that settles beneath the branches. The biggest challenge with preventing sand from going into the outlet happens during forward filtration, when water is moving quickly through the outlet. In this case, the sand-water interface at the edge of the exclusion zone must be large enough that the force of gravity on the sand is greater than the force of the water moving up through the sand.

## Literature Review and Previous Work

The work of StaRS FInE has not been investigated outside of AguaClara, making the project exciting, ~~and~~ requiring innovation on the part of each team member. In the past, the team has found examples related to filters from aquaponics and various filtering methods. That being said, the alternate systems are more complicated, and would have encountered the same issues that AguaClara filters had already faced. The StaRS FInE team members remained the same from the fall of 2018 to the spring of 2019. That being said, the team focused on research in the fall, whereas the team shifted to fabrication in the spring.

From the reports of the 2015 team, it seems that the necessary wingspan and size of the sand-water interface was not calculated correctly. This is supported by their lack of success with keeping sand from exiting the filter during higher forward filtration velocities. The size of the spring of 2019's model interface is much larger and there has been greater success in keeping sand out of the outlets.

In the fall of 2018 the team discovered  a few key insights. First, the team tested the angle at which sand falls in a pipe filled with water to determine an optimal angle where sand escaping the gravity exclusion zone is still likely to fall back down. The optimal angle was determined to be 26.64 degrees.  

From the calculations done with the AguaClara fluid calculation Python code library, a "Christmas tree" design was created in OnShape and 3D printed to fit inside of a 4-inch tube. Unlike previous teams dating back to 2015, the fall 2018 team ensured that the flow rate, velocity, and wing area of the apparatus all work together to prevent sand from exiting during backwash. This apparatus is still being used this semester as a main tool for research.

## Methods

### Experimental Apparatus Design
#### Trial 1

The apparatus was designed in OnShape last semester, first including a 3D-printed horizontal filter, and then a 4-Inch diameter PVC pipe that would become the prototype for StaRS FInE testing of the gravity exclusion method for extraction. For more information on this apparatus, reference the Fall 2018 Report. Below are the OnShape part studio, the OnShape drawings, and the photo of the newly fabricated apparatus. After assembling the apparatus, it was designed to have outlet holes in the filter and in the prototype that match tubing size for the outlet flow rate.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/ApparatusOnshape.png" width= "500"> </p>
<p align="center">
  Figure 2. The OnShape Drawing of the prototype.
</p>
<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/FIlterDrawing.png" width= "500"> </p>
<p align="center">
  Figure 3. The part studio design of the 3D printed filter.
</p>
<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/ApparatusDrawing.png" width= "500"> </p>
<p align="center">
  Figure 4. The part studio design of the whole prototype.
</p>
<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/ApparatusReal.png" width= "700"> </p>
<p align="center">
  Figure 5. The apparatus setup with peristaltic pumps and tubing.
</p>

The experiments up to trial 1 had tested the filter's ability to form sand exclusion zones. Monroe suggested that the team simulate real life AguaClara filter conditions as best as possible. Therefore, it was designed so that the inlet, below the filter, would simulate the injection source for forward filtration.

The design also considered the rate at which injection and extraction would occur. AguaClara plant sand filters perform filtration by running water through and extracting from the sand bed at controlled rates. The respective injection and extraction rates were calculated based on backwash velocity and the respective design of the team's apparatus. This is calculated in the Python code in the [manual](#Manual) below. These rates were converted to RPM for the use of peristaltic pumps in ProCoDa, marked as inject and extract. The values for the first trial were as follows:
| Injection Flow Rate     | Extraction Flow Rate
|---------------------------|-----------------------|
| 36.67 mL/s | 18.36 mL/s      |


In the first trial, the team allowed the injection flow (inlet) to fill the tube to the top before the extraction pump (outlet) was turned on. The extraction pump pulled water until the prototype was halfway drained and then the extraction pump would turn off again. At this point, gravity made injection from the top of the apparatus unnecessary and acted as an "injection" source. The idea was that because the water level was rising to above the top branch, gravity would act to pull this water out and the system would behave the same way as it would if the team were actively pumping in water from the top.

The last design consideration was converting between mL/s and RPM on the peristaltic pump that was connected to the inlet and outlet tubing. The team made new set points that converted to RPM values for the pump using ProCoDa, the outlet and inlet flow in mL/s and the tubing sizes (16 for outlet and 18 for inlet). More is detailed about the set points below in the [manual](#Manual). This was a design consideration for the team because the tubing size was adjusted in the apparatus based on the capacity of the peristaltic pump rates and calculations in ProCoDa.


#### Trial 2
In the design of the second experimental apparatus, the team reconsidered the flow rates of injection and extraction pumps. Understanding more about the application of the prototype to real Aguaclara Filters, the team calculated the following:

| Injection Flow Rate | Extraction Flow Rate |
| ------------------- | -------------------- |
| 36.67 mL/s         | 36.67 mL/s           |

After trial 1, the team came to understand that the 6 layers of sand filter would be extracting at the same rate. Therefore, the flow rate that the team had used previously was not sufficiently large.

Again, more information about these number can be found in the Python code below in the [manual](#Manual).

The team used the same method of filling the prototype to the top before draining and turning off the extraction before the water level reached below the extraction tubes.

#### Trial 3
In anticipation of failure, the team first decided to measure whether only one filter outlet could consistently extract at the flow rate of 36.67 mL/s. To do so, the team planned on stopping flow from the upper two holes and attaching one pump to the injection tube one pump to the extraction tube. Therefore, the apparatus was designed so that the team could monitor the extraction zone and escape of sand into the outlet more closely.

#### Trial 4

In actual AguaClara plants, the water is driven out of the filter by gravity, there are not electric pumps. Therefore, the apparatus was changed so that water could freely flow out of the outlets, rather than having tubing and peristaltic pump pulling it out.

The team obtained a rubber cap and clamp for the top of the apparatus, thinking that the system would fill up and possibly overflow. It was discovered that this was not a concern because at steady-state, the water level does not rise above the level that the pressure from the atmosphere establishes. This pressure was an issue in this trial because water was only exiting from the bottom branch. If the holes were plugged in order to allow the whole apparatus to fill with water, the water would flow out from the three branches quickly until the water level was only above the last hole again. There was also a problem when the top was placed on during forward filtration that it pushed air into the reactor and forced sand out of the holes. No sand exited when the apparatus was left still and the exclusion zones were allowed to form.

#### Trial 5

As in the recent trials, the team added dry sand to the empty reactor and then filled the reactor with water. During trial 5 the same flow rate was used as for trials three and four.

Up to trial 5, the water had successfully flowed from the outlets of the reactor without sand exiting, though the issue with air bubbles lodged between the branches of the reactor remained. The air bubble would move when different holes were blocked. The team hypothesized that this problem was caused by the pressure within the reactor caused by the lid that had been placed on top. In addition, the team presumed that when sand did exit, it was due to a pressure differential caused in that moment by blocking part of the exit. The team considered the fact that in an AguaClara plant, the filter is open to the atmosphere, and as a result decided to remove the lid from the reactor, leaving the top open. The hope was that eliminating the lid would eliminate the air bubbles. This proved to be correct as will be discussed in the next section.

#### Trial 6
The main goal for the sixth trial was to generate a system in which the extraction holes and filter were all submerged under water. This task was difficult for the team because there were no longer extraction tubes and it could not simply be submerged in water because of the sand and the need to regulate how much water was coming out.

The team thought of a small apparatus that would be added on to the current apparatus. It would be some kind of cup or box that would surround the extraction holes to be filled with water. Although it would be open at the top to the atmosphere for water to flow out, this technically would submerge the filter system with water and would fix the pressure differential issues between the three branches.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/Onshape6.png" width= "700"> </p>
<p align="center">
  Figure 6. The team's idea to enclose the filter holes; the shape here would be closed on the bottom and allow water to spill over the top.
</p>

### Experimental Apparatus Fabrication
#### Trial 1
In the previous semester, the team glued extraction tubes to the apparatus to begin to test design feasibility. Upon revisiting the idea, the team decided the outlet pipe size did not match a minimum inner diameter value.

| Respective Flow Rate      | Minimum Tube Inner Diameter  
|---------------------------|-----------------------|
| 36.67 milliliter / second | 3.762 millimeter      |

<p align="center">
Reference manual below for Python code calculations of these values. </p>

Glue had been used to connect the outlet "pipes" (tubing) to the reactor (the 4-inch diameter PVC pipe). To adjust the apparatus, after shaving the glue from the previous tubes, the team detached the tubes. Using the new calculated inner diameter, the team found tubing that met the minimum standard and considered its effect on the design of the 3D printed "pine-tree" filter which already fit to the prototype PVC tube by drilled holes. In the OnShape drawing, the team determined that if the filter was taken from the prototype, large enough holes could be drilled with the drill press without ruining the integrity of the model. The holes were designed to be offset from the original holes while still remaining in the bounds of the upper and lower wings. Holes were drilled to match these on the 4-Inch PVC prototype.

With three new outlet tubes of sufficient diameter glued water-tight, the team used two T-joint push-to-connect tubes to attach the outlet to a peristaltic pump of size 16 tubing. The inlet (lower cap) was tapped with push-to-connect that was attached to size 18 tubing in a peristaltic pump.

The team made the mistake of filling the apparatus with sand and then inverting so that exclusion zones could no longer form. In this trial, colored sand was chosen to closely monitor the escape of sand from the outlet tubes, but the dye colored the water, making it more difficult to see failure.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/InvertedApparatus.png" width= "350"> </p>
<p align="center">
  Figure 7. The colored sand filling the exclusion zones as the apparatus was inverted.
</p>


#### Trial 2
In the second trial, the team drained the water and sand from the prototype. To better simulate plant conditions, Monroe suggested that the team first fill the prototype with water, and add sand from the top. This would create sand exclusion zones initially which would be maintained during water flow through the filter.

Also, to prevent sand from falling into the injection tube, the team added metal mesh between the tube and the push-to-connect. Though these holes were small enough to prevent sand loss, they were large enough to not restrict flow.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/Trial2Water.JPG" width= "350"> </p>
<p align="center">
  Figure 8. Water filling the apparatus before the addition of sand.
</p>

Using newly calculated flow rates from the experimental design passage above, the apparatus was set up the same way as in the first trial, with detail in respect to the order of addition of sand and water. This also prevented the sand from entering the injection tubing because there was a constant water stream that made use of gravity exclusion. When the sand nearly filled the tube, the upper lid was secured and the extraction began.

#### Trial 3
This purpose of this trial was to test the feasibility of the intense newly calculated flow rate. Therefore, the team honed in on one filter wing outlet hole to analyze. The team used plugs at the push-to-connects in lieu of pump tubing to stop the flow from the upper two tubes.

Other than the use of only one extraction hole, the test was conducted in the same way as the earlier trials where the apparatus was filled with water and sand before extraction. After beginning extraction, the injection flow would remain until the water level was close to the opening of the filter outlet hole. The injection and extraction tubes were attached to two peristaltic pumps, set to their effective flow rates in RPM.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/Trial3SetUp.jpeg" width= "350"> </p>
<p align="center">
  Figure 9. Sand filling the apparatus before extraction.
</p>
#### Trial 4
<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/IMG_5276.JPG" width= "500"> </p>
<p align="center">
  Figure 10. The apparatus with a rubber cap and no extraction tubes. Note the formation of clean exclusion zones.
</p>

The apparatus was filled with water and then sand, then the cap was placed on while the water was still being pumped into the bottom. This initial pressure change of placing a cap on and forcing air into the apparatus and some sand out of the outlet. This suggested that this added pressure was an incorrect way of testing the filter.
#### Trial 5
As in the recent trial, the team added dry sand to the empty reactor and then filled the reactor with water. In contrast to previous trials, the team left the apparatus open to the atmosphere on top, leaving the lid off for the duration of experimentation.

#### Trial 6
To fabricate the cup shape that would generate the submerged system the team hoped, a 125 mL Nalgene sample bottle was cut in half to fit the side of the current apparatus and curved to generate a water-tight shape using the precision drill. The narrow top part of the bottle was also cut so that water could spill over the top. The team considered that the cup would have to cover all three of the outlet holes in choosing the use the bottle.

Using PVC-glue, the team secured the bottle half to the apparatus and tested for water-tightness before conducting experiments with it.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/Apparatus%20Design%206.jpeg" width= "500"> </p>
<p align="center">
  Figure 11. The apparatus with the designed half-cup being glued; note the open top and enclosed bottom to be filled with water during the trial.
</p>

### Feasibility of Design and Analysis
Before running the experiments, the team ensured that the prototype was watertight in order to collect accurate data regarding the flow rates of injection and extraction.

#### Trial 1

The initial mistake of inverting the apparatus was caused by a limitation in the team's understanding of how the design would form gravity exclusion zones. The lower of the three triangular partitions was able to form the strongest exclusion zone, which was in fact pulling water without sand.

This trial gave the team an indication of how to move on, but it should be noted that flow rates were not yet indicative of the Aguaclara filtration flow rates (of injection and extraction).

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/Trial1Filter.jpg" width= "350"> </p>
<p align="center">
  Figure 12. The exclusion zone on the lower structure forming.
</p>

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/Trial1Tubes.png" width= "350"> </p>
<p align="center">
  Figure 13. The extraction tubes pulling water without sand from the lower exclusion zone. Note the top tube was pulling sand from the most failed exclusion zone and the middle was pulling air.
</p>

#### Trial 2

The biggest issue with the second trial was that only the bottom tube pulled water out. This can be explained by a couple of possibilities. There was water leaking through the middle and top tubes, suggesting that they were not watertight and so they may have been pulling air only. The existence of air bubbles within the filter was also indication that there were flaws in this design.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/Trial2Filter.JPG" width= "350"> </p>
<p align="center">
  Figure 14. The filter extraction zones during the second trial. Note the air bubbles in between the layers.
</p>

The top tube did not have any sand in it and the exclusion zones did exist, in a sense which is an essential insight moving forward. This means that at least one of the gravity exclusion zones formed and was capable of operating at the necessary velocity without failure. In agreement with the first trial, the lowest of the three "branches" was successfully pulling water.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/Trial2Tubes.png" width= "450"> </p>
<p align="center">
  Figure 15. The extraction tubes during the second trial.
</p>

#### Trial 3
In the third trial, the team discovered a very promising result. The extraction pump could pull water out of one layer of the filter without sand in the output. The minimum failure velocity of the exclusion zones, although not yet found, should be greater than the maximum flow rate out of the filter in true AguaClara plants.

Although this information is exciting for the team, this trial did not use all three exclusion zones that the original design intended. The optimized filter would pull water from all three of the outlet tubes.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/ExclusionZonesTrial3.PNG" width= "450"> </p>
<p align="center">
  Figure 16. The exclusion zones during the third trial.
</p>

The air bubbles persisted in the upper two partitions that were plugged. The next move for the team would be to take steps to understand more about the pressure differential in the apparatus and determine a different way to extract from the filters, because the air bubble problem does not resolve during experimentation.

Another persistent issue was the availability of pumps that function at a flow rate as high as the system needs. Also, in the AguaClara filters, there are not electric pumps that pull water from the filter, the effluent rate is determined by the rate of water going in and gravity, which is the beauty of the gravity powered system.

#### Trial 4
This trial solved some problems from Trial 3. It was confirmed that only one pump is necessary to pump water in from the bottom, and the air bubble issue presented itself in a different way. This time, the water level fell to just above the bottom hole, so instead of bubbles there was no water in those branches at all. This suggested a deeper issue with the system because of pressure differences between the three branches.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/NoExtractionTubes.png" width= "350"> </p>
<p align="center">
  Figure 17. The apparatus without extraction tubes, filled with water that does not exit the system due to pressure differential.
</p>

#### Trial 5
The new apparatus set-up proved successful in dislodging the air bubbles that had previously caused concern. The set up for Trial 5 remained effective in preventing sand from exiting. The new set-up did cause a new issue. Once the tank filled to a point above all outlets (with outlets blocked during filling), the water level would drop and exit solely through the bottom most outlet.

The team suspected that this exit issue was due again to a pressure differential, which led to the idea of submerging the outlets, as will be discussed in trial 6.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/Trial5Photo.png" width= "350"> </p>
<p align="center">
  Figure 18. Water freely flowing form the lowest outlet hole.
</p>

#### Trial 6
Trial 6 was incredibly successful for the progress of this project. The submerged system worked seamlessly, and it was the most authentic model of true AguaClara filter thus far. The team conducted an initial test to see that the cup design would suffice, and, after proving its success, ran the trial at steady state for 30 minutes. This proved that the system could consistently pull water from the exclusion zones without sand also escaping.

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/CupFlowScreenshot.png" width= "300"> </p>
<p align="center">
  Figure 19. Water, without sand, coming from the outlet cup covering the outlet holes. Note, the water level slightly above the cup, which was unaffected in the long term.
</p>


## Conclusions

The spring of 2019 team discovered through experimentation that given all design parameters, it is possible for the stacked rapid filter with injection and extraction to run without allowing sand to escape through the outlets.

Testing the apparatus with sand and water running at filtration speeds made the flaws in the apparatus used for experimentation clear, and the team was able to adapt the apparatus to overcome the initial concerns. The spring of 2019 trials showed that the "Christmas tree" design can handle very high filtration speeds without failure. The second trial showed that the bottom branch of the filter can handle high velocities of filtration without sand leaving in the outlet pipes, which is encouraging for predicting the success of this design. The third trial stands to show the strength of the exclusion zones that are formed by this design. The fourth, fifth, and sixth trials have progressed to better simulate AguaClara plants. The experiments have repeatedly shown that at the very least, the design will not fail even at forward filtration speeds that are much faster than predicted. Because of the pressure issues that the team has found with the apparatus failures, there have been many tests where all of the water comes out of one outlet branch. This is a problem in testing the whole design, but at the same time, it shows that each branch can handle a filtration speed three times faster than it needs to. This large range of filtration speed is encouraging as the team considers testing the branched design at Cornell's water treatment plant.

## Future Work
Based on the trials completed in the spring of 2019, the next steps will require moving forward to implement this design in a real, full-scale AguaClara plant.

The future team must first establish methods to fabricate the 3D printed shelves on a larger scale. After establishing a new apparatus, the large scale system must be tested in Cornell's water treatment plant before the design enters large-scale production and implementation in AguaClara plants. It is an exciting time for StaRS FInE.

# Manual
## ProCoDa

The ProCoDa used thus far in the semester has been limited to making sure the input and output peristaltic pumps are running at the correct flow rates for their tube size. The team has not yet run an extended experiment regulated by ProCoDa. Using some of the pre-made Aguaclara packages, flow rate and fluid mechanic calculations are made easier for teams in lab.

For the peristaltic pump regulation calculations, the states were as follows.

### States

<p align="center"> <img
src="https://raw.githubusercontent.com/AguaClara/StaRSFine/master/Images/PCD4.PNG" width= "500"> </p>
<p align="center">
  Figure 20. The list of ProCoDa set points used in experimentation.
</p>

#### OFF
The off state was used whenever the team was not experimenting. Because the team only used ProCoDa for calculations, rather than collecting data, these states were not used often.

#### INJECT
The INJECT state used the set points *Just Water Flow* and *Water Tubing Size* to take into account the inlet flow rate in mL/s and the tubing size from inlet the peristaltic pump. As demonstrated above in figure ____, the *Just Water Pump* state outputs the value in revolutions per minute (RPM) divided by 100.

#### EXTRACT
The EXTRACT state used the set points *Outlet Flow* and *Outlet Tubing Size* to take into account the outlet flow rate in mL/s and the tubing size from the outlet peristaltic pump.*Outlet Pump*, used in the first three trials only, was setting the outlet flow rate for the peristaltic pump.



## Python Code
### Variables
$area$ : area of the sand bed

$areamm$ : area in mm

$backwashvelocity$ : velocity of water in the backwash stream

$filterflow$ : Minimum flow rate of the water

$headloss$ : Headloss

$temp$ : Temperature of operation

$\nu$ : Kinematic Viscosity of water based on temperature

$piperough$ : k, pipe roughness

$diamtube$ : tube diameter

### Trial 1 Code
```Python
#This code was used for trials. The error in this code was in the line below assuming that the extraction flow rate would be divided by two.
import math
import numpy as np
import pandas as pd
from aguaclara.core.units import unit_registry as u
from aguaclara.core import pipes as pipe
from aguaclara.core import physchem as pc
from aguaclara.core import utility as ut
import aguaclara.design.floc as floc
from aguaclara.research import floc_model as fm

area = 100*u.cm**2
#area of the filter bed for simulations
areamm = area.to(u.mm**2)
backwashvelocity = 11*u.mm/u.s
filterflow = (backwashvelocity*areamm*2)/6
#filterflow is the flow rate of water coming out of each filter
print(filterflow.to(u.ml/u.s))
injectionflow = filterflow*6
#injectionflow is the rate at which the water would come through the filter (all six layers that would be in an aguaclara plant)
print(injectionflow.to(u.ml/u.s))
extractionflow = filterflow*2
#extractionflow is the flow rate at which the team will extract water from the filter because water is coming from above and below the filter
print(extractionflow.to(u.ml/u.s))

headloss = 1*u.m
Length = 1*u.m
temp = 20*u.degC
Nu = pc.viscosity_kinematic(temp)
PipeRough = 0.1*u.mm
KMinor = 2
#to find the diameter of tube for the three tubes that will come out of our filter
diamtube = chem.diam_pipe((filterflow/3), headloss, Length, Nu, PipeRough, KMinor)
print(diamtube.to(u.mm)) #inner diameter of tube we would like to come out

#The below code was revised for trial 3
v_filtration = 11 * u.mm/u.s
#this is the velocity we want to use for extraction of water during the filtration process
N_outlets = 3
#our apparatus has 3 outlet holes
lengthfilter = 10 * u.cm
#the filter has a general cross sectional area of 100
Q_outlet = (v_filtration*lengthfilter**2/(2*N_outlets)).to(u.mL/u.s)
#the error was in multiplying the N_outlets by two
print('The flow rate through one filter outlet is', ut.round_sf(Q_outlet,2))
```

### Trial 2-6 Code
```Python
#This code was used for trials 2 through 6
import math
import numpy as np
import pandas as pd
from aguaclara.core.units import unit_registry as u
from aguaclara.core import pipes as pipe
from aguaclara.core import physchem as pc
from aguaclara.core import utility as ut
import aguaclara.design.floc as floc
from aguaclara.research import floc_model as fm

area = 100*u.cm**2
#area of the filter bed for simulations
areamm = area.to(u.mm**2)
backwashvelocity = 11*u.mm/u.s
filterflow = (backwashvelocity*areamm*2)/6
#filterflow is the flow rate of water coming out of each filter
print(filterflow.to(u.ml/u.s))
injectionflow = filterflow*6
#injectionflow is the rate at which the water would come through the filter (all six layers that would be in an aguaclara plant)
print(injectionflow.to(u.ml/u.s))
extractionflow = filterflow*2
#extractionflow is the flow rate at which the team will extract water from the filter because water is coming from above and below the filter
print(extractionflow.to(u.ml/u.s))

headloss = 1*u.m
Length = 1*u.m
temp = 20*u.degC
Nu = pc.viscosity_kinematic(temp)
PipeRough = 0.1*u.mm
KMinor = 2
#to find the diameter of tube for the three tubes that will come out of our filter
diamtube = chem.diam_pipe((filterflow/3), headloss, Length, Nu, PipeRough, KMinor)
print(diamtube.to(u.mm)) #inner diameter of tube we would like to come out

v_filtration = 11 * u.mm/u.s
#this is the velocity we want to use for extraction of water during the filtration process
N_outlets = 3
#our apparatus has 3 outlet holes
lengthfilter = 10 * u.cm
#the filter has a general cross sectional area of 100
Q_outlet = (v_filtration*lengthfilter**2/N_outlets).to(u.mL/u.s)
print('The flow rate through one filter outlet is', ut.round_sf(Q_outlet,2))

#This portion of the code demonstrates the peristaltic pump abilities
tubing18 = 3.8 * u.mL/u.revolution
Maxspeed = 600 * u.revolution/u.min
Q_pump_max = (Maxspeed * tubing18).to(u.mL/u.s)
print('The max flow rate with one peristaltic pump is', ut.round_sf(Q_pump_max,2))
#What is the max flow from a peristaltic pump with #18 tubing at 600 rpm?
```
## Onshape
Link to the full design:
https://cad.onshape.com/documents/2e536bd8940f20fc75058241/w/42817f17b88f823e779070ce/e/a78ef9a6ae52e13f92aed459?configuration=Angle%3D0.3839724354387525%2Bradian%3BList_NCIYbvAAUq0uK3%3DDefault%3BNumber%3D3.0%3BRadius%3D0.012700000000000001%2Bmeter%3BSpacing%3D0.01905%2Bmeter%3BThickness%3D0.0031750000000000003%2Bmeter%3Bdepth%3D0.10160000000000001%2Bmeter%3Blength%3D0.03429000000000001%2Bmeter

## Materials List
* 4-inch PVC pipe (obtained from available lab materials)
* 3-D printed "Chrismas tree" (printed by Paul)
* Sand (obtained from available lab materials)
* Distilled water from the blue line (available in lab)
* Peristaltic pump Tubing, size 18 (available in lab)
* Tubing used in apparatus (available lab materials)
* Peristaltic Pumps 100-600 RPM
* PVC Glue
* Nalgene 125 mL bottle (available in lab)
