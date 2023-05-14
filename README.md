# Animal Farm

A sample Express application written in Node.js for a Github README post.

##  Prerequisites

* Node.js
* yarn

### Install modules

Run `yarn` to install the required node modules.

```shell
yarn install
```

## Running

You can run the sample app in a couple of different ways. The first is to launch the application via `yarn`:

```shell
yarn start
```

Or you can directly run it via `node`:

```shell
node app.js
```

## Tests

You can also run the tests via `yarn`:

```shell
yarn test
```
## to try the workflow
  - modify the app
  - create a project in render 
  > https://render.com/
  - create an api key from you account settings 
  > https://dashboard.render.com/u/"youruserGoesHereId"/settings
  - get the deploy hook from the app in the app settings
  - create two secrets in you github repository one with the name RENDER_API_KEY and paste the api key there
  the second variable is SERVICE_ID 
  > only paste the frist parameter of the deploy hook it starts with srv- and finish in the start of the querystring
  - **push to your repository**