# The MVP

## Personas and Scenarios

### Target Personas

- Student Event Organizer
- Family Member
- Newcomer in a City
- Party Organizer
- Party Goer

### Key Persona

**Party Organizer**: This persona is crucial because they drive the initial adoption and continuous use of the app by creating events and managing guests. Their positive experience directly impacts the other personas (like party goers and family members) who attend and interact with the events they organize.

### High-Level Scenarios to Adopt, Use, and Share the Product

#### Adopting

- Discovering the app through various channels such as word-of-mouth, social media, advertisements, or community groups.
- Downloading and installing the app from the app store.

#### Using

- **Student Event Organizers and Family Members**: Setting event details, creating task lists, and managing reminders.
- **Newcomers**: Searching for nearby events, checking party details, and deciding which events to attend.
- **Party Organizers**: Authenticating guests with QR codes, managing offline guest lists, and ensuring smooth event check-ins.
- **Party Goers**: Using the app to find safe transportation options after attending parties.

#### Sharing

- Recommending the app to friends, family, and fellow event planners due to its user-friendly features and efficient management tools.
- Sharing positive experiences on social media or within community groups to encourage others to download and use the app.

## User Stories and Key Features

### User Stories

- As a student event organiser, I want to easily plan a party with friends using an app, so that I can efficiently set the event location, create a grocery list, and assign tasks like buying beverages. The app's reminders and updates make planning stress-free and enjoyable.
- As a family member, I want to utilise the app to effortlessly plan our gatherings, enabling me to delegate tasks and organise details with ease. This ensures smoother coordination, reduces my worry, and allows me to focus on enjoying quality time with my loved ones.
- As a newcomer in a city, I want to use the app to discover events in close proximity to me so that I can meet new people. The party style tag allows me to see what kind of party it is: “Alcohol-free”, “Vegan-friendly”, etc.
- As a party organiser, I can easily authenticate people attending my party with their QR-code. The guest list is stored on-device, so I don’t need internet access to verify they were indeed invited. The guest also does not need to have internet access to show their QR code.
- As a party goer, I am looking for a way to get back home safely. The app will provide options for safe transportation.

### Key Features

1. **Event Creation and Management**: Essential for party organizers to plan and manage their events efficiently.
2. **Task Assignment and Reminders**: Helps users delegate tasks and receive automated reminders.
3. **Guest Authentication with QR Codes**: Ensures secure and smooth guest check-ins.
4. **Offline Guest List Management**: Allows organizers to manage guest lists without requiring internet access.
5. **Event Discovery for Newcomers**: Helps new users find and attend nearby events.
6. **Safe Transportation Options for Party Goers**: Provides safe travel options after events.

## Success Criteria

### Evaluation Metrics

1. **User Penetration Metrics**
   - **Number of Downloads**: Track how many times the app has been downloaded from the app store.
   - **Active Users**: Measure daily and monthly active users (DAU/MAU) to understand engagement.
   - **User Retention Rate**: Calculate the percentage of users who continue to use the app over a specific period (e.g., after one week, one month).
   - **User Growth Rate**: Monitor the rate at which new users are signing up and engaging with the app.

2. **Quality and Satisfaction Metrics**
   - **User Feedback and Reviews**: Collect qualitative feedback through surveys, in-app feedback forms, and app store reviews.
   - **Net Promoter Score (NPS)**: Measure how likely users are to recommend the app to others.
   - **Feature Usage Statistics**: Track how frequently key features (e.g., event creation, task assignment, guest authentication) are used.
   - **Customer Support Tickets**: Analyze the number and type of support tickets to identify common issues and areas for improvement.

3. **Ecosystem Partner and Investor Engagement**
   - **Partnership Development**: Track the progress of discussions with potential ecosystem partners (e.g., venues, transportation services).
   - **Investor Interest**: Measure the number and quality of interactions with potential investors, including meetings, pitch presentations, and follow-up interest.
   - **Customer Acquisition**: Monitor the number of event organizers, family members, and newcomers who adopt the app and provide testimonials or case studies.

## Coming in Future

### New Features
- **Check-in**: Quick access to events via QR code or invite link for seamless entry.
- **Shared Budget & Purchases**: Simplifies the management of collective expenses for events.
- **Party Rating & Review System**: Allows attendees to rate and review events, providing valuable feedback with a stars system.
- **Improved Carpooling and Sleeping Options**: Enhanced features for organizing transportation and accommodations.
- **Firebase Notifications**: Implementing Firebase for real-time notifications to keep users informed.
- **Real-Time Location Tracking**: Enables attendees to easily locate each other during events.
- **Event Geolocation**: Provides easy navigation to event locations through integrated mapping.
- **Photo Sharing**: Allows post-event photo sharing directly from the app's camera.

### Enhanced Authentication
- **Phone Number and Email/Password Authentication**: Additional methods for user authentication, ensuring flexibility and security.

### Offline Capabilities => Not sure which ones will be available for the MVP
- **Event Location Storage**: Event locations are stored locally on the device.
- **Local Map Download**: A 10 km² area around the event location is downloaded using OpenStreetMap, ensuring navigation even without internet access.
- **Event Information Caching**: All event details are cached on the device for offline access.
- **Offline Playlists**: Spotify link implementation allows offline access to event playlists.
- **Offline Chat Messages**: Chat messages are available in offline mode, ensuring continuous communication.
- **QR Code Authentication**: Authenticate attendees to an event using their QR codes, even without internet connectivity.

