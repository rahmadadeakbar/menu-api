# menu-api

# Get Starts with TypeScript in Node.js
- Bootstrap a Node.js Project

# Install Project Dependencies

Here's what each of the above packages does in your project:

express: Fast, unopinionated, minimalist web framework for Node.js.

dotenv: Zero-dependency module that loads environment variables from a .env file into process.env.

cors: Express middleware to enable CORS with various options.

helmet: Express middleware to secure your apps by setting various HTTP headers, which mitigate common attack vectors.

To use TypeScript, you also need to install a stable version of typescript as a developer dependency:

npm i -D typescript

# Initialize TypeScript in Node.js
To help the TypeScript compiler understand your project's structure, you need to create a tsconfig.json file within the directory you want to use as the root directory of the TypeScript project. In this case, your project directory and the TypeScript project directory are the same.

To easily generate the tsconfig.json file, ensure that you are under the project directory and issue the following command:

npx tsc --init
That's all that you need for now to configure your TypeScript project with sensible defaults.

# Use Environmental Variables


# Create an Express App with TypeScript



# Test the API with the Demo Client
You can use a demo application, the WHATABYTE Dashboard, to interact with your Menu API like any user would. The demo application lets you enable and disable its authentication features.

Since you have not yet implemented authorization in your API to protect your endpoints, you'll use the demo client without any authentication features, which allows you to perform read and write operations on your Menu API as an anonymous user.

Set up the demo client application
Head to https://dashboard.whatabyte.app to open the demo client. If this is your first time using this client application, the Auth0 Demo Settings view will open up.


# get all items
GET /api/menu/items

# get a single item using an id parameter
GET /api/menu/items/:id

# create an item
POST /api/menu/items

# update an item using an id parameter
PUT /api/menu/items/:id

# remove an item using an id parameter
DELETE /api/menu/items/:id