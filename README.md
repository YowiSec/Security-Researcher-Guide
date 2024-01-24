# Security-Researcher-Guide
A collection of tips, tools and guides for the aspiring web3 security researcher.



## What is a security review/smart contract audit?
  - 3 phases of a security review
      - Initial Review 
          - 0. Scoping/Onboarding
              - Rekt Test
          - 1. Reconnaissance
              - Solidity Metrics by Consensys OR cloc
          - 2. Vulnerability identification 
          - 3. Reporting 
      - Protocol fixes
          - 1. Fixes issues
          - 2. Retests and adds tests
      - Mitigation Review
          - 1. Reconnaissance
          - 2. Vulnerability identification 
          - 3. Reporting
           
  
## The Rekt Test
1. Do you have all actors, roles, and privileges documented?
2. Do you keep documentation of all the external services, contracts, and oracles you rely on?
3. Do you have a written and tested incident response plan?
4. Do you document the best ways to attack your system?
5. Do you perform identity verification and background checks on all employees?
6. Do you have a team member with security defined in their role?
7. Do you require hardware security keys for production systems?
8. Does your key management system require multiple humans and physical steps?
9. Do you define key invariants for your system and test them on every commit?
10. Do you use the best automated tools to discover security issues in your code?
11. Do you undergo external audits and maintain a vulnerability disclosure or bug bounty program?
12. Have you considered and mitigated avenues for abusing users of your system?
