# Getting Started

You have to add your own PLAYLIST url in **src/App.js** as shown here:

```javascript
spotify.getPlaylist('xXxXxXxXxXxXxXxXxXx').....
```

and also your spotify API KEY in **src/spotify.js** as shown here:

```javascript
const clientId = 'xXxXxXxXxXxXxXxXxXxX'
```

** I had issues (with material-ui module) using npm v7... so i did a downgrade to v6 and it worked **

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.
