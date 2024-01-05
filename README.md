# PAC3 EHC2

- Deployment: https://github.com/AitorSantaeugenia/PAC3_ECH2
- Repo: https://pac3-ehc2.netlify.app/

## Dependencies

``` js
  "devDependencies": {
    "@parcel/transformer-sass": "^2.9.3",
    "autoprefixer": "^10.4.15",
    "npm-run-all": "^4.1.5",
    "parcel": "^2.9.3",
    "postcss-import": "^16.0.0",
    "postcss-plugin": "^1.0.0",
    "postcss-preset-env": "^9.1.1",
    "posthtml-include": "^1.7.4",
    "precss": "^4.0.0",
    "rimraf": "^5.0.1",
    "sharp": "0.31.1",
    "tailwindcss": "^3.4.0"
  }
```

## Scripts
```js
    "parcel:serve": "parcel src/index.html -p 8123 --target web --open",
    "parcel:build": "parcel build src/index.html --target web --no-source-maps --no-cache",
    "clean": "rimraf dist .cache .cache-loader .parcel-cache",
    "dev": "npm-run-all clean parcel:serve",
    "build": "npm-run-all clean parcel:build",
    "test": "echo 'Everything is working as expected ✅\nStart working on your project by running \\033[1mnpm run dev\\033[0m'"
```