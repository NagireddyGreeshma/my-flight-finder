API for Flight System app in express.js with MongoDB
## Setup
## Demo
[![Watch the video](https://img.youtube.com/vi/ZJsrkypCF7E/maxresdefault.jpg)](https://youtu.be/ZJsrkypCF7E)

create a root directory `flight-system`
and clone these two repositories in it

`git clone https://github.com/rafaewaqarqazi/flight-system-api.git`

`git clone https://github.com/rafaewaqarqazi/flight-system-client.git`

copy the `.env.template` file in the api directory and rename it to `.env` and add the following environment variables

```env
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
AMADEUS_CLIENT_ID=your_amadeus_client_id
AMADEUS_CLIENT_SECRET=your_amadeus_client_secret
```

## Available Scripts

In the project client directory, run:

### `yarn install`

In the project api directory, run:

### `npm install`
### `npm run dev`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

