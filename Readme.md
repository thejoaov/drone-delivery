# Drone Delivery App

This app is made with
- Web:
  - ViteJS + SWC
  - React
  - Typescript
  - Testing (70% unit coverage)
- Backend Server
  - NestJS
  - Typescript
  - Testing (100% unit/e2e coverage)
- Docker

## How to run
First, after cloning the repository, clone the submodules with
```sh
git submodule update --init --recursive
```
After that, run both the front `web` and the backend `server` with
```sh
docker compose up
```