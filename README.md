# React Berry Dashboard `full-stack`

Full-Stack Seed project generated by **[React App Generator](https://appseed.us/generator/react/)** top of *Berry Dashboard* design. The backend logic is provided by a simple, `easy-to-extend` API Server that manages the Authentication flow (login, registration, logout) using `JSON Web Tokens` (JWT).

<br />

> 🚀 Build Timestamp `2022-10-13 17:47`

- **React Frontend**: `Berry Dashboard` (open-source)
  - `M-UI` based design
  - Modern aesthetics UI design - Designed by *[CodedThemes](https://bit.ly/37fF9RT)*
  - React, Redux, Redux-persist

- **API Backend Server**: `NodeJS` / `Express` / **SQLite** 
  - `TypeScript`, Joy for validation
  - **DB Layer**: `TypeORM`, `SQLite` persistence
  - **Auth**: Passport / `passport-jwt` strategy
  - [API Definition](https://docs.appseed.us/boilerplate-code/api-unified-definition) - the unified API structure implemented by this server


<br />

> Links

- 👉 [React Berry Dashboard](https://react-node-js-berry-dashboard.appseed-srv1.com/) - LIVE Demo (from a similar product)

- 👉 **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`
- ✅ [PRO Version Available](#pro-version) - `enhanced UI` and more `features`

<br />

![React Berry Dashboard - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/174480640-e0b450b1-07a8-4cc7-84bc-287bb9c45773.png)

<br >

## ✨ How to use it

Being a full-stack product, the backend and the frontend should be compiled and started separately. 
Before starting to compile the product, make sure you have the following tools installed in the environment:

- [NodeJS](https://nodejs.org/en/) - version `14.x` or higher
- [GIT](https://git-scm.com/) - used to clone tjhe sources from Github
- [Python3](https://www.python.org/) - used in many tools

<br />

### 👉 Start the Frontend 

> **Step 1** - Once the project is downloaded, change the directory to `react-ui`. 

```bash
$ cd react-ui
```

<br >

> **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step 3** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

At this point, the app is available in the browser `localhost:3000` (the default address).


<br /> 

### 👉 Start the Backend Server 

> **Step 1** - Change the directory to `api-server-nodejs`

```bash
$ cd api-server-nodejs
```

<br >

> **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step 3** - Run the SQLite migration via TypeORM

```bash
$ npm run typeorm migration:run
// OR 
$ yarn typeorm migration:run
```

<br />

> **Step 4** - Start the API server (development mode)

```bash
$ npm run dev
// OR
$ yarn dev
```

The API server will start using the `PORT` specified in `.env` file (default 5000).

<br /> 

## 👉 Codebase Structure

```bash
< ROOT / src >
     | 
     |-- config/                              
     |    |-- config.ts             # Configuration       
     |    |-- passport.ts           # Define Passport Strategy             
     | 
     |-- migration/
     |    |-- some_migration.ts     # database migrations
     |
     |-- models/                              
     |    |-- activeSession.ts      # Sessions Model (Typeorm)              
     |    |-- user.ts               # User Model (Typeorm) 
     | 
     |-- routes/                              
     |    |-- users.ts              # Define Users API Routes
     | 
     | 
     |-- index.js                   # API Entry Point
     |-- .env                       # Specify the ENV variables
     |                        
     |-- ************************************************************************
```

<br />

## 👉 SQLite Path

The SQLite Path is set in `.env`, as `SQLITE_PATH`

<br />

## 👉 Database migration

> Generate migration:

```bash
$ yarn typeorm migration:generate -n your_migration_name
```

> run migration: 

```bash
$ yarn typeorm migration:run
```

<br />

<br />

## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Berry Dashboard is a premium React Design now available for download as a full-stack app. Made of hundred of elements, designed blocks, and fully coded pages, Berry Dashboard PRO is ready to help you create stunning websites and web apps.

- 👉 [React Berry Dashboard PRO](https://appseed.us/product/berry-dashboard-pro/full-stack/) - Product Page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![React Berry Dashboard PRO - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/174492378-280b6de6-df58-4df7-865d-f86f6e9b1dd0.png)

<br />

---
**React Berry Dashboard** - Full-Stack Seed project generated by **[App Generator](https://appseed.us/generator/)**.
