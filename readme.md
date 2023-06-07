Frontend
--------------------------------------------
1) Make any frontend changes recommended by Abhishekh
2) Fix any minor UI issues
3) Change hard coded divide amount by fetching decimal value from rewards mint in swaps connectors
4) Integrate Roadmaps and Objectives
5) Implementation of Infinite scroll
6) Implement import existing spl token properly, migrate away from hard-coded values
7) Add keep alive of 60 seconds headers to each api call, calling the python api, put it in a config file, so could change easily
8) Research on solitia

Backend(Web2)
---------------------------------------------
1) Make CI/CD for python and nodejs apis
2) Build github bots
3) Migrate python api to typescript
4) Add tests to typescript apis
5) Correct Roadmap and Objective typescript APIs

Backend(Web3)
---------------------------------------------
1) Migrate contract tests away from mocha

Design
---------------------------------------------
1) Figure out design of dev onboarding part our app

Blocked
---------------------------------------------
1) Migrate contracts to spl token 2022 standard

Future
---------------------------------------------
1) Custom heap allocator using free lists, good example https://github.com/oxfeeefeee/smalloc/blob/main/src/lib.rs.
   Dont really need it right now but something when we try to scale put contracts to hopefully billion people or more
