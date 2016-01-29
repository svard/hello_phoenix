# HelloPhoenix

Proof of concept app for using Phoenix channels in Elm with the [elm-phoenix](https://github.com/svard/elm-phoenix) package.

Based on the [Phoenix framework guide](http://www.phoenixframework.org) app but with the client written in Elm.

To start your Phoenix app:

  * An existing installation of Elm 0.16 is required
  * Install dependencies with `mix deps.get`
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

It is required to put

```
"svard/elm-phoenix": "2.0.0 <= v < 3.0.0"
```

as a dependency in the elm-package.json file to make Elm recognise the elm-phoenix package. But since this package is not yet installable by the Elm installer all Elm dependencies are provided in this repo.

The Elm client is located in web/static/elm/Chat.elm.

The Elm code is compiled using the elm-brunch plugin. How it is configured can be seen in brunch-config.js.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: http://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
