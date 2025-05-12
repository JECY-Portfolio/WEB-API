# WEB-API
A Web API (**Application Programming Interface**) is a set of rules that allows different software systems to communicate over the internet using standard protocols like HTTP. 
In simple terms, it allows different applications to talk to each other online. It lets one application send and receive data from another, often in formats like JSON or XML.

# Example: 
A weather app uses a Web API to fetch real-time weather data from a remote server like OpenWeatherMap. This helps the app provide accurate and up-to-date information without collecting the data itself.

#  3 APPS THAT I USE AND THE API THEY MIGHT BE USING
1) SPOTIFY
2) GOOGLE MAPS
3) TRUECALLER
______________________________________________________________________________________________________________________________________________________________________________________________________________
**SPOTIFY: **
Spotify is a leading music streaming platform offering access to a vast library of songs, podcasts, and playlists. It provides both free and premium subscription models, allowing users to stream music across various devices.

**KEY APIs USED BY SPOTIFY: **
1.	Spotify Web API: This RESTful API allows developers to access Spotify's music catalog, manage user libraries, and control playback. It provides endpoints to retrieve information about tracks, albums, artists, and playlists, as well as to manage user data and playback sessions. 
2.	Web Playback SDK: This JavaScript library enables developers to create a Spotify Connect device in the browser, allowing for seamless playback of Spotify content within web applications. It supports features like track control, volume adjustment, and metadata retrieval. Spotify for Developers
3.	Ads API: The Ads API allows Spotify to manage and report on advertising campaigns within the platform. It provides endpoints for creating and managing campaigns, as well as retrieving performance metrics. Spotify for Developers
   
**RECENT CHANGES: **
In November 2024, Spotify updated its Web API, restricting access to certain endpoints for new applications and those in development. These changes include the deprecation of features like audio features, audio analysis, and recommendations, aiming to enhance platform security and control over data usage.

______________________________________________________________________________________________________________________________________________________________________________________________________________
**GOOGLE MAPS: **
Google Maps leverages the Google Maps Platform APIs, including:
•	Maps JavaScript API: Used for displaying interactive maps on websites and apps. It allows developers to embed fully functional maps that users can interact with by zooming, panning, and marking locations.
•	Directions API: This API calculates travel routes between two or more locations and provides detailed directions. It accounts for real-time traffic conditions and offers alternative routes.
•	Geolocation API: Used to determine the physical location of devices based on GPS, Wi-Fi, or other location-tracking technologies. It enables apps to provide location-based services like finding nearby places or tracking a user's movement.

These APIs are heavily used in mobile apps and websites for various location-based services, from navigation to local search.

______________________________________________________________________________________________________________________________________________________________________________________________________________
**TRUECALLER: **
Truecaller is a mobile application that offers caller identification, spam blocking, and contact management services. It leverages a vast database of phone numbers and user-contributed data to provide real-time information about incoming calls and messages.Truecaller

**APIs USED BY TRUECALLER: **
1.	Truecaller SDK: This SDK enables developers to integrate Truecaller’s phone number verification and user profile retrieval features into their applications. It allows for seamless user onboarding by leveraging Truecaller's existing user base for authentication without the need for OTPs. The SDK supports Android, iOS, and web platforms. (docs.truecaller.com)
2.	Verified Business API: This API provides businesses with the ability to display their verified caller ID on users' devices, enhancing trust and reducing the chances of calls being marked as spam. It includes features like generating access tokens and setting up webhooks for real-time updates. docs.truecaller.com
3.	TruecallerJS: An open-source JavaScript library that facilitates phone number lookups using the Truecaller API. It simplifies the process of retrieving phone number details in Node.js, JavaScript, and TypeScript applications. 
4.	TruecallerPy: A Python package that offers functionalities to interact with the Truecaller API. It supports operations like login, OTP verification, and phone number search, making it suitable for backend integrations. 

**RECENT CHANGES**
As of November 2024, Truecaller has updated its Web API, restricting access to certain endpoints for new applications and those in development. These changes include the deprecation of features like audio features, audio analysis, and recommendations, aiming to enhance platform security and control over data usage. 
