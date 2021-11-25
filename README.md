# pages-playgound
<<<<<<< HEAD
Repository to play with github pages and learn how they work

See <https://imker25.github.io/pages-playgound>, to see what gets rendered during the rendering.

## Chapter 1

See how `*.md` files gets converted.

Add a image:
![Screenshot of a terminal](./img/Console.png)

A lot of stuff that needs special **jekyll plugins**, like [mermaid](https://mermaid-js.github.io/mermaid/#/) will not work with the standard workflow since they need *unsafe* plugins. Thats why we use a own combination of github actions to get the docs created.

Work with code:

```bash
#!/bin/bash
mkdir -p ./tmp
ls -l ./tmp
```
