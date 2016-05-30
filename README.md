# Programming Project proposal (yet unnamed) Bob Oey

### Global description
For this project I intend to create a public transport (PT) assistance application. Current popular PT apps offer robust guidance, but lack in real-time assistance during the trip. This interaction gap is especially problematic for travellers unknown with the itinerary, such as tourists or simply people unknown with that specific route. Most notably, knowing when to prepare for leaving the vehicle or requesting a stop is often confusing. Real time PT data is available through the OpenOV api (http://openov.nl/) which already is essential for the user friendliness of modern day PT apps. Here I will empower environment-naive users with the comfort locals enjoy through their familiarity with their city by using their geolocation to track their PT vehicle and inform them of upcoming changes (e.g. Press Stop Now and exit your Tram # at the next stop).


### Minimum Viable Product (MVP)
Alerting the user of upcoming exit movements will be main novel feature and as such forms the basis of the MVP. Additional features may include informing the user of the next step of their itinerary including directions from their exit to continue their route (e.g. Wait 3 minutes at #CURRENT_STOP and get in #NEXT_VEHICLE **or** Cross the street to the stop in the other direction)


### Components

###### Route planning interface (From / To)

###### Map view to show route and current location

###### Live route view (overview of upcoming changes)

###### Background functionality (Notifications)


### Required data sets and APIs

###### Google Maps API
###### Google Maps Directions API
###### iOS Region Monitoring
###### OpenOV API

### Possible difficulties

###### Power consumption
Power consumption issues could arise from continuous location monitoring. I don't know yet what the most efficient way of tracking the user would be. Once a user has boarded a vehicle and has verified this (?) it could be enough to poll the OpenOV data for the vehicle's position, making location irrelevant except for checking purposes.