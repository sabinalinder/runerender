# Runerender

## A frontend for the small business
This frontend is made by and for small businesses that want an efficient and optimized site with ecommerce and a blog.
It will work like a charm together with the backend Magiquill but can be used with any backend you want.

# Getting started

## Installation
Note: If you want to run Runerender on docker, you can skip to Installation - Docker after step 1 below.

### 1. Clone the repository
Clone the repository from github:
```bash
git clone git@github.com:sabinalinder/runerender.git
```

### 2. Set node version
Version 18 or above is required for this project. Check your version with node -v.
nvm is recommended for node version handling.

### 3. Install dependencies
Install dependencies:
```bash
yarn install
```

### 4. Start it up!
Start up the project. It will automatically open in your browser at http://localhost:4321/.
```bash
yarn run dev
```

## Docker
### Start 
```bash
docker compose up --build
```

### Stop
Stop and clean up.
```bash
docker compose rm --volumes --force
```