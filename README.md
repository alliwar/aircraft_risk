**Minimize the Risk of Injuries and Fatalities:**

***How StellarSkies Should Enter the Domestic Flight Market***

by  Allison Ward, Anthony Mansion, and Rick Lataille for the Flatiron School

**Business Understanding**

StellarSkies is an established US-based company seeking to enter the domestic flight industry utilizing both commercial and private aircraft. They have a large budget and are willing to allocate their funds to the planes that will make the best investments long-term. They requested that we identify planes that will allow them to travel across the United States with the lowest risk.

**Source of Data**

Our initial data set was pulled from the National Transportation Safety Board’s (NTSB) Aviation Accident data set from 1962 to 2023. The data  contains information regarding civil aviation accidents and selected incidents in the United States and international waters.

**Important Features and Limitations of the Data**

The dataset used in this analysis was provided by The Flatiron School. It only shows planes in accidents; we do not know how many flights took place overall, so we cannot normalize our data. Additionally, it does not differentiate between hardware failures and pilot error.
Therefore, the scope of our analysis is limited. 

**Analysis**

Our analysis uses a metric of safety as the most important factor in determining which private and commercial jets to purchase. We utilized a variable "Major Injuries", calculated as a sum of total serious injuries and fatalities per event, as our guide.


The first part of our analysis identifies the type of plane StellarSkies should consider. Our analysis shows that single-engine and reciprocal-engine planes are the most dangerous.

Single engine airplanes accounted for 75% of major injuries between aircrafts in our dataset between 1-4 engines.


![Engine Types](https://github.com/alliwar/aircraft_risk/blob/main/Aviation%20Images/Screen%20Shot%202024-03-07%20at%205.19.33%20PM.png?raw=true)

Reciprocating engine planes accounted for 77% of major injuries between those listed as turbo fan, turbo propeller, turbo jet, turbo shaft, and electric engine planes.

![Engine Number](https://github.com/alliwar/aircraft_risk/blob/main/Aviation%20Images/Screen%20Shot%202024-03-07%20at%205.19.48%20PM.png?raw=true)

The second part in our analysis was an analysis of individual manufacturers.
Between total major injuries of Boeing, Airbus, and Embraer airlines, Boeing accounted for 85% of major injuries.

![Commercial](https://github.com/alliwar/aircraft_risk/blob/main/Aviation%20Images/Screen%20Shot%202024-03-07%20at%205.23.52%20PM.png?raw=true)

For smaller business jets, Textron accounted for 96% of major injuries, Bombardier accounted for 3% of major injuries between Textron, Bombardier, Gulfstream and Dassault airlines.

![Private](https://github.com/alliwar/aircraft_risk/blob/main/Aviation%20Images/Screen%20Shot%202024-03-07%20at%205.25.15%20PM.png?raw=true)

**Safety Considerations**

Next, we took into account variables that negatively impact safety, such as the schedule of operations.
Despite accounting for only 25% of the year, the months of June, July and August accounted for 36% of major injuries.

![Month](https://github.com/alliwar/aircraft_risk/blob/main/Aviation%20Images/Screen%20Shot%202024-03-07%20at%205.27.26%20PM.png?raw=true)

Incidents on Saturdays and Sundays accounted for 39% of major injuries during the week.

![Day](https://github.com/alliwar/aircraft_risk/blob/main/Aviation%20Images/Screen%20Shot%202024-03-07%20at%205.27.14%20PM.png?raw=true)

**Conclusion**

Our analysis reveals that:
1. Reciprocating engines and single-engine planes present the biggest risk of major injury and should be avoided.
2. Boeing, Cessna and Bombardier have worse safety records than Airbus, Embraer, Gulfstream and Dassault.
3. Lastly, summers and weekends are more dangerous and protocols should be set in place keeping this in mind.

**Recommendations**

We have put together four potential options for aircraft purchases keeping these recommendations in mind:


Commercial flights: 


1. Airbus A220: An established operator
(Est. Cost: $91.5mm)
2. Embraer E190–E2: A new entrant
(Est. Cost: ~$60mm)

Private Flights:
1. Dassault Falcon 2000LXS: For spacious luxury
(Est. Cost: ~$34mm)
2. Gulfstream G280: A smaller and lighter option (Est .Cost: $25mm)


An Interactive Dashboard:

 https://public.tableau.com/views/AircraftSafetyAnalysis_17097661480200/FinalDashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

