## LiReddit

NOTE: This is an actively maintained repo. This README file also contains detailed notes on steps taken to build the project. Following this with the code must make it easier to learn.

### Yarn dependencies

Yarn is embedded in Node >= 16.0. Just do:

```
corepack enable
yarn init -2
```

To install Typescript, do:

```
yarn add -D @types/node typescript
```

#### To run TS at start

Add a start script in package.json as:

```
"start": "ts-node src/index.ts"
```

Then install a global package by

```
npm install -g ts-node
```
