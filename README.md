# new parcel app

use this as an app template usig the parceljs bundler

## npm scripts


    "dev:clean": "rimraf build/dev",
    "dev:open": "parcel src/index.html --out-dir build/dev --open",
    "dev": "npm run-script dev:clean && npm run-script dev:open",
    "prebuild": "rimraf build/dist",
    "build": "parcel build src/index.html --out-dir build/dist"
