# esm-download

Test case for ESM download graphs.

```bash
npm i; npm start
```

Open your browser at `http://localhost:8080`, open developer tools and check the network tab.

Because the `index.html` does not import the default or `stream` exports from `/mithril/index.js`, we would expect those imports not to have been downloaded/