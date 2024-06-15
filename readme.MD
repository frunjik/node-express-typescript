# setup express for typescript

## init git repo
git init

## create server folder
mkdir server

## goto server folder
cd server

## create package.json
npm init -y

## install express
npm install express --save

## install dotenv
npm install dotenv --save

## install typescript
npm i -D typescript @types/express @types/node

## init typescript
npx tsc --init

## init nodemode and ts-node
npm i -D nodemon ts-node
