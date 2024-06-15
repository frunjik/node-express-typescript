# init git repo
git init

# create server folder
mkdir server

# goto server folder
cd server

# create package.json
npm init -y

# install express and dotenv
npm i express dotenv

# install typescript
npm i -D typescript @types/express @types/node

# init typescript
npx tsc --init

# init nodemode and ts-node
npm i -D nodemon ts-node

