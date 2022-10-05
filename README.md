# AIS4SIA Alta Scuola Politecnica XVII Cycle Project

The AIS4SIA system collects data about the status 
of the vines and provides insightful information about 
the water stress of the plants that can be exploited to 
estimate and predict the yield trend of the vineyard for 
the upcoming harvest season.

The system is constituted by two main parts: the sensing 
modules collect information about the vines and the 
vineyard status, while a server analyzes the collected 
data, computes the **Crop Water Stress Index**(CWSI), 
and generates maps that can be used to monitor the 
current status of the vineyard in detail, as well as to 
make prediction about the future development of the 
grapes and the plants.

The sensing subsystem is composed of a series of 
fixed sensors along the rows of the vineyard. The 
fixed sensors measure: pressure, air temperature, 
air humidity, ultraviolet (UV) radiation, infrared (IR) 
radiation, and ambient light. A thermal 
camera detects instead the canopy temperatures of 
the leaves of the plants, which is an essential parameter 
for the computation of the CWSI. The collected data 
are transmitted to and stored in a server where ML 
algorithms fuse the information coming from all sensors.

The core feature of our system is the analysis of the 
on-field data: studies correlates the water stress 
(that can be monitored through the CWS) during 
each period fo the year with the ideal plant and grape 
growth for each specific grapevine. As a consequence, 
the proposed solution increases awareness of one of 
the main parameters affecting production quality and 
quantity, while also enabling a wise water management, 
and boosting plants care. Lastly, the elasticity of the 
proposed sensing system and of the software suite 
allows for an adaptive and always evolving solution.
