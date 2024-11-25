# Requirements

## User Needs

### User stories
TODO: Write brief user stories to explain how various actors would interact with the system to accomplish a goal.
    Express these in the form from agile development:- As a (role) I want (goal) so that (benefit).

### Actors
TODO: List and describe the actors/users for this product.

### Use Cases
TODO: Describe each use case (at least one per team member).
    Give each use case a unique ID, e.g. UC1, UC2, ...
    Summarise these using the use-case template below.

| TODO: USE-CASE ID e.g. UC1, UC2, ... | TODO: USE-CASE NAME | 
| -------------------------------------- | ------------------- |
| **Description** | TODO: Goal to be achieved by use case and sources for requirement |
| **Actors** | TODO: List of actors involved in use case |
| **Assumptions** | TODO: Pre/post-conditions if any</td></tr>
| **Steps** | TODO: Interactions between actors and system necessary to achieve goal |
| **Variations** | TODO: OPTIONAL - Any variations in the steps of a use case |
| **Non-functional** | TODO: OPTIONAL - List of non-functional requirements that the use case must meet. |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |

| USE –CASE 1 | BUSINESS OWNER |  

| -------------------------------------- | ------------------- | 

| **Description** | A business owner seeks to identify neighborhoods or areas with high foot traffic while ensuring safety from high crime rates to maximize customer visits and protect the business’s reputation. | 

| **Actors** | - Primary Actor: Business Owner | 

| | - Supporting Actors: Local Police Department (for crime data), Traffic Monitoring System, Commercial Real Estate Agents, Local Government (for zoning and safety regulations) | 

| **Assumptions** | The business owner has access to local crime data and traffic statistics. | 

| | - The real estate database or mapping service provides accurate information on foot traffic and safety in different areas. | 

| | - Data sources are up-to-date. </td></tr> | 

| **Steps** | 1. The business owner defines the criteria for a "high-traffic" area (e.g., busy streets, proximity to schools, parks, or other commercial centers). | 

||2. The business owner reviews available crime data for these areas. | 

||3. The business owner identifies high-traffic areas with low crime rates. | 

||4. The business owner compares rent/prices and availability of properties in those areas. |  

||5. The business owner selects the most suitable area for opening a business based on the combined factors of safety and foot traffic. | 

| **Variations** | 1. The business owner finds no suitable areas with both high traffic and low crime, requiring a reassessment of business location priorities. | 

||2. If crime data is unavailable or outdated, the owner may have to rely on local perceptions or anecdotal information. | 

| **Non-functional** | - Performance: Data sources should be updated regularly, with real-time crime and traffic data accessible to the business owner. | 

| | - Usability: The interface for reviewing crime and traffic data should be user-friendly. | 

| | - Security: Business owner data and property search information should be securely stored. | 

| **Issues** | - Inaccurate or outdated crime data could lead to incorrect decisions about location. | 

| | - High-traffic areas may come with higher property costs, which may not align with the business owner's budget. | 

| | - Local crime spikes (e.g., temporary) may not be reflected in crime data. | 

| USE-CASE 2 | PEDESTRIAN |  
| -------------------------------------- | ------------------- | 
| **Description** | A pedestrian wants to access real-time data about pedestrian-related crime in areas they frequently walk in order to make informed decisions about which| areas are the safest to walk through. | 
| **Actors** | - Primary Actor: Pedestrian (User)  |
| |- Supporting Actors: Local Law Enforcement (providing crime data), Mobile App or Website Interface (delivers crime data to the pedestrian), Data Aggregation System |(collects and compiles data) | 
| **Assumptions** | - The pedestrian has access to a device (smartphone, computer) that can access crime data.|  
||- Crime data is up-to-date, accurate, and available for the areas the pedestrian frequents.|  
||- The pedestrian knows how to use the app or website interface. </td></tr> 
| **Steps** | 1. Pedestrian opens a mobile app or website that provides crime data.  |
||2. Pedestrian enters or selects their frequently walked areas (e.g., home, work, park).  |
||3. The system retrieves and displays crime data for pedestrian-related crimes in those areas.  |
||4. Pedestrian reviews the crime data, which may include types of crimes, frequency, and trends over time.  |
||5. Pedestrian decides on the safest routes or areas based on the information provided. | 
| **Variations** | 1. If the pedestrian is in a new area, the app may suggest nearby areas with the least pedestrian-related crime based on the data available.  |
||2. If there’s no recent data for a specific area, the app may display a warning or prompt the pedestrian to check again later. | 
| **Non-functional** | - Performance: The app or website should load crime data within 3 seconds.  |
||- Usability: The user interface must be intuitive and easy to navigate for pedestrians of all ages.  |
||- Accessibility: The app/website should be accessible to people with disabilities (e.g., text-to-speech for vision-impaired users). | 
| **Issues** | - Limited community engagement or resistance to policing initiatives could hinder program effectiveness.  |
||- Budget constraints could limit the number of officers available for community patrols.  |
||- Inconsistent crime data or lack of updated information could lead to ineffective deployment of resources. | 


TODO: Your Use-Case diagram should include all use-cases.

![Insert your Use-Case Diagram Here](images/use-case.png)

## Software Requirements Specification
### Functional requirements
TODO: create a list of functional requirements. 
    e.g. "The system shall ..."
    Give each functional requirement a unique ID. e.g. FR1, FR2, ...
    Indicate which UC the requirement comes from.


### Non-Functional Requirements
TODO: Consider one or more [quality attributes](https://en.wikipedia.org/wiki/ISO/IEC_9126) to suggest a small number of non-functional requirements.
Give each non-functional requirement a unique ID. e.g. NFR1, NFR2, ...

Indicate which UC the requirement comes from.
