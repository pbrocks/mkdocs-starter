# Building a mkdocs-site

## Creating and Setup

```sh
mkdocs new mkdocs-site
```

### Starter READme Page

```sh
curl 'https://pbrocks.work/mkdocs/mkdocs-starter.md' > README.md
```

### Sample About Page

```sh
curl 'https://jaspervdj.be/lorem-markdownum/markdown.txt' > docs/about.md
```

### mkdocs.yml

```yml
site_name: Site Title
nav:
    - Home: index.md
    - About: about.md
theme: readthedocs
```

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Structure

### Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

### Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
