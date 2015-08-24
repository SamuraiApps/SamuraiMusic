# SamuraiMusic
README
SamuraiMusic's goal is to be a cloud-based collaberative platform for musicians and sound people to work together remotely on music projects.  

Goals for the project include:
  The ability for user's to work off of other user's ideas
  The ability to version different versions of the same songs
  The ability to put the raw multi-tracked content available for global collaberation
  Changes to songs should be saved to a cloud environment without user input
  
Rudementary Architecture:
  The structure of the application will have 3 main components.  They are as follows:

Endpoint Apps
-------------------------------------------------------------------------------
  Endpoint platforms will have an app or application interface that will be where the user interacts with the service.  Likely each relevent hardware/vendor platform will require it's own app (Windows, Android, IOS, etc...)  Android will be the introductory platform.  The app will have multiple screens/activities, the requirements for which, will be outlined in other places.

Middleware
-------------------------------------------------------------------------------
  The app will read information from webservices which will serve as basically middleware for the app which will be responsible for processing user requests, and for fulfilling requests from the service.

Database/Storage
-------------------------------------------------------------------------------
  The data will be stored in and retrieved from a Mongo database.  The structure of which has yet to be determined.
