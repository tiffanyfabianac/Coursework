This material is created as part of course 1 or 4 in the Building Cloud Computing Solutions at Scale: Cloud Computing Foundations

## Terms to Remember:
  - **Makefile** - recipe for building software that makes sure application runs the same in any environment, available on all Linux systems
  - **Linting** - best practice in Python, checks for bad syntax, catches bugs before they occur, enhances automation
  - **Python Virtual Environments** - isolates python to a directory
  - **GitHub Actions** - SaaS-based build server that allows for Continuous Integration which will automatically test code, YAML based
  - **Continuous Integration** - form of automated testing
  - **YAML** "yet another markup language" is  a high-level, human-readable configuration file where you put in steps like test my code, lint my code

## Quiz Questions:
- What are the 8 principles for effective technical teamwork?
- What are 5 key tasks for technical project management?
- Name a couple project planning methods
- What are the project management anti-patterns?
- What is continuous integration and why do you care about it?
- Name 7 types of tests

## Important Concepts:
- Effective Technical Discussions
- Effective Technical Teamwork
  - **Have a clear, elevating goal** 
  - **Results-Driven Structure** set a goal, meausre the steps taken to achieve that goal, and use metrics for achieving the goals t measure the team
  - **Competent Team Members**
  - **Unified Commitment** to ensure everyone is on the same page in solving the problem
  - **Collaborative Climate** by rewarding teamwork, ensure there is no harmful competition
  - **Standards of Excellence** by making is clear what good is
  - **External Support and Recognition** upper management is supporting the team and their goal
  - **Principal Leadership** the leader has to have ethical character and is setting a clear inspiration for doing the right thing
  - _Talent vs Teamwork_ when building the team, ensure you are assessing the teammembers character, not only the talent. Teamwork builds the best possible outcome for an organization
 
- Effective Technical Project Management
  - Build a quarterly schedule which identifies week by week what will be built/what you will build
  - Do a weekly demo
  - Research DevOps - code is always in a deployable state
  - Automated testing - "if it's not automated, it's broken"
  - Create tickets in a 4 hour - 3 day timeframe, make it super simple and work to eliminate meetings
  - Avoid hero-driven development that requires someone to work all-night, or put in some type of heroic feat to deploy
  - Work to make things better every day
  - Project planning methods
    - Ticketing system like Trello or JIRA
    - Week by week planning in a spreadsheet
  - Project management anti-patterns:
    - Hero-driven development - 1 person has to complete some large effort to save the day
    - Crisis-driven development - the only way development gets done is during a huge crisis
    - HiPPO - highest paid person's decision where resources are pulled off work because CEO wants some feature
    - Heavy Scrum - all time is spent in the process instead of the productivity
    - Faith in people vs faith in the process - have a simple process with people delivering incremental results that can be shown
  -  Create an AWS Cloud Dev Environment
    -  Review terms: make file, linting, continuous integration, YAML, Python virtual environment, GitHub actions
    -  Continuous integration is a way of ensuring that code is always in a known state which saves time *Software is always knowable (either working or not) & saves time
      -  The best starting point is often to create a local scaffolding (makefile, test, virtual environment)
      - Next ensure SaaS build server is ready to automatically test code (every time a change is made, the code is tested)
  - Cloud9 is a cloud-based development environment that allows for developing inside the cloud environment where the cloud will run
    - Create virtual machine
  - Python Project Scaffold
    - Create Make File - requirements.txt - hello.py - text_hello.py - virtual environment
   - Types of tests: Unit (low level), Integration (different modules/services work well together), Functional (verifying business requirements), End-to-End (mimic users), Acceptance testing (formal verification that app forms), Performance (how the app works under load), Exploratory (sanity check to ensure things are working) 

## Recommended Additional Learning Material
- Teamwork: What must go right, what can go wrong by Larson and LaFasto
