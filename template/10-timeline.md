# Timeline/Resource Planning

*What’s the overall schedule you’re working towards?*

We anticipate a rewritte in Flutter, to reach the IOS userbase.
This is obviously a significant undertaking.


*What resources are required?*

The main resource needed is developement time : we need to carefuly convert the existing codebase to use Flutter for the UI, as well as migrating away from firebase and setup a hosted sql database and the backend code to interact with it.

Regarding material resources, we need to setup testing for the IOS world : an apple computer and a real ios device are needed in addition to our existing hardware, to better test and understand the feeling of the app running on a real device.

| Resource                    | Description                                                                                 | Estimated Cost   |
|-----------------------------|---------------------------------------------------------------------------------------------|------------------|
| Development Time            | Convert existing codebase to use Flutter, migrate from Firebase, set up hosted SQL database | 6 to 8 weeks     |
| Apple Computer              | Required for testing in the iOS environment                                                 | $1,200 - $2,500  |
| iOS Device                  | Needed for real-device testing                                                              | $400 - $1,200    |
| Existing Hardware           | Additional hardware resources for testing and development                                   | Already owned    |


*What are the intermediate milestones?*

## First intermeditate milestone

Before doing the rewrite, it would need to re-evaluate the overall flow of the app. After doing some user testing, their feedback indicated that the party-goer side of the app needed significant improvements. This first intermediate milestone will focused on the new app flow mockup (in Figma), to better align our vision with what the testers have told us they expected from the app.

Here are the key points for this milestone:

- Complete, beautiful app mockup in Figma

- Written feedback from testers

- Clear and common vision for the app flow in written form

## Second intermediate milestone

Creating a successful "UI only" flutter app working on both android and ios. At this point, the backend will not have been fully connected.
This allow us to develop and focus on the UI of the app without waiting for the backend to be complete, thus team members can work in parallel.

At this point, we will fill the UI with mockup data, and we will be able to do a quick testing sessions with users, to get feedback early one.

Key points for this milestone:

- The app runs on android and ios
- It is aesthetically pleasing, and conforms to the Figma app mockup

## Third intermediate milestone

The backend side with the server code and database are completed in the sense that they replicate all the functionnalities offered by firebase in the POC and have added all of the new functionalities for the MVP that are possible with the inclusion of a SQL database. As previously mentionned, this milestone can be reached before or after milestone #2.

Key points for this milestone:

- The backend runs in a server in our control
- A language & framework has been choosen and is used for the backend
- A SQL database has been properly set up
- The user inputs are properly sanitized
- Security measures are properly implemented


## Fourth intermediate milestone

The backend and frontend should be fully connected. Intense user testing will be done to remove any pain points in the user flow.

Key points for this milestone:

- A lot of unit tests will be needed to test for the proper integration between the backend and the frontend.
- The app works as expected without an internet connection
- All the functionalities of the POC will be implemented


# Sprints

Each milestone is more or less two sprints on it's own, by doing one week sprints. We assume these steps will be completed rather quickly, as the team already has a good understanding of the goal of the app and it's overall structure. Furthermore, LLMs in our experience can really help to build UI once a clean app mockup can be given as a prompt. Milestone 2 and 3 can be worked on simultenously by different members of the team. Two people could be dedicated to the backend side, with the rest of the team working on the UI.

