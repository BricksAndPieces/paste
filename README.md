# Paste
A completely client side pastebin service. The contents of the paste are compressed into the URL of the paste using [LZMA](https://github.com/LZMA-JS/LZMA-JS) for compression.

Pros:
- No need for a server
- No data losss associated with the website going down (you can always decompress the url using another program)
- Privacy (all client side)

Cons:
- Long urls

> Note: This paste is a version of topaz's [paste](https://github.com/topaz/paste) with some improvements. 

The paste includes [CodeMirror](https://codemirror.net/) which allows for syntax highlighting and theming similar to IDE's. This allows the paste to syntax highlight 150+ coding lanuages. This makes it nicer to share code snipets with this paste.
