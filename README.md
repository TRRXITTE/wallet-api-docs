# walletAPI-docs
This is a very lightly tweaked version of https://github.com/swagger-api/swagger-editor for our use case.

## Running

Visit https://traaittplatform.github.io/wallet-api-docs/

Or, if developing locally, simply open `index.html` in your web browser

## Updating the documentation

Modify the swagger.json file. You may wish to use http://editor.swagger.io/ to preview how your changes will look (Import as yaml - easier to modify - then export as JSON)

## Updating dist folder after changes

`npm i` (Only the first time)

`npm run-script build`
