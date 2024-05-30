# Non-Functional Requirements

## Security, privacy, and data retention policies

*Which are the applicable laws and regulations?*

We cannot promote the use of illegal substances in the app. This is not something that is addressed in the current POC.

*What are your internal policies?*

The goal of the app is to help organize events. Obviously, some events are not desirable and should not be promoted on the app.

*Which privacy features do you need from the phone?*

The user location is heavily used throughout the app. This is an obviously important private information. Currently, we don't store it in the database and the user's location is only used to help discover events 

## Adoptions, Scalability and Availability

*What kind of traffic patterns do you expect to see?*

We expect people will join the app for a particular promotion (e.g. skip the line to buy Balelec tickets), and a good fraction will churn if they don't use it in the couple of weeks afterwards.

*Are there known periods of bursty traffic that the MVP must be designed to support?*

In the "promotion brings in a bunch of people" scenario, the bursty traffic is very much predictable. Thus, using the flexibility of modern cloud infrastructure, Chimpagne should be able to support the spike in traffic.