# Design and Implementation

## Frontend

*List the key libraries, languages, components used by the MVP.*

Jetpack compose was used as the declarative UI framework. Everything is written kotlin, with a tiny bit Java for tests.

*If applicable, describe essential screens.*

The app is divided into

- Event creation
- Event discovery
- Event details

## Backend

*Decompose the MVP into functional blocks.*

We use Firebase to store data

## Data Model

*What data are you collecting / managing?*

We collect event informations. The event information 

*How is it organised?*

We have the following collections:
- accounts
- events
  
Inside each collection, there are many documents (one for each account, one for each event)

*Where is it stored?*

The data is stored in firebase

*How is it shared/copied/cached?*

The data is cached client-side, so a basic offline experience is possible

## Security Considerations

## Infrastructure and Deployment

*How is the application developed, tested and deployed?*

The app is developed without taking into consideration a "real" backend : there is no security consideration, the inputs are checked client-side, but this does not provide security.

*Any special infrastructure requirements.*

## Test Plan

*How is the application developed, tested and deployed?*

The app is rigorously tested : code coverage is tested in the CI with sonar cloud, and the CI runs the tests at each commit.

*Any special infrastructure requirements.*

The architecture is quite standard and no special or deeply custom infrastructure is required for Chimpagne.
