# The GrapeVine

### T3A2-A, Full Stack App (Part A)

#### A Team Project By: Jacqueline Cope & Nga Dang

---

### Purpose

Following a few glasses of wine and plenty of conversation with our client, _Vineyard Productions_, we have been requested to create a full stack web application to support wine lovers of Australia.

The purpose of the site is to bring people together on a dedicated platform where they can share their love of wine and learn a tip or two along the way. This benefits the community of wine consumers at all levels to then be able to try recommended wines by those who have shared and contributed within the community.

In addition to sharing wine experiences, a dashboard of the most popular wines that users have _liked_ will be available.

### Functionality / Features

- Age verification to ensure users are of legal age
- To participate in the community users must create an account, however non-users (visitors) will have viewing access only
- A registered and signed in user that is authenticated:
  - May create a new post of a wine they enjoyed to share with the public
  - Has the ability to like a wine that has been posted, which will increase the popularity of the wine and may be displayed in the dashboard
  - Can comment on other users posts
  - May delete/remove or edit their own post
  - May NOT adjust or change the rating system and, or other’s peoples' comments
  - Has the ability to browse the catalogue of other contributors (other posts) and add comments accordingly
- A visitor may access and read all comments and see ratings without contributing. Contributing means making comments or participating in rating the wines
- A Navbar to store all main links for easy navigation of the site as well as a login/sign-up link
- The site runs on the basis of trust, where the user may _like_ a wine post by 'cheersing' (🥂) to like a post, following a similar concept to Facebook/Twitter. A user who has tried the wine and would like to recommend it to others can do so by _‘recommending’_ (🎖) the wine.
- The website will provide a list of categories to choose from. ie. White wine, red wine, etc
- The site will include a dashboard to show the current state of the most popular wines rated by users
- The host will require 2 types of user accounts, including administrator as well as a standard user accounts. All users will login via the same login access
- An administrator will have the ability to delete inappropriate content of any user

### Target Audience

- The target audience will need to be at the right legal age for drinking. The user must be 18+
- The App is targeted for users living in Australia at varying age groups

### Tech Stack

**Frontend:** React, HTML, CSS, Axios, Styled components / Bootstrap(?)
**Backend:** Rails API
**Database:** PostgreSQL, AWS S3
**Deployment:** AWS, Netlify
**DevOps:** Git, GitHub, VSCode
**Testing:** TBC
**Utilities:** Draw.io, Balsamiq Wireframes
**Project-management tools:** Trello, Discord

**React libraries:**

- Knock - user authentication/authorisation (TBC)
- Styled Components

### Data Flow Diagrams

![Data Flow Diagram - Guest](./dataFlowDiagrams/dfdGuest.png)

![Data Flow Diagram - User](./dataFlowDiagrams/dfdUser.png)

![Data Flow Diagram - Admin](./dataFlowDiagrams/dfdAdmin.png)

### Application Architecture Diagram

![Application Architecture Diagram](./architecture/architecture.png)

### User Stories

There are numerous possibilities to scale up the site. Therefore, the minimum viable product has been outlined with additional features to be added should time permit in the first release.

#### Minimum Viable Product

| As a...                           | I want to...                                                                                     | So that...                                                                                           |
| --------------------------------- | ------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| user / guest                      | view all wines listed, including the comments and the number of likes                            | I am able to see what recommendations others have and how others have responded to a particular wine |
| guest                             | create an account with an email address, username and password                                   | I have a unique account that is secure and doesn’t require providing too much personal information   |
| user                              | comment on a wine that has been posted                                                           | I can share my opinion/experience with the community                                                 |
| user                              | be able to like a post                                                                           | I can share my opinion with the community                                                            |
| user                              | be able to recommend a wine if I have tried it                                                   | others can know about this wine, boosting its popularity                                             |
| user                              | sign out when I have finished using the site                                                     | I can close my session off and my account is secured                                                 |
| user                              | create a post in a convenient and easy manner                                                    | the process is quick, easy to follow and can be shared with the community                            |
| user / guest / site administrator | be able to navigate the site easily without having to guess where to find certain site functions | I can navigate easily                                                                                |
| guest                             | be able to see what the community is about and has to offer                                      | I can understand if it’s relevant to my interests                                                    |
| user / guest                      | know what wines are popular                                                                      | I can try something new                                                                              |
| user                              | be able to edit or delete my own post/comment                                                    | if I make a mistake or need to retract a comment I am able to                                        |
| site administrator                | add a new wine to the wine list in a convenient and easy manner                                  | the process is quic and easy to follow                                                               |
| site administrator                | be able to edit or delete wine(s) from the wine list                                             | I am able to make modifications if need be                                                           |

#### Additional Features

| As a...            | I want to...                                                                       | I want to...                                                                          |
| ------------------ | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| user / guest       | search flavour profiles that I like                                                | I can discover wines that match the flavour profiles I prefer                         |
| user / guest       | have the ability to search wines, whether that is by name, grape type, region etc. | I can discover new wines that are relevant to what I’m searching                      |
| User               | be able to save the wines that I've tried or liked                                 | I can remember and try them                                                           |
| user               | be able to report a post or comment I deem as inappropriate                        | I am comfortable within the community and that the terms of site use are being upheld |
| site administrator | be able to remove anything reported as offensive                                   | it is able to be reviewed if meets the terms of site use                              |
| user / guest       | be able to get in contact with the site owner                                      | if I have any problems or suggestions I can pass it on to someone who can assist      |

### Wireframes

#### Standard Home Page

![Standard Home Page](./WireFrames/guestHome.png)

#### Login

![Login](./WireFrames/login.png)

#### Signup

![Signup](./WireFrames/signUp.png)

#### Loggedin User Home Page

![Loggedin User Home Page](./WireFrames/loggedinUserHomePage.png)

#### Wish List

![Wish List](./WireFrames/wishList.png)

#### Search Output

![Search Output](./WireFrames/searchOutput.png)

#### Report A Users Comment

![Report A User Comment](./WireFrames/reportUserPost.png)

#### Contact Us

![Contact Us](./WireFrames/contactUs.png)

#### Wine Ratings

![Wine Ratings](./WireFrames/wineRatings.png)

#### Administrator Dashboard

![Administrator Dashboard](./WireFrames/adminDashboard.png)

#### Create Post

![Create Post](./WireFrames/createPost.png)

#### Update A Post

![Update A Post](./WireFrames/updatePost.png)

#### Delete Post

![Delete Post](./WireFrames/deletePost.png)

#### Administrator Notification

![Administrator Notification](./WireFrames/reportedUserPost.png)
