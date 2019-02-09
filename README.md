# whoami
[![whoami|jihdeh](/avtbase.png)](https://github.com/jihdeh)

### I'm Babajide, and i'm a Software Engineer.

I have 5 years of professional software development experience and 1 year self taught coding experience. Living in Lagos, Nigeria, i have been working remotely for the past 4 years, so i pretty much have experience getting up late in the night to meet up with meetings or fix a bug.

Proficient Technical skills:
  - Frontend
    - Html/Css/Css processors(scss/sass)/Bootstrap/Material-ui
    - Javascript
    - ReactJS/Redux
    - **And any other Javascript library i need to get the job done**
  - Backend
    - ExpressJS/KoaJS
    - MongoDb
    - Nodejs
  - Development Operations
    - Aws (Storage/aws-amplify/lamdba)
    - Google Cloud (storage/compute/kubernetes)
    - Docker
    - Command line tool 
  - Testing
    - Jest/Enzyme
  - Version Control
    - Git
    
Technical skills of the past:
- These are skills i have worked with in the past that i'd probably need learning over again to get up to speed.
  - Python / Flask
  - PostgreSQL
  - D3.js
  - Salesforce (Apex)


Soft Skills: 😇
   - Well written and verbal communication skills.
   - Teamwork and working with people across different departments.
   - Approachable, patient and takes ownership on decisions.
   - Open-mindedness
   - Problem solving

I'm also a code mentor, you can view my profile here on [Codementor](https://codementor.io/jihdeh_f)

Staying up to date:
I stay up to date in a number of ways, following tech blog posts, mentoring people as i get to learn a thing or two sometimes, checking github repository changelogs :)

Greatest Challenges i have faced technically:
 - Outdated development packages,
   - : - The goal was to upgrade packages on a monolithic project, on both the frontend and the backend
   - Solution 
      -  We started small, split the backend from the frontend, at this point, the application was no longer isomorphic (server side rendering removed).
      - Then upgrade the small packages, that aren't peer dependencies of another library, more like helper libraries, e.g [Lodash](https://lodash.com/), [Axios](https://github.com/axios/axios) etc.
      - Next was to move up to the bigger libraries that could break stuff (React), this was super challenging as it was a large codebase.
    - One month later - Upgrade was complete.
 - 2AM deploys,
   - Application was built without a staging/testing server, and deployments were done manually (server shuts down, pull updates to server, and then spin server up again). Imagine if there was a bug that needed to be fixed and you had users on your site?
   - Solution
      - Create a deployment pipeline on github connected with Jenkins, when a push was done to a branch on github, two things happen. 1. Automated deployed, a new instance of your application is spun up, 2. A unique url is created for you to test your work e.g unique-branch.domain.app.
      - Once everything works as expected on your unique url, you can merge your work with staging branch for further QA testing, then the master branch(production code) if all goes well.
- High requests, failing application,
  - This application requires alot of resources as it processes large video files to give back analysis, everytime there was a high number of requests and video interviews coming through, 1. the site processes requests slow, leading to bad user experience, 2. The server crashes leading to loss of video files taken by users for analysis, the solution at the time was to reach out to them to take the video again.
  - Solution
    - We decided to move the application's backend processing service to Google kubernetes as the service helped with load balancing and scaling, everytime we had high requests, new servers are spun up to handle the requests sharing the load across servers, and it scaled back down anytime we didn't have much requests.
    
I am quite resourceful, if i can't come up with a solution, i know how to google for solutions, using google queries, deep search stuff.
I like learning new things, trying them out, to see if it'll be useful in a project i'm working on.
I'm passionate about what i do, passionate about adding value to where-ever i find myself, giving my best and delivering quality code.
