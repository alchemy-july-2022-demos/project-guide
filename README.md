# Project Kick-Off

- Review Toolkit
- Review Requirements
- Think about Ideas
- Present Ideas
- Group Idea Discussion (Gather Town)
- Coagulate into teams
- Review
    - Team
    - Planning
    - Presentations

## Toolkit

- Handle user events
- Track and change state on a web page
- Use randomness
- Model game rules with js logic
- Model "real world" things with objects and arrays
- Display things
    - list of things
    - detail of a thing
    - form to create (or update) a thing
    - update things already displayed
        - change content (text) or presentation (class, etc.)
        - same-page list modifications (add, remove, update)
- Using search params to pass information (application state) between pages
- Display
    - color and typography
    - images
    - layout (static, grid, flex)
- Use a backend (supabase)
    - CRUD (Create, Read (Select), Update, Delete) with Database
    - Auth
        - Authentication (you are who you say you are): sign in, sign up
        - Authorization (we know who you are, but can you do this thing?): RLS
    - Image/File Uploads
    - Maybe Realtime

## Requirements

- Group collaboration tool to organize features like Miro. (You'll link to this tool in your Canvas submission).
- Setup
    - Create a GitHub Organization for your repo (add team members as admins)
    - Create a Supabase Project (add team members)
    - Follow the general architecture we used during the course
    - Use the auth template
- Deployed on netlify
    - main and PR previews
- GitHub
    - Branching strategy (feature --> main)
    - Team PR Process
    - Get help for pulling and merging
- CSS
    - Thoughtful layout
    - "Branding"
- Supabase Auth and protected pages.
- Data requirements:
    - User or Profile related to at least one table
    - One of the following:
        - At least two tables related tables _besides_ user or profile relationship
        - Your app is a sufficiently complex "game" that stores game state or result in supabase.
    - RLS Correctly applied
- Should have (mostly) all CRUD operations:
    - Create
    - Read one/Read all, 
    - Update or Upsert
    - Delete
- A "Built By" page detailing who worked on the project

## Team Agreements

- What team members want to get out of project
- Schedule/Off-hours
- How you each fit into shared purpose?
- How will you make sure everyone can: speak, ideate, lead
- How will you make each other better?
- How will you share progress?
- How will you deal with conflicts?

Also: 
- No 'cowboy coding'
- "If you want to go fast, go alone; if you want to go far, go together."
- "Slow is smooth, smooth is fast"

## Planning Requirements

Use a planning tool like Miro or Whimsical

High Level Concept, work out what:

- Mission and what is in scope
- Very lean MVP looks like opens the door to adding more features
- The general idea is, including domain entities (things your app is about)

**Get sign-off on your idea at this stage**

Then do additional planning keeping resources in your planning board.

- What pages are in the app
- Database Schemas
- Themes, Image ideas

Things that are close need to be crisp, things you will get to next can be fuzzier:

- Wire frames for each page
- What state is needed? What actions change state?
- What data is needed? What actions change data?

## Commit history

- Everybody knows that commit history is never the whole story. Indeed, in pair/mob programming a navigator contributes a great deal without making a signle commit! Nonetheless, commit history is one metric we use to evaluate individual participation. 
- To this end, be vigilant to make sure you are personally making a fair number of commits to the group repo. 
    - This may mean having candid conversations during morning standup about how you feel you are not getting enough time as the driver.
- We also liik at the Insights -> Contributors graph from github, which describes the commits by each team member. 

## Peer feedback. 

In the "Sprint Week Project Submission" assignment on Canvas, in addition to describing their own contributions, you will be asked to evaluate you team dynamic in general, and to specifically  evaluate each member's contributions.

### Instructor check-ins. 

We'll visit your group at least once daily to ask how the project is going. In addition to a progress check, this is a _temperature check_. We'll be looking to see if the group dynamics feel off. Specifically we'll ask ourselves: does one person seem to be dominating the project to the detriment of the group? In a group project, this can be just as damaging (perhaps more damaging) than a coder who contributes nothing to a codebase.
