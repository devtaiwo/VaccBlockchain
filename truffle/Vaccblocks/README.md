# Vaccblocks
Dapp proto to allow for storage of patient vaccination records in eth blockchain. 

# Setting up the development environment
There are a few technical requirements before we start. Please install the following:

    Node.js v6+ LTS and npm (comes with Node)
    Git

# Environment
$ node -v
v8.11.1

$ npm -v
5.6.0

$ truffle version

Truffle v4.1.8 (core: 4.1.8)

Solidity v0.4.23 (solc-js)

$ # Ganache

$ # MetMask version: 4.6.1

# Instructions:
1. Download the complete repository and go to the folder in your terminal

2. Run the development console.

        truffle develop

3. Compile and migrate the smart contracts. Note inside the development console we don't preface commands with truffle.

        compile
        migrate

4. Open another ternminal and Run the liteserver development server (outside the development console) for front-end hot   reloading. 
   Smart contract changes must be manually recompiled and migrated.

   // Serves the front-end on http://localhost:3000

        npm run dev


