# Capstone 1 Proposal
## 1. What goal will your website be designed to achieve?
The main goal of my website is for users to track each game of bowling frame by frame and to share/compare their scores with other users on the website. Another goal of my website is for users to locate nearby bowling alleys.

## 2. What kind of users will visit your site? In other words, what is the demographic of your users?
Ultimately the main demographic of my users are bowlers, but it can be used for any user who wants to track their scores and locate a nearby bowling alley.

## 3. What data do you plan on using? You may have not picked your actual API yet, which is fine, just outline what kind of data you would like it to contain.
My application will utilize a search feature that many Map related APIs have. The feature will search for nearby bowling alleys within a given distance from an address entered/your location. I plan on either using the Google Maps API or the MapQuest API.
The app will also use its own API containing data of users and user scores.

## 4. In brief, outline your approach to creating your project (knowing that you may not know everything in advance and that these details might change later). Answer questions like the ones below, but feel free to add more information:

#### a. What does your database schema look like?
The bowling tracker API will consist of 3 tables: __bowlers, games, and bowler_scores__.
#### b. What kinds of issues might you run into with your API?
	
#### c. Is there any sensitive information you need to secure?
My app will store user accounts so passwords will need to be secure.
#### d. What functionality will your app include?
Basic functionality will be tracking each frame of a bowling game by number of pin fall, spare, or strike. Locating bowling alleys will also be another functionality.
#### e. What will the user flow look like?
On the home page, the user would first see a description of the web app, as well as forms
for login and sign up. It will also display a leadership dashboard with the top games. There will be a navigation bar with links: Home, Games (user games), Match tracker (enter score frame by frame), Locate bowling alleys (using MapQuest API). Each link will bring the user to their respective page.

#### f. What features make your site more than CRUD? Do you have any stretch goals? 
I would like to add the ability for a user to enter which bowling ball and bowling alley were used for each game. Also, a notes section for the user to use to add notes about that game.
