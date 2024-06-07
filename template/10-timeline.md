# Timeline/Resource Planning

*What’s the overall schedule you’re working towards?*

We anticipate a rewritte in Flutter, to reach the IOS userbase.
This is obviously a significant undertaking.


*What resources are required?*

The main resource needed is developement time : we need to carefuly convert the existing codebase to use Flutter for the UI, as well as migrating away from firebase and setup a hosted sql database and the backend code to interact with it.

Regarding material resources, we need to setup testing for the IOS world : an apple computer and a real ios device are needed in addition to our existing hardware, to better test and understand the feeling of the app running on a real device.

| Resource                    | Description                                                                                 | Estimated Cost   |
|-----------------------------|---------------------------------------------------------------------------------------------|------------------|
| Development Time            | Convert existing codebase to use Flutter, migrate from Firebase, set up hosted SQL database | 10 to 15 weeks   |
| Apple Computer              | Required for testing in the iOS environment                                                 | $1,200 - $2,500  |
| iOS Device                  | Needed for real-device testing                                                              | $400 - $1,200    |
| Existing Hardware           | Additional hardware resources for testing and development                                   | Already owned    |


*What are the intermediate milestones?*

## First intermeditate milestone

Before doing the rewrite, it would need to re-evaluate the overall flow of the app. After doing some user testing, their feedback indicated that the party-goer side of the app needed significant improvements. This first intermediate milestone will focused on the new app flow mockup (in Figma), to better align our vision with what the testers have told us they expected from the app.


## Second intermediate milestone

Creating a successful "UI only" flutter app working on both android and ios. At this point, the backend will not have been fully connected.
This allow us to develop and focus on the UI of the app without waiting for the backend to be complete, thus team members can work in parallel.

**TODO ADD DETAILS FOR POSSIBLE TASKS JUST LIKE THE POCKETCAMPUS MVP**


## Third intermediate milestone

The backend side with the server code and database are completed in the sense that they replicate all the functionnalities offered by firebase in the POC and have added all of the new functionalities for the MVP that are possible with the inclusion of a SQL database. As previously mentionned, this milestone can be reached before or after milestone #2.

**TODO ADD DETAILS FOR POSSIBLE TASKS JUST LIKE THE POCKETCAMPUS MVP**

## Fourth intermediate milestone

The backend and frontend should be fully connected. Intense user testing will be done to remove any pain points in the user flow.

**TODO MORE DETAILS ARE NEEDED HERE**

# Sprints

Each milestone is more or less a few sprints on it's own. We assume these steps will be completed rather quickly, as the team already has a good understanding of the goal of the app and it's overall structure. Milestone 2 and 3 can be worked on simultenously by different members of the team. Two people could be dedicated to the backend side, with the rest of the team working on the UI.

