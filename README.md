# pages-playgound

Repository to play with github pages and learn how they work 

## Chapter 1

See how `*.md` files gets converted.

Add a image:
![Screenshot of a terminal](./img/Console.png)

Add mermaid support by adding the following to `_config.yml`:

```yaml
plugins:
  - jekyll-spaceship
```

Add a diagram:

```mermaid!
pie title Pets adopted by volunteers
  "Dogs" : 386
  "Cats" : 85
  "Rats" : 35
```
