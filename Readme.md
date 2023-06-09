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

You can see the app working in production on [https://drone-delivery-bc93amlga-thejoaov.vercel.app/](https://drone-delivery-bc93amlga-thejoaov.vercel.app/)

## How to run locally
First, you should clone the repository with
```sh
git clone --recurse-submodules https://github.com/thejoaov/drone-delivery
```
This will clone the repositories with the submodules.

Alternatively, you can grab any update not yet pushed to this repository with
```sh
git submodule update --remote
```
After that, run both the front `web` and the backend `server` with
```sh
docker compose up
```