# Parse Markdown to AnnotatedString

This is based on Erik Hellman's work here: [MarkdownComposer](https://github.com/ErikHellman/MarkdownComposer),
but tweaked to decouple the Markdown parsing from rendering, leveraging AnnotatedStrings, and
delegating the rendering to Compose's Text().

Pretty rough cut so far, with a lot of Erik's code still present, serves only as a PoC built on top
of another PoC 😅