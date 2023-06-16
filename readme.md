Frontend
--------------------------------------------
1) Make any frontend changes recommended by Abhishekh
2) Fix any minor UI issues
3) Integrate Objectives
4) Implementation of Infinite scroll
5) Implement import existing spl token properly, migrate away from hard-coded values
8) Fix re-fresh page, signer object not found issue

Backend(Web2)
---------------------------------------------
1) Make CI/CD for nodejs apis(Priority:Low)
2) Add tests to typescript apis(Priority: Medium)
3) Add child objectives part of typescript api(Priority: High)
4) Add stake/unstake part of bots(Priority:Medium)
5) Migrate the entire web2 python and nodejs api to Postgres(Priority:High)

Backend(Web3)
---------------------------------------------
1) Migrate contract tests away from mocha(Priority: Low)
2) Publish web3 connector typescript sdk on npm publicaly(Priority: Low)
3) Publish anchor's idl account(Priority:Low)

Design
---------------------------------------------
1) Figure out design of dev onboarding part our app

Blocked
---------------------------------------------
1) Migrate contracts to spl token 2022 standard
2) Integrate orca and raydium in frontend
3) Integrate pyth price feeds in frontend

Future
---------------------------------------------
1) Custom heap allocator using free lists, good example https://github.com/oxfeeefeee/smalloc/blob/main/src/lib.rs.
   Dont really need it right now but something when we try to scale put contracts to hopefully billion people or more
