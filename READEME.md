## Calyptus TODO List exercise.

Simple TODO list Smart contract using Anchor framework:

https://calyptus.co/lessons/building-a-to-do-list-with-anchor/


Clone repo.

### Build and Deploy

Run local validator in seperate terminal window

`solana-test-validator`

Set config to local solana cluster

`solana config set –-url localhost`

Complie the contract

`anchor build`

Deploy to local cluster

`anchor deploy`

---

Close previous validator terminal window

### Run Tests

Install packages

`yarn` or `npm install`

Run tests

`anchor test`