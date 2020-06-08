<h1 align="center">
<br>
  <img src="readme_files/logo.svg" alt="ECOLETA" width="120">
<br>
<br>
ECOLETA
</h1>

<p align="center">Connecting people to Recycling Companies!</p>


<div align="center">
  <img src="readme_files/1.gif" alt="Ecoleta" height="425">
  <img src="readme_files/2.gif" alt="Ecoleta" height="425">
</div>

<hr />

## About Ecoleta
This app has two major systems combining into a powerful idea that can help people to be more active on the environmental cause.
<br /> <br />
It allows recycling companies to publish their addres and inform what kind of items they are able to recycle and collect.<br/> Users, on the other hand, can use the app to look right on the map API for the nearest recycling point. Users can also filter what categories of items they are looking forward to discard.<br/>
By choosing one recycling point, Users have access to selected Company's profile, featuring Photo, Name, address, MailTo Button and Whatsapp Contact Button.

## Features
This app uses the best features to web and app development:

- ⚛️ **React Js** — Used for the Company's Sign Up Form website
- ⚛️ **React Native** — Used for the Users app
- 💹 **Node Js** — Used for Backend features like App Filters, database manager, Company's profile page and so on
- 💹 **Node Js Dependencies** - Axios, Knex, Express, Crypto, Multer, Cors and others

## Getting started
<b>* Yarn required</b><br/>
1. Clone this repo using <code>git clone git@github.com:sor-alan/NLW-01.git</code>

### Server Config
1. Set server IP on PointsController.ts and itemsController.ts files<br/>
2. Open terminal on src folder <br/>
3. Run <code>npm install</code> to install node dependencies <br/>
4. Build database by running <code>npx knex migrate:latest --knexfile knexfile.ts</code><br/>
5. Run server with <code>yarn dev</code>

### Web App Config
1. Set server and web IP on Api.ts, index.ts (CreatePoint and Home) files<br/>
2. Open terminal on web folder <br/>
3. Run server with <code>npm start</code>

### App Config
1. Download Expo App from PlayStores/AppStore <br/>
2. Open terminal on mobile folder <br/>
3. Run server with <code>npm start</code><br/>
4. Connect your phone through Expo<br/><br/>

<h1 align="center">
Thank you!
</h1>
<div align="center">
  <img src="readme_files/landing-page.png" alt="Ecoleta">
</div>
