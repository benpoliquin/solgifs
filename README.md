# Solana GIF Portal Project

### **Welcome 👋**
To get started with this course, clone this repo and follow these commands:

1. Run `npm install` at the root of your directory
2. Run `npm run start` to start the project locally


## Generate new BaseAccount to store data
```
cd src
node createKeyPair.js
```

# Copy IDL for program info every time `anchor deploy` is ran:
* `solana_program/target/idl/project_name.json`
* Copy this file to `src/idl.json`