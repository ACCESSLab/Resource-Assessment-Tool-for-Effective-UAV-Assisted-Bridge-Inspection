# Resource-Assessment-Tool-for-Effective-UAV-Assisted-Bridge-Inspection

In this study, a resource estimation tool that can be used to estimate the resources required for UAS-assisted bridge inspections is developed. The tool can aid inspectors in determining the estimated flight time and resources required for using a specific UAS and operator during inspection of a specific bridge. The tool supports the development of optimal flight paths based on the structural geometry and positioning of structural elements of a bridge, establishes a range of recommended flight speeds for conducting reliable UAS-assisted bridge inspections based on the skill level(s) of the pilot(s) involved in the conduct of inspections, and establishes a recommended range of wind speed and the corresponding standoff clearance information for safely conducting the UAS- assisted bridge inspections. The tool also provides an estimated number of batteries required to allow the estimated required flight time.

=====================================================================================================================================
Tool Inputs:

Following are the inputs that comprise the Inspection Plan, Bridge Dynamics, and Pilot Skill-Based Flight Speed Range are required for the estimations. Units are mentioned for each input. One of the pilot skill levels should be selected from the three provided options.

Inspection Plan:

# of Vertical Flights
# of Horizontal Flights
# of Longitudinal Flights
# of Isolated Elements
Error Factor (%)
Adjustment Time	(/sec)
Flight Speed (mph)


Bridge Characteristics:			

Heigh of Vertical Element		    /ft
Length of Horizontal Element		/ft
Length of Longitudinal Element	/ft
Length of Grade Beam			      /ft
Width of Deck				            /ft
Length of Deck				          /ft
Number of Spans		
Inspection Time of Isolated Element		

UAV Characteristics:		

Flight time /battery	/min
Time /battery swap		/min

Flight Speed Range Based on Pilot’s Skill Level

Basic		      1.00 - 1.75		mph
Intermediate	1.75 - 2.30		mph
Professional	2.30 - 3.00		mph

=====================================================================================================================================

Tool Outputs:

The tool provides the estimation of the flights in minutes across vertical, horizontal, longitudinal, isolated and per span.

Time for Total Vertical Flights	    (min)
Time for Total Horizontal Flights   (min)
Time for Total Longitudinal Flights (min)
Time for Total Isolated Flights	    (min)

Flight Time Per Span (min)

Based on the flight time per battery, battery swap time and pilot skill level, the tool provides the estimate of the total inspection time and the number of batteries that would be required to complete the whole data collection process for the bridge under inspection.
Total Bridge Inspection Time (min) and converted into hours
		
Number of Batteries (#)		
		




