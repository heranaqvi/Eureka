# Eureka
A system that enables high quality reviews of the published work, while incentivizing authors and reviewers to participate in this decentralized, open, and public scientific publishing platform.

Abstract
Out casting, sharing, and publishing the collected knowledge, experiences, and outputs of scientific works, regard- less of being empirical or purely theoretical, has always been one of the key assets of human evolution. However, on one hand, re-usability of published work depends on accessibility, and, on the other hand, on the correctness of published work. Studies on the traditional scientific publishing platforms reveal many deficits with those systems, which had been addressed with the proposed blockchain-based solution called Eureka. Eureka enables high quality reviews of the published work, while incentivizing authors and reviewers to participate in this decentralized, open, and public scientific publishing platform.

Project Deliverables
● A simple system that integrates the Ethereum Network with a minimal front-end application, and a back-end consisting of a server managing the database.
● Eureka token contract implementation


 System Architecture

 WorkFlow Diagram
1. An author submits their manuscript in the Eureka platform (paying with EKA)
2. Once the Ethereum node triggers a new event in the Smart Contract (a new
submission), it informs the adequate set of reviewers.
3. Each reviewer can call a public function in the smart contract and submit their
review. Once the review gets submitted, the reviewer gets rewarded with EKA
tokens.
4. TheScienceMattersservernotifiestheauthor(convenience),whichcanthenget
the rating from the blockchain.
5. Oncethereviewflowisfinished,theeditorisinformedofanewmanuscripttobe
approved.
6. If the manuscript gets published, all referenced authors, for which an address
was found, get rewarded with EKA tokens.

Eureka’s Token-based Rewards

DApp
In order to build our dApp, we needed a few dependencies first.
● Node Package Manager (NPM)
● Truffle Framework
This allows us to build decentralized applications on the Ethereum blockchain. It also enables us to test our smart contracts and deploy them to the blockchain. It also gives us a place to develop our client-side application.
● Ganache
This is a local in-memory blockchain that ​gives us 10 external accounts with addresses on our local Ethereum blockchain.
● Metamask
This is a special browser extension in order to use the Ethereum block chain.
Eureka SC Contract Deployment


Initial_Migration.js
Deploy_contracts.js
Smart Contract Deployment
Ganache After Deployment


 Front End
