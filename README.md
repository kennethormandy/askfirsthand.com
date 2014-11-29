# First Hand

## Running locally

If you’d like to run the website locally, you’ll need [Node.js installed](http://nodejs.org). Then, run the following commands on your terminal. If you’re unfamiliar with the terminal, take a look at [this helpful introduction](http://wiseheartdesign.com/articles/2010/11/12/the-designers-guide-to-the-osx-command-prompt/).

```bash
# Install Harp
npm install -g harp

# Clone the repository
git clone https://github.com/kennethormandy/askfirsthand.com

# Move into the folder you just downloaded
cd askfirsthand.com

# Install dependencies through npm
npm install

# Serve the project with Harp
harp server
```

## Deploying

You’ll have to be a collaborator to deploy this project. [Email Kenneth](kenneth@chloi.io) to get access, and thanks for your interest!

First, follow the [Running locally](#running-locally) instructions. Then run the following command:

```bash
# Compile and deploy to askFirstHand.com
npm run deploy
```
