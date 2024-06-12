PARKFINDER FLUTTER VERSION! 
WorkSpace   
Github:

•	Repository: [https://github.com/diegocaboj/MAD2024_DiegoCabo_LuciaZayas](https://github.com/diegocaboj/MAD_2024_DiegoCabo_LuciaZayas_Flutter)

•	Releases: [https://github.com/diegocaboj/MAD2024_DiegoCabo_LuciaZayas/releases](https://github.com/diegocaboj/MAD_2024_DiegoCabo_LuciaZayas_Flutter/releases)

Workspace: [https://upm365.sharepoint.com/sites/MobileAppDevelopment_DiegoCabo_LuciaZayas/SitePages/CollabHome.aspx](https://upm365.sharepoint.com/sites/MobileAppDevelopment_DiegoCabo_LuciaZayas/SitePages/CollabHome.aspx)  
[Tracking in Sharepoint](https://upm365.sharepoint.com/sites/MobileAppDevelopment_DiegoCabo_LuciaZayas/SitePages/Tracking.aspx)  

Description:  
ParkFinder is an application that has numerous posibilities. The application has a login where you must indicate an email and password, and once inside the application, there is the possibility to view the credentials in the settings screen. In ParkFinder, you can see on a map both your location and the parking lots in Madrid, view information about them, and there is a system to give feedback with a star system and also text, and read the feedback from other users. You can also see which parking lots are near your location in addition to making queries without needing to have the location active to know which parking lots are at the distance you want from the coordinate you want. Finally, ParkFinder has a system that shows your previous locations and it leaves you the possibility of deleting them as well as seeing them. 

Screenshots and navigation  
[Complete Folder](images)   
[Screenshot1](images/Flutter1.JPG)     
[Screenshot2](images/Flutter2.JPG)    
[Screenshot3](images/Flutter3.JPG)    
[Screenshot4](images/Flutter4.JPG)    
[Screenshot5](images/Flutter5.JPG)  
[Screenshot6](images/Flutter6.JPG)    
[Screenshot7](images/Flutter7.JPG)    
[Screenshots8](images/Flutter8.JPG)    
[Screenshots9](images/Flutter9.JPG)    
[Screenshots10](images/Flutter10.JPG)    
[Screenshots11](images/Flutter11.JPG)    
[Screenshots12](images/Flutter12.JPG)    
[Screenshots13](images/Flutter13.JPG)    
[Screenshots14](images/Flutter14.JPG)    
[Screenshots15](images/Flutter15.JPG)    
[Screenshots16](images/Flutter16.JPG)    
[Screenshots17](images/Flutter17.JPG)   
[Screenshots18](images/Flutter18.JPG)    
[Screenshots19](images/Flutter19.JPG)    
[Screenshots20](images/Flutter20.JPG)    
[Screenshots21](images/Flutter21.JPG)  
[Screenshots22](images/Flutter22.JPG)  
[Screenshots23](images/Flutter23.JPG)  
[Screenshots24](images/Flutter24.JPG)  
[Screenshots25](images/Flutter25.JPG)  
[Screenshots26](images/Flutter26.JPG)  
[Screenshots27](images/Flutter27.JPG)  
[Screenshots28](images/Flutter28.JPG)  
[Screenshots29](images/Flutter29.JPG) 

Demo Video:  
[Video](https://upm365.sharepoint.com/:v:/s/MobileAppDevelopment_DiegoCabo_LuciaZayas/EXwcaUqy9MxCpCtg10OOQhcBMXkvus8zilAYcUs1DaJCGA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=rzXwbC)  




FEATURES  
FUNCTIONAL FEATURES    
Parking Information Display:  
ParkFinder fetches and displays a list of parking spots with detailed information, including address, postal code, organization description, latitude and longitude.  

User Feedback:  
Users can provide feedback on specific parking spots of Madrid. This includes entering comments and giving a rating (1 to 5 stars).  
The feedback is stored in Firebase Realtime Database and can be retrieved and displayed within the app.  

Location Tracking:  
ParkFinder tracks the user's location using the Geolocator package. This information can be used to filter parking spots based on proximity.  

Geolocation-Based Features:  
Users can enable or disable location tracking through a switch in the home screen.  

Interactive UI Elements:    
Feedback entries can be interacted with through long-press gestures, allowing users to update or delete their feedback.  

Persistent Data Storage:  
PArkFinder uses SharedPreferences to store and retrieve user-specific data.  


TECHNICAL FEATURES  

Firebase Integration:  
the app uses Firebase Authentication for user authentication and to store and retrieve user feedback data.   

Geolocation:  
The Geolocator package is used to access and track the user's location.  
Location data is periodically saved to a CSV file and displayed in the UI.  

API Interaction:  
The app fetches parking information through HTTP requests using an external API service.  

Real-Time Data Updates:  
Implements real-time updates for feedback using Firebase's onValue listener.  

HOW TO USE
1. Login 
You have to introduce your email and your password. If you don't have account you can use the account with the email x@hotmail.com and the password 123456.

2. Navigation  
The collection screen displays a list of available parking spots.  
Tap on a parking spot to view more details.  

3. Providing Feedback
Access Feedback:
Select a parking spot and go to the feedback section.
Enter Feedback:  
Add your comments in the text field and select a rating from 1 to 5 stars.  
Submit Feedback:  
Tap "Submit Feedback" to send your review.
 
4. Viewing and Updating Feedback  
View Feedback:  
Feedback from other users is displayed under each parking spot.  
Update/Delete Feedback:  
Long-press your feedback entry to update or delete it.

5. Location-Based Services  
Enable Location Tracking:  
Allow location permissions when prompted.  
Find Nearby Spots:  
Use the "Near Me" option to see  nearby parking spots (600 meters from you).  
Custom Location:  
Enter manually latitude, longitude, and distance in the "Filter by" option to see which parking lots are in these distance in meters.

6. Map View     
Tap the map view to see parking spots on a map.  

7. Logging Out  
Go to the app menu and select the logout option in settings to log out.

Participants  
List of MAD developers:  

Diego Cabo Jurado (d.cabo@alumnos.upm.es)   
Lucía Zayas Martin (lucia.zayas@alumnos.upm.es)  
Workload distribution(50%/50%)  

Releases: [https://github.com/diegocaboj/MAD_2024_DiegoCabo_LuciaZayas_Flutter/releases](https://github.com/diegocaboj/MAD_2024_DiegoCabo_LuciaZayas_Flutter/releases)

 

