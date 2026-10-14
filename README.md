# Movie search

A React page that lists movies from TMDB. One running copy is at https://moviedb-react-1.netlify.app/.

On load, `src/App.js` fetches popular movies and `src/MovieBox.js` draws each one in a four-column grid. The card shows the poster and a View More button. View More opens a dialog with the poster, the title, the vote average labeled IMDb, the release date, and the overview. Posters come from TMDB at width 500.

Search submits the text in the box and replaces the grid with those results. An empty list shows `Sorry !! No Movies Found`.

The popular request and the search request use two different API keys. Both are written in `src/App.js`. MovieDb App and Trending in the bar link to `/home`. The app is this one page, so those links leave it.

## Run

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000).

`npm test` starts the test watcher. `npm run build` writes the production build. `npm run eject` copies the build config into the project, and that copy cannot be undone.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). The references from that README:

- [Running tests](https://facebook.github.io/create-react-app/docs/running-tests)
- [Deployment](https://facebook.github.io/create-react-app/docs/deployment)
- [Getting started](https://facebook.github.io/create-react-app/docs/getting-started)
- [React](https://reactjs.org/)
- [Code splitting](https://facebook.github.io/create-react-app/docs/code-splitting)
- [Analyzing the bundle size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)
- [Making a progressive web app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)
- [Advanced configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)
- [npm run build fails to minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
