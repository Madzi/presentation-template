# Template for Presentation

This project contains template for presentations.

Presentation slides represents into `src/asciidoc/index.adoc` document.

The first level header represent title slide for presentation.

```adoc
= Presentation Title
Some text for this slide
```

The second level header represent top level slides into presentation.
Navigation between top level slides is made by left and right arrows.

```adoc
== Top level slide
Text for top level slide
```

The third (, fourth, fifth, etc...) level header represent subslides.
Navigation from top level slide to subslides is made by up and down arrows.

## Precompile

To check project compilation can be used command:

```sh
mvn asciidoctor:process-asciidoc
```

## Presentation

The presentation will be accessible from browser after run presentation server:

```sh
mvn asciidoctor:http
```

Now presentation can be opened as [local site](http://localhost:2000)
