## Brag Document
> _**Note**: in reverse-chronological order_

### 2026
- published a [technical post-mortem and white paper on AI-driven engineering](https://github.com/minademian/documentation-library/blob/main/route-planning-opti-app-with-llm/route-planning-opti-app-with-llm.md), from the hackathon exercise last month!

### 2025
- set up my documentation library and published a detailed how-to guide with EKS.
- built an AI-first fullstack solution (vanilla JavaScript + Spring Boot + Postgres) in 4 hours during a hackathon
- architecting a wider solution to enable users to manage liturgical texts without having to learn SQL and make changes in a bundled in-app SQLite database. More coming soon.
- executed a difficult React Native upgrade from 0.75.2 to 0.79.4 and accounted also for Android 16kb page size support. Truly teeth-cutting stuff!
    - offered back some APK and AAB bundle validation scripts to the community - ([APK](https://gist.github.com/minademian/6e841c8e1a84308c6b3dc937a2d4a4cd),[AAB](https://gist.github.com/minademian/71a5a3d0243496ce6a2a49956c01e4cd))
- published several deep-dive guides, technical deep-dives, anddesign documents:
    - Delving into React Native - ([1](https://blog.minademian.com/lessons-learned-from-a-react-native-app-in-production/), [2](https://blog.minademian.com/using-the-adapter-pattern-to-tame-wild-react-native-upgrades/), [3](https://blog.minademian.com/grafting-in-tdd-into-a-legacy-react-native-codebase/))
    - how I approached the [JIRA Worklogs Bot design](https://blog.minademian.com/system-design-document-jira-worklog-bots/)
    - how to [timebox idea execution with AI](https://www.linkedin.com/pulse/timeboxing-ideas-ai-assisted-engineering-mina-demian-5z0mf?trackingId=nVMMQynoZ09mPHCTmwRw5A%3D%3D&lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_recent_activity_content_view%3BGQcDkcGaSLq%2BQBVn7A8u2A%3D%3D)
- launched my [documentation library](https://github.com/minademian/documentation-library) with a [complete guide to deploying a service to AWS EKS](https://github.com/minademian/documentation-library/blob/main/deploying-a-service-to-aws-eks/deploying-a-service-to-aws-eks.md)
- 1 new microservice `git-notification-service` and Python script `git-sync` built and at pre-alpha, the former running successfully in production two weeks in a row
    - microservice listens for webhook events posted from vanilla Git server and processes them with Kafka
    - Python script runs a diff check between vanilla Git and destination Github, creates commits in destination if not found.
- launched [yarn-shell-completion](https://github.com/ursine-inc/yarn-shell-completion) as open-source!
- launched [server-utilities](https://github.com/minademian/server-utilities) as open-source!
- Cleared to host and maintain jira-worklogs-bot under private account!!
- 4 alphas and pre-alphas built this week with AI-assisted engineering and rapid prototyping
    - React Native application
    - sql.js + vanilla JS/HTML CRUD console for sqlite databases
    - Revamp of old React app into 2025 React 18 + Chakra UI listings module
    - Custom WordPress theme + plugin
- First foray into bot development
    - JIRA worklogs bot - Spring Boot application sideloaded into Teams
    - MCP server - Node application sideloaded into Teams
- Able to refactor and confirm diff-check was idempotent through AI-assisted debugging and pair-programming
- Taught myself how to setup, configure, and deploy sideloaded Teams applications in Entra
- Deployed and launched DR to production, against all odds
- Left JIRA board clear ahead of vacation and paused full solution in production
- Becoming a Java programmer
- Becoming an AI-assisted engineer, leveraging AI to code
- First Java package in production under public domain
- First bash utility aiming for production quality
    - Pitched to CTO office to be considered for open source under Cabonline
    - Passed first Solution Architect review!
- Passed 1st quarterly review with positive feedback!
- Cleared to release OSS candidate under own name!
- - Took part in interview process, exerting influence and leadership
    - coworkers deferring to my judgment
- Successful end of mentoring intern. Got good feedback
- Brought down Scytale audit task from 51 to 9 within 48 hours
    - Sent new short weekly report to boss about state of technical debt
    - Saved company money
    - Set up automated tests for FE repos
- PoC finally fixed in test, working!
    - Transparency with stakeholders, internal and external
    - Took inventory and wrote report that may come in handy later
- EXCEEDED EXPECTATIONS AND GOT RAISE
- Handled the situation with the DR deadline. Got an extension by arguing facts and being a leader.
- Successfully identified, troubleshooted, communicated, and documented a test environment issue that could have delayed or blocked release.
    - Built FE logging solution as part of above
- Doing recognized work with CISO in auditing
    - Learning the ins and outs of auditing tool
- Taking up space and asserting myself in team
- Solved the infra issue
    - Have become a lot more comfortable and knowledgeable with AWS, ECS
- Have gotten better at infra + networking + AWS
- Delivered demo albeit a tad buggy. Went the extra mile, put in extra effort an hours
- Taking up space at Engineering Excellence Chapter
- Working directly with Group CTO!
- Finished hard refactor of status polling
- Stepped in to help out lead with compliance/technical debt, assigned by SM
    - Got temporary owner access to GitHub org

### 2024

- 2 non-trivial PRs, 1 DevOps PR merged in first full week of work at Cabonline
- Documented nx monorepo upgrade process
- Started audit of front-end repos, identified CI/CD and deployment targets
- Merged 4 PRs, one of them accessibility and HARD. Required collaboration with original author
- Merged 2 complex PRs
    - Went through lengthy and intense review process
    - Built up social capital and rapport with team mates
- Took on bigger PR this week that will get me involved in work with backend, API endpoints
    - Contributing to knowledge transfer
    - Taking on more difficult tasks rather than just playing it safe with smaller cosmetic changes
- Showing initiative and coworkers are noticing and commenting on it
- Contributed to documentation
- Wrote summary of Swedish-language webinar for rest of English-speaking team
- Helped out backend with validating OpenAPI documentation by resolving a pain point
    - set up a way to validate OpenAPI documentation
- Did PoC in under an hour to integrate Storyblok API into <redacted>
- WON A CODE ARGUMENT WITH COWORKER
- WON MY SECOND CODE ARGUMENT WITH… HIM. O_O
- Finished one significant new feature, going through a long review process, learning a lot about architecture and design in React
- GOT INVITED TO ENGINEERING CHAPTER BY JUST WORKING HARD AND SHOWING UP AND DELIVERING ON PROJECTS AND BEING MY AUTHENTIC SELF
- Tapped to mentor intern and effectively be lead on new PoC
- Contributed to pitch deck for PoC
    - drafted initial solution design
    - contributed to visual design
- Good relationships with Scrummaster and PO
- Intern flourishing!
- Went from support on DR to frontend lead
    - Building relationships
    - Challenging myself technically and relationally, soft-skills wise
    - Building relationships up and across
- Done CI/CD 90% on my own, deployed backend service with AWS
    - Taking ownership and driving project
- Leveraging relationships to get help with BE
    - BE is starting to look and function like a proper microservice

### 2023

#### Completed projects
* 2023 v1 of minademian.com
* micro-service, built in TypeScript, in production

#### Technical skills
* learned React from scratch
* built my first micro-service and learned about API design

#### Professional development
* 50% through 6 courses of Google Project Management: Professional Certificate on Coursera

#### Feedback and recognition
* Positive feedback and encouragement from CTO at Fondo
* Positive feedback from CPO at Fondo on solving pesky CSS animation bug on fondo.se

#### Open source contributions
* Here's to 2024!
