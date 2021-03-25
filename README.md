# docgen

[![Go Report Card](https://goreportcard.com/badge/docgen)](https://goreportcard.com/report/docgen)

Auto-generate routing documentation in JSON, Markdown, or Markup (HTML) for a `chi` Router from your app source.

* Tests generated by [cweill/gotests](https://github.com/cweill/gotests)
* Vendoring with [github.com/tools/godep](https://github.com/tools/godep)
* Using Go [.gitignore Template](https://github.com/github/gitignore/blob/master/Go.gitignore)
* Code Screenshot made with [Carbon](https://carbon.now.sh)

## fork info

* Building HTML generation
  * Templates built, passing tests
  * HTML Generator is being built, not yet functional (3/18/2018)
    * 85% complete
    * 15% remaining: String building for routes, middleware, handlers & related tests
  * Configuration obj

Check markup.go & markupTemplates.go for new code, started from a copy of markdown.go.

Build:

    go build

Test:

    go test
    go test docgen/raml

Use:

See [an example use of the Markdown Generator](https://github.com/go-chi/chi/blob/master/_examples/rest/main.go#L105)

![Example Screenshot](carbon.png)