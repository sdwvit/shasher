## Summary

This is a demo todo-app.

### Dependencies

This app uses express + postgraphile + next.js.

You need to have postgres database set up and running.
You may find pgsql dump file in `./server/db/create.pgsql`.

To restore make sure you have database called `shasher` and run `psql shasher < ./server/db/create.pgsql`

### Setup

0. Run `nvm use` to switch to project node 10.16.0
1. Run `yarn` to install dependencies and generate .env file.
2. Run `yarn start` to run application.
3. Go to `http://localhost:3001` using your favorite browser.

### Browsers tested

- Safari 12
- Chrome 76
- Mobile Safari 12
- Firefox 68
 
