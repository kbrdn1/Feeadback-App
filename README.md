# Feeadback-App
This is a simple project to learn Svelte and Node /w TypeScript.

## Tech Stack
### Frontend
- Svelte
- Tailwind CSS
- Iconoir

### Backend
- Node
- Express
- Mongoose
- Lodash
- Dotenv
- Cors
- Bcrypt
- Jsonwebtoken
- Nodemon

### common
- Typescript

## Installation
Run the follwing command to setup the project.

Install pnpm `npm install -g pnpm` or use `npm`
### Frontend
Go in folder `./app` and install dependencies
```sh
cd app
pnpm install
```
Run app
```sh
pnpm dev -- --open
```
### Backend
Go in folder `./backend` and install dependencies
```sh
cd backend
pnpm install
```
Environment variables
```sh
cp .env.example .env
```
and edit `.env` file
```sh
# .env
APP_URL=http://localhost:<frontend-port> # default: 5173
PORT=<port>
```

Run the server
```sh
pnpm dev
# or
pnpm build && pnpm start
```
