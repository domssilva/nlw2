<h1 align="center">Proffy</h1>
<p align="center">
  <a href="https://opensource.org/licenses/MIT" target="_blank">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>
<p align="center">
    <img src="./ReadmeAssets/layout.png" alt="project banner">
</p>

Proffy is an online educational platform to connect teachers and students, allowing them to schedule lessons according to the selected time and price.

# The Extra Mile
As a challenge, these are the features I implemented by myself to extend the original application:

|                                    Feature                                  |  commit    |
| --------------------------------------------------------------------------- | ---------- |
|  (Backend):  Create DB Seed with Knex                                       | [eecd...](https://github.com/domssilva/NextLevelWeek2/commit/eecd9991581f6ffa4d210844a11976050cdeae28#diff-469bba0a564235dfceede42db14f17b0) |
|  (Backend):  Create utility with Faker to generate teachers                 | [a5c2...](https://github.com/domssilva/NextLevelWeek2/commit/a5c25399b102df904868c2a64be27f37badbb1a9#diff-469bba0a564235dfceede42db14f17b0) - [3571...](https://github.com/domssilva/NextLevelWeek2/commit/35717238936f692318f4f3f639a8025c83b35109) |
|  (Backend):  Create new route to fetch all registered teachers              | [880c...](https://github.com/domssilva/NextLevelWeek2/commit/880c03c219310790afc4c6d39f81c82a22dd409c) |
|  (Backend):  Create index route to document API                             | [5e84...](https://github.com/domssilva/NextLevelWeek2/commit/5e84559c8382cd54c9b4b87cb3c8a8b0c05b797a) |
|  (Frontend): Create a profile page where you can verify all registered proffys| [5f8e...](https://github.com/domssilva/NextLevelWeek2/commit/5f8e92477dbb1b8a91060ae18b21df7606ff5f2f) |


#### New Routes:

##### API Documentation
<img src="./ReadmeAssets/apidocs.png" alt="project banner">

##### /teachers
<img src="./ReadmeAssets/teachers_route.png" alt="project banner">

#### New Page to see all registered Proffys (teachers):
<img src="./ReadmeAssets/fenewpage.png" alt="project banner">

# Technical Overview

<h3 id="tech" >🧰 Tech Stack</h3>

- ⚛️ **react.js** — A JavaScript library for building user interfaces.
- ⚛️ **react native** — A JavaScript framework for writing natively rendering mobile applications for iOS and Android.
- 🔷 **Typescript** — A typed superset of JavaScript that compiles to plain JavaScript.
- 💹 **Node.js** — A JavaScript runtime built on Chrome's V8.
- 💼 **Express** — A fast, flexible and minimalist web framework for Node.js.
- 🦢 **sqlite3** — A small, fast, self-contained, high-reliability, full-featured, SQL database engine.
- ⚓ **knex** — SQL query builder designed to be flexible, portable, and fun to use.

<h3 id="setup">🔧 Setup</h3>
1. clone this repo:

```bash
    git clone https://github.com/domssilva/NextLevelWeek2
```

<h3 id="server">💻 Server</h3>
1. set up server:  

```bash
    cd NextLevelWeek2/back/
```

```bash
    npm install
```

```bash
    npm run dev #launches ts-node-dev
```

<h3 id="client">💻 Client</h3>

3. set up client:
```bash
    cd NextLevelWeek2/front/
```

```bash
    npm install
```

```bash
    npm start
```

<h3 id="client">📱 Mobile</h3>
1. set up mobile:

```bash
    cd NextLevelWeek2/mobile/
```

```bash
    npm install
```

```bash
    npm start  #launches expo
```

# 🚀 Credits

This project was created by [Rocketseat](https://rocketseat.com.br/).
