# parcel-hmr-on-external-http-server-test

- `npm run clean` = delete `./dist` directory
- `npm run copy` = copy `./src/index.html` to `./dist` (and create the directory)
- `npm run build` = first run `npm run clean` and `npm run copy`, then do a Parcel build (`parcel build ./src/index.js`)
- `npm run prewatch` = npm run build",
- `npm run watch` = first run `npm run build`, then run Parcel in watch mode (`parcel watch ./src/index.js`)
- `npm run serve` = run HTTP-server (without any specialities, e.g. `http-server ./dist`)
- `npm start` = first do a build (`npm run build`), then start HTTP-server and Parcel watch mode concurrently (`npm-p watch serve`)