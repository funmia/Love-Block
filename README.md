# Love Block Project

## How to use
1. Install Node.js.

2. Clone the repo to your computer.
```
git clone https://github.com/adoolaeghe/Love-Block
cd Love-Block
```

3. Install truffle testing framework and testrpc, a Node.js based Ethereum client used for development.
```
npm install -g ethereumjs-testrpc
npm install -g truffle
```

4. Install the node dependencies.
```
npm install
```

5. Install Metamask chrome plugin at https://metamask.io/.

6. Run testrpc in a separate terminal window. This will print out 10 pre-funded accounts along with a 12 word mneumonic which will allow you to regenerate these.
```
testrpc
```

7. Open a Metamask account using the 12 word mneumonic. Your account will contain 100 ETH.

8. In your original terminal window run:
```
truffle compile
truffle migratenpm run development
```
9. The app will be launched at localhost:3000.


## To run the tests:
```
truffle test
```

## User Stories

```
As a user,
So that I can demonstrate my commitment to another user,
I would like to be able to create a request for their hand in marriage.

As a user,
So that I can celebrate the marriage with the blockchain community,
I would like to see a confirmation of my marriage.

As a user,
So that I choose between two options,
I would like to be able to choose between yes and no.

As a user,
So that I can show evidence of my marriage,
I would like to receive a certificate once my marriage has been confirmed.
```

## Tech Stack

Ethereum/Testrpc
Truffle
Solidity
Javascript
Jade
Web3.js

## Team charter

* Simplicity
* Stand ups daily 10am
* Retro Daily at 5pm
* Have fun
* Consider everyone's views and opinions
* Open communication and honesty
* Respect that everyone has a life outside of the project
* Document key moments in the project
* Change pairs regularly
* Have a different stand up/retro leader each day
* Be kind to each other :)
