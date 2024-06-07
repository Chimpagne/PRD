# Timeline/Resource Planning

*What’s the overall schedule you’re working towards?*

We anticipate a rewritte in Flutter, to reach the IOS userbase.
This is obviously a significant undertaking.


*What resources are required?*

The main resource needed is developement time : we need to carefuly convert the existing codebase to use Flutter for the UI, as well as migrating away from firebase and setup a hosted sql database and the backend code to interact with it.

Regarding material resources, we need to setup testing for the IOS world : an apple computer and a real ios device are needed in addition to our existing hardware, to better test and understand the feeling of the app running on a real device.

*What are the intermediate milestones?*

## First intermeditate milestone

Before doing the rewrite, we think we need to re-evaluate the overall flow of the app. The user testing that was done indicates that the party-goer side of the app needs significant improvements. This first intermediate milestone will be a new flow mockup (in Figma), to better align with what the testers have told us they except from the app.


## Second intermediate milestone

A successful "UI only" flutter app working on both android and ios. At this point, the backend has not been connected.
This allow us to develop the UI of the app without waiting for the backend to be complete, thus the team members can work asynchronously.


## Third intermediate milestone

The backend side with the server code and database are completed in the sense that they replicate all the functionnalities offered by firebase in the POC. As previously mentionned, this milestone can be reached before or after milestone #2.

## Fourth intermediate milestone

The backend and frontend are fully connected, all the interactions available in the POC are replicated.


# Sprints

Each milestone is more or less a sprint on it's own. We assume these steps will be completed rather quickly, as the team already has a good understanding of the goal of the app and it's overall structure. Milestone 2 and 3 can be worked on simultenously by different member of the team. Two people could be dedicated to the backend side, with the rest of the team working on the UI.

