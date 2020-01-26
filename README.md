# monsoonmeasure
Inspiration
Water is a scarce and vital resource and it should be treated as such. One member of our group saw this firsthand, as he has lived through droughts in his hometown of San Francisco, CA. It is important, therefore, to conserve such a precious resource through any means possible. Gallons and gallons of water runs off of roofs every year, 0.63 gallons per square foot of roofing per inch of rain, in fact! We believe that if people knew how much water could be conserved in their home or business by implementing some sort of roof water collection system, people around the world could save much more of this important resource than it currently does and could improve quality of life for the entire human race.

What it does
monsoonmeasure uses the user's location or a user inputted address to locate the user's desired building. Then, using the building's attributes, the app identifies average annual rainfall in the area and calculates the building's roof's surface area to finally calculate the amount of rain water the user could gather yearly, just by utilizing the water falling on the user's roof. This app helps users plan water collection and puts perspective on how much water users can collect rather than pay for.

How we built it
We built monsoonmeasure through React Native using Expo. By using this platform, we made our application very portable and therefore monsoonmeasure can run on iOS, Android, and Web. This allows nearly internet connected device to be able to run our application and take advantage of this calculation. In addition to the the React Native platform, we used Google Cloud and Google Maps API to provide user location data and location autocomplete data. We also used OpenStreetMap API to identify building attributes/coordinates to calculate surface area.

Challenges we ran into
During the development of this application, we had to overcome MANY challenges. Our main challenges included:

Google Maps API implementation - We were struggling for some time to implement the map interface as a view within the application. This was the objective of our app so we had to make sure it was was robust and completely integrated within the app.
Google Maps autocomplete - After the Google Maps implementation, we were having trouble with address search autocompletion. After many tests and API adjustments based on Google documentation, we were able to implement autocompletion. We believed this was a crucial feature to the app since the app is focused for user convenience.
Latitude/Longitude Calculation - When we were coding our application, we had to account for the coordinates be given in degrees, radius of Earth, and the curvature of Earth. This was proven to be a very challenging obstacle since we had to account for all this factors while calculating various shaped roofs (after all, not all roofs are simple rectangles). This resulted in us having to implement multiplecomplex mathematical equations.
Accomplishments that we're proud of
Overall, we are proud of the concept and application we built. We want to bring awareness for how much water users could utilize and bring perspective on how much water we could save from just collecting rainwater.

