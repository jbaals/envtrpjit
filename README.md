# envtrpjit
The files contain two sets of 20 instances each for the bi-objective just-in-time truck routing problem (envTRP-JIT).
The first data set comprises instances with n=12 shipments and the second one instances with n=99 shipments. The instances are based on those for the Pollution Routing Problem by Bektaş and Laporte (2011) (original instances available on http://www.apollo.management.soton.ac.uk/prplib.htm).
For each instance the parameters are split into 8 tabular separated .txt-files, containing the following information:
•	demands.txt - the capacity demands at the different suppliers (kilogram),
•	loadCapacity.txt - the load capacity of the truck (kilogram),
•	numTrucks.txt - the number of trucks,
•	penalties.txt - the costs per time unit of earliness or tardiness (monetary units),
•	releaseDueDates.txt - the release dates (first column) and due dates (second column) for each shipment (minutes),
•	travelDistances.txt - the travel distances between the locations of the different shipments, the depot, and the OEM (meters),
•	travelTimes.txt - the travel times between the locations of the different shipments, the depot, and the OEM (minutes),
•	truckWeight.txt - the curb weight of the trucks (kilogram).

References:
Tolga Bektaş, Gilbert Laporte, The Pollution-Routing Problem, Transportation Research Part B: Methodological, Volume 45, Issue 8, 2011, Pages 1232-1250, https://doi.org/10.1016/j.trb.2011.02.004.

