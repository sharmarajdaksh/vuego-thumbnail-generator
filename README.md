# VUEGO-THUMBNAIL-GENERATOR

To run, generate an api token from [here](https://screenshotapi.net) and place it in a file named .env in the project root.
```
SCREENSHOTAPI_TOKEN=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

Then, to run the app, run:
```
go run .
```

Note: The app serves from the vue build (that is, the dist folder). So, in case you make any changes in the frontend, you'll need to rebuild the vue app with:
```
cd vuego-thumbnail-generator
npm install
npm run build
```