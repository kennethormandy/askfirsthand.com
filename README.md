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

## Deploying to the [Harp Platform](http://harp.io)

First Hand uses a somewhat unconventional method of deploying to the Harp Platform. You’ll need to have access to the project on the Harp Platform and the Dropbox shared with you to deploy. Follow the [Running locally](#running-locally) instructions, and then:

```bash
# Compile to your Dropbox
npm run deploy
```

Now, just press “Publish” on the [Harp Platform](http://harp.io).
