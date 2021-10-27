# stepzen-spectaql-docs

Create static documentation for your GraphQL with [StepZen](https://stepzen.com/) and [SpectaQL](https://github.com/anvilco/spectaql)! You can find a full explanation of how to do this by reading the article [Creating Static Documentation For GraphQL APIs Using GraphQL SDL
](https://stepzen.com/blog/creating-static-documentation-for-graphql-apis-using-graphql-sdl).

## Getting started

Before you get started, you'll need to get yourself a [StepZen account](https://stepzen.com/request-invite) and install the [StepZen CLI](https://stepzen.com/docs/quick-start).

After creating an account you can clone the repository and move into the newly created directory on your local machine. Here you must start the GraphQL server by running `stepzen start`. This will make a GraphQL server with the GraphQL schemas from this repository. Make sure to replace the variables `stepzen_api_endpoint` and `stepzen_api_key` with your own.  

To create the documentation you must run `npx spectaql -D config.yml` to create the static documentation with SpectaQL based on the StepZen GraphQL API and the SpectaQL configuration in `config.yml`. The output will be a static website that you can find in the `public` directory.



