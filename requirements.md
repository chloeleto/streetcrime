# Requirements

## User Needs

### User stories
- As a business owner I want to identify crime hotspots in an accessible way like an interactive map with up-to-date data. 

- As a pedestrian I want to determine the safest walking route for me to take according to the level of crime near me. 

- As a member of the local authorities, I want to gather more insights on crime in the area to obtain predictive safety data.
- 
### Actors
- Business & property owners  
- Pedestrians 
- Local authorities & council 

### Use Cases

| USE –CASE 1 | IDENTIFY CRIME HOTSPOTS |  
| -------------------------------------- | ------------------- | 
| **Description** | The user is able to view an interactive map which displays the crime levels of areas in Bristol, and can be filtered to show the most high-incident areas across the city. | 
| **Actors** | User | 
| **Assumptions** | - The user is able to navigate and interact with the map. | 
| | - The user has access to a device and network. | 
| | - Data source (OpenData Bristol) is up-to-date and system has access to this. </td></tr> | 
| **Steps** | 1. The user navigates to the website. | 
||2. The system loads the interactive map. | 
||3. The map displays crime levels for different areas in Bristol. | 
||4. The user interacts with the map (zooming, panning etc.). |  
||5. The user applies filters to view high-incident areas. | 
||6. The system updates the map based on the selected filters. |
||7. The user reviews the filtered crime data. |
| **Variations** | 1. User does not apply filters → The default crime data is displayed. | 
||2. User selects specific areas only → The system updates the map to show selected areas. | 
| **Non-functional** | - Performance: Data sources should be updated regularly, with real-time crime and traffic data accessible to the business owner. | 
| | - Usability: The interface for reviewing crime and traffic data should be user-friendly. | 
| | - Security: User data and property search information should be securely stored. | 
| **Issues** | - Inaccurate or outdated crime data could lead to incorrect decisions about location. | 
| | - Local crime spikes (e.g., temporary) may not be reflected in crime data. | 


| USE-CASE 2 | DETERMINE THE SAFEST WALKING ROUTE |  
| -------------------------------------- | ------------------- | 
| **Description** | Determine the safest walking route for a pedestrian to take according to the level of crime near them on the interactive map. | 
| **Actors** | User |
|| - Mobile App or Website Interface (delivers crime data to the pedestrian), Data Aggregation System (collects and compiles data) | 
| **Assumptions** | - The map and routing system function correctly.|  
||- Crime data is up-to-date, accurate, and available for the areas the pedestrian frequents.|  
||- The pedestrian knows how to use the app or website interface. </td></tr> 
| **Steps** | 1. User opens a mobile app or website that provides crime data.  |
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

| USE-CASE 3 | Gather insight for predictive safety data |  
| -------------------------------------- | ------------------- | 
| **Description** | Gather more insights on crime in the area to obtain predictive safety data. | 
| **Actors** | User | 
|| - Supporting Actors: Data Systems (crime databases, traffic systems) | 
| **Assumptions** | - The predictive analytics and data visualization tools are accurate and functional. |
|| - Crime data is integrated properly into the system. | 
| **Steps** | 1. The user navigates to the safety insights section of the website. | 
||2. The system loads the interactive graph displaying historical and predictive crime data. | 
||3. The user selects the area they want to analyze from the graph. | 
||4. The user chooses the type of predictive data they want to view. | 
||5. The interactive graph updates, displaying crime predictions for the selected area. | 
| **Variations** | 1. User adjusts graph settings → The system updates the graph dynamically based on new filters. | 
||2. Crime data is incomplete or unavailable → The system notifies the user and provides generalized predictions. | 
| **Non-functional** | - Performance: Real-time data analysis and monitoring of crime trends. | 
|| - Usability: The tools used for communication with the community (e.g., websites, apps, | | or hotlines) should be user-friendly and accessible. | 
|| - Scalability: The community policing program should be scalable to different neighborhoods with varying levels of crime. | 
| **Issues** | - Limited community engagement or resistance to policing initiatives could hinder program effectiveness. | 
|| - Predictive data may be based on outdated or incomplete information if crime data is delayed.. | 
|| - Predictions are based on models, and may not always account for sudden shifts in crime patterns..| 

TODO: Your Use-Case diagram should include all use-cases.

[Use cases](https://github.com/user-attachments/assets/fc3106e6-38c3-4c97-9e5d-5c50c251a592)


## Software Requirements Specification
### Functional requirements
- Crime data visualisation 

    - Users can view crime incidents on an interactive map, with the ability to filter data by crime type (e.g. burglary, theft, assault) and timeframe (daily, weekly or   monthly). The map should clearly highlight high-crime areas, helping users make informed decisions. 

- Localised crime data 

    - When users click on a specific area, the system provides detailed data for that location, such as crime rates, types of incidents, and any related trends. The system should also offer tailored safety advice based on the crime type (e.g., home security tips for burglary-prone areas). 

- Business-focused tools 

    - The platform should allow business owners to analyze crime patterns in specific areas to identify safe, high-traffic locations. It should provide insights on crime-related risks, such as theft or vandalism, and help businesses reduce their exposure through strategic decisions, including security investments and adjusted operating hours. 

- Real-time data integration 

    - The system must fetch and display real-time crime data from trusted sources (such as local police reports or government databases). It should ensure that the displayed information is always current, with frequent updates to reflect ongoing changes in crime patterns. 


### Non-Functional Requirements
- Performance and Scalability: 

    - The system should be able to handle a large volume of users and data without performance degradation. As user numbers increase, the platform should remain responsive and continue to provide quick access to crime data. 

- Security and Privacy: 

    - All personal data, such as user profiles or crime reports, must be securely stored and processed. The platform should comply with data protection regulations (e.g., GDPR) to safeguard user privacy and ensure sensitive information is handled appropriately. 

- Usability: 

    - The system should have an intuitive, user-friendly interface that is easy to navigate, even for individuals with limited technical knowledge. This includes clear map visualizations, simple search and filter options, and straightforward instructions to help users quickly access the information they need. 

- Data Accuracy and Integrity: 

    - The platform should only present accurate, up-to-date crime data sourced from reputable authorities. Mechanisms for verifying the reliability of data and flagging inaccuracies should be in place, ensuring that users receive correct and trustworthy information at all times. 

Indicate which UC the requirement comes from.
