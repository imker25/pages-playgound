# pages-playgound

Repository to play with github pages and learn how they work

See <https://imker25.github.io/pages-playgound>, to see what gets rendered during the rendering.

## Markdown

See how `*.md` files gets converted.

A lot of stuff that needs special **jekyll plugins**, like [mermaid](https://mermaid-js.github.io/mermaid/#/) will not work with the standard workflow since they need *unsafe* plugins. Thats why we use a own combination of github actions to get the docs created.

Work with code:

```bash
#!/bin/bash
mkdir -p ./tmp
ls -l ./tmp
```

The readme now is stored in the `docs` folder and linked to the repositories root, since the mkdocs action will not follow links.

### Mermaid diagrams

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
