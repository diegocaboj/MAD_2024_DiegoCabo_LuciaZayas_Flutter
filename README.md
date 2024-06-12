PARKFINDER FLUTTER VERSION!  WorkSpace  
Github:

•	Repository: [https://github.com/diegocaboj/MAD2024_DiegoCabo_LuciaZayas](https://github.com/diegocaboj/MAD_2024_DiegoCabo_LuciaZayas_Flutter)

•	Releases: [https://github.com/diegocaboj/MAD2024_DiegoCabo_LuciaZayas/releases](https://github.com/diegocaboj/MAD_2024_DiegoCabo_LuciaZayas_Flutter/releases)

Workspace: [https://upm365.sharepoint.com/sites/MobileAppDevelopment_DiegoCabo_LuciaZayas/SitePages/CollabHome.aspx](https://upm365.sharepoint.com/sites/MobileAppDevelopment_DiegoCabo_LuciaZayas/SitePages/Tracking.aspx)

Description:  
ParkFinder is an application that has numerous posibilities. The application consists of a login where you must indicate an email and password, and once inside the application, there is the possibility to view the credentials in the settings screen. In ParkFinder, you can see on a map both your location and the parking lots in Madrid, view information about them, and there is a system to give feedback with a star system and also text, and read the feedback from other users. You can also see which parking lots are near your location in addition to making queries without needing to have the location active to know which parking lots are at the distance you want from the coordinate you want. Finally, ParkFinder has a system that shows your previous locations and it leaves you the possibility of deleting them as well as seeing them. 

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

Features  

Functional Features  
Parking Information Display:  
The application fetches and displays a list of parking spots with detailed information, including address, postal code, organization description, and geographical coordinates (latitude and longitude).  

User Feedback:  
Users can provide feedback on specific parking spots. This includes entering comments and giving a rating (1 to 5 stars).  
The feedback is stored in Firebase Realtime Database and can be retrieved and displayed within the app.  

Location Tracking:  
The app tracks the user's location using the Geolocator package. This information can be used to filter parking spots based on proximity.  
Geolocation-Based Features:  

Users can enable or disable location tracking through a switch in the UI.  
The app requests necessary location permissions from the user.  

Interactive UI Elements:  
Includes buttons and pop-up menus for navigation and additional options.  
Feedback entries can be interacted with through long-press gestures, allowing users to update or delete their feedback.  

Persistent Data Storage:  
The app uses SharedPreferences to store and retrieve user-specific data such as API tokens.  


Technical Features  

Flutter Framework:  
The app is built using Flutter, which allows for a single codebase to run on both Android and iOS platforms.  

Firebase Integration:
Utilizes Firebase Authentication for user authentication.  
Firebase Realtime Database is used to store and retrieve user feedback data.  

Geolocation:  
The Geolocator package is used to access and track the user's location with high accuracy.  
Location data is periodically saved to a CSV file and displayed in the UI.  

API Interaction:  
The app fetches parking information through HTTP requests using an external API service.  

Real-Time Data Updates:  
Implements real-time updates for feedback using Firebase's onValue listener.  

Error Handling:  
Comprehensive error handling for various operations like network requests, Firebase interactions, and geolocation services.  

UI/UX Design:  
Modern Material Design components for a clean and intuitive user interface.  
Uses various widgets like ListView, StreamBuilder, TextFormField, and SnackBar for a responsive and interactive user experience.
