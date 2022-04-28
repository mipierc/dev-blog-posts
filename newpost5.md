## Dev Post 5

##### Author: Michael Pierce

###### Date: 29 March 2022

#### __Fire Drills__
Who knows how a product can break better than the people who built it? Fire drills are fictitious events based on scenarios that simulate real-world incidents. They allow validation of your response in the case of an incident and check whether the developers know how to react under various scenarios that may come up during an incident. To start, theoretical questions need to be asked, such as "What would happen if our database became corrupted?". The team of developers then has to identify all potential problems in the case of the incident and then suggest solutions for each. For each incident, the team should ask:

+ How would we know this situation is happening? Do we have
sufficient monitoring around the application to identify this as a
situation, and how would it manifest itself?
+ Do we know what the impact will be? Is there any temporary
mitigation we could put in place?
+ Do we know how to recover from this situation?
+ How likely is this situation to occur?

If the team is able to answer these questions for each scenario, the team will be able to identify improvements to the current system that can minimize downtime in the case of an incident. The team can also develop user stories to assist in the development of the solution. 

#### __Roles__
Think of a fire drill as a role-playing game. There need to be defined roles for each person involved. At a minimum, there should be a role for the game master and one for the on-call engineer. The game master is the person who is responsible for running the fire drill, and the on-call engineer is the person who is going to triage the incident. It is beneficial to have a variety of roles, such as:

+ Customers
+ Secondary on-call engineer
+ Managers
+ Service Desk

#### __Running a Fire Drill__
Now that the fire drill session has been developed, it should be driven by the guidelines developed earlier in the response in case of an incident. These fire drills should simulate a real scenario. The only difference should be that instead of interacting with the live systems, there should be a setup to simulate the incident. If using a communication tool like Microsoft Teams, the fire drill can be run in a separate channel or over a video chat. The on-call engineer will be responsible for requesting information from the game master, and each role will be responsible for completing what was defined for their role. It can also be extended to include a separate channel of communication for the team to convey information to the customer.
