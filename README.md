# The GrapeVine

### T3A2-A, Full Stack App (Part A)

#### A Team Project By: Jacqueline Cope & Nga Dang

---

### Purpose

Following a few glasses of wine and plenty of conversation with our client, _Vineyard Productions_, we have been requested to create a full stack web application to support the wine lovers of Australia and Australian wine industry.

The purpose of the site is to bring people together on a dedicated platform where they can share their love of Australian wine and learn a tip or two along the way. This benefits the community of wine consumers at all levels to then be able to try recommended wines by those who have shared and contributed within the community.

In addition to sharing wine experiences, a dashboard of the most popular wines that users have _liked_ or _recommended_ will be available.

### Functionality / Features

- Age verification to ensure users are of legal age
- Each week the website administrator will share a number of new wines, as posts, for users to share their opinions about
- To participate in the community users must create an account, however non-users (guests) will have viewing access only and limited access to features
- A registered and signed in user that is authenticated:
  - Has the ability to like a wine that has been posted, which will increase the popularity of the wine and may be displayed in the dashboard
  - Can comment on wine posts
  - Can delete or edit their own post
  - Cannot adjust or delete another person's comments
  - Has the ability to browse the catalogue of other contributors (other posts) and add comments accordingly
- A guest may access and read all comments and see ratings without contributing. Contributing means making comments or participating in rating the wines
- A Navbar to store all main links for easy navigation of the site, including login/sign-up
- The site runs on the basis of trust, where the user may _like_ a wine post by 'cheersing' (🥂) to like a post, following a similar concept to Facebook/Twitter. A user who has tried the wine and would like to recommend it to others can do so by _‘recommending’_ (🎖) the wine.
- The website will include filtering options to assist in the user search experience ie. wine type, grape, etc
- The site will include wine ratings to show the most popular wines rated by users
- The site will include 2 types of user accounts, including a website administrator as well as a standard user accounts. All users will login via the same login access
- A website administrator will have the ability to delete inappropriate content of any user

### Target Audience

- The target audience will need to be at the right legal age for drinking. The user must be 18+
- The App is targeted for users living in Australia at varying legal age groups specifically interested in Australian wines

### Tech Stack

**Frontend:** React, HTML, CSS

**Backend:** Rails API

**Database:** PostgreSQL, AWS S3

**Deployment:** Netlify & Heroku

**DevOps:** Git, GitHub, VSCode

**Testing:** RSpec - Rails, JEST - JavaScrupt

**Utilities:** Draw.io, Balsamiq Wireframes

**Project-management tools:** Trello, Discord

**React libraries:**

- JWT - user authentication/authorisation
- Styled Components
- React Bootstrap

### Data Flow Diagrams

![Data Flow Diagram - Guest](./docs/dataFlowDiagrams/dfdGuest.png)

![Data Flow Diagram - User](./docs/dataFlowDiagrams/dfdUser.png)

![Data Flow Diagram - Admin](./docs/dataFlowDiagrams/dfdAdmin.png)

### Application Architecture Diagram

![Application Architecture Diagram](./docs/architecture/architecture.png)

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

![Standard Home Page](./docs/WireFrames/guestHome.png)

#### Login

![Login](./docs/WireFrames/login.png)

#### Signup

![Signup](./docs/WireFrames/signUp.png)

#### Loggedin User Home Page

![Loggedin User Home Page](./docs/WireFrames/loggedinUserHomePage.png)

#### Wish List

![Wish List](./docs/WireFrames/wishList.png)

#### Search Output

![Search Output](./docs/WireFrames/searchOutput.png)

#### Report A Users Comment

![Report A User Comment](./docs/WireFrames/reportUserPost.png)

#### Contact Us

![Contact Us](./docs/WireFrames/contactUs.png)

#### Wine Ratings

![Wine Ratings](./docs/WireFrames/wineRatings.png)

#### Administrator Dashboard

![Administrator Dashboard](./docs/WireFrames/adminDashboard.png)

#### Create Post

![Create Post](./docs/WireFrames/createPost.png)

#### Update A Post

![Update A Post](./docs/WireFrames/updatePost.png)

#### Delete Post

![Delete Post](./docs/WireFrames/deletePost.png)

#### Administrator Notification

![Administrator Notification](./docs/WireFrames/reportedUserPost.png)

### Trello Board Screenshots

The Trello board screenshots below are in order of dates, showing the progress of the assignment as it develops over time.

![Trello Board](./docs/trello/02_07_22.png)

![Trello Board](./docs/trello/03_07_22_jc.png)

![Trello Board](./docs/trello/03_07_22_nr.png)

![Trello Board](./docs/trello/04_07_22.png)

![Trello Board](./docs/trello/06_07_22.png)

![Trello Board](./docs/trello/07_07_22.png)

![Trello Board](./docs/trello/08_07_22.png)

![Trello Board](./docs/trello/09_07_22.png)

![Trello Board](./docs/trello/10_07_22.png)

![Trello Board](./docs/trello/10_07_22_userstories.png)

![Trello Board](./docs/trello/11_07_22.png)

![Trello Board](./docs/trello/12_07_22_aad-redo.png)

![Trello Board](./docs/trello/13_07_22.png)

![Trello Board](./docs/trello/13_07_22_aad-detailed_log.png)

![Trello Board](./docs/trello/15_07_22.png)




























