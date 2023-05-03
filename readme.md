Frontend
--------------------------------------------
1) Make changes recommended by Abhishekh

Backend(Web2)
---------------------------------------------
1) Make CI/CD for python and nodejs apis(Priority:Low)
2) Make Unit tests for python and nodejs apis(Priority:Low)
3) Make changes to integrate changes in metadata uri from frontend(Priority:Medium)

Backend(Web3)
---------------------------------------------
1) Update our dependency graph to update anchor-spl to "0.27.0" from "0.25.0", this is creating a compilation issue in many cases with new changes
made to support better and simpler api in newer versions of anchor-spl
2) Audit accounts in context of each function and
   i) If context length>9 accounts, add Box<> to account to do heap allocation and prevent stack overflow
   ii) Remove Box from as many accounts in context as possible while keeping "unboxed" accounts in context <= 9, stack retrival is more efficient
       than heap retrival and should be used whenever possible
   iii) Verify how send_funds and send_tokens work and why there are two of these in our smart contract
