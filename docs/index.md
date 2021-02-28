# Building a mkdocs-site

## Creating and Setup

```sh
mkdocs new mkdocs-site
```

### Starter READme Page

```sh
curl 'https://pbrocks.work/mkdocs/mkdocs-starter.md' > README.md
```

Above is for Github; below is for MkDocs.

```sh
cp README.md about.md 
```

Search and replace `mkdocs-site` and `MkDocs Site` as necessary.

### Sample Layout Page

```sh
curl 'https://jaspervdj.be/lorem-markdownum/markdown.txt' > docs/layout.md
```

### mkdocs.yml

```yml
site_name: MkDocs Site Title
nav:
    - Home: index.md
    - About: about.md
    - Layout: layout.md
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

- [Heading](#heading)
  * [Sub-heading](#sub-heading)
    + [Sub-sub-heading](#sub-sub-heading)
- [Heading](#heading-1)
  * [Sub-heading](#sub-heading-1)
    + [Sub-sub-heading](#sub-sub-heading-1)
- [Heading](#heading-2)
  * [Sub-heading](#sub-heading-2)
    + [Sub-sub-heading](#sub-sub-heading-2)


# Heading levels

> This is a fixture to test heading levels

<!-- toc -->

## Heading

This is an h1 heading

### Sub-heading

This is an h2 heading

#### Sub-sub-heading

This is an h3 heading

## Heading

This is an h1 heading

### Sub-heading

This is an h2 heading

#### Sub-sub-heading

This is an h3 heading

## Heading

This is an h1 heading

### Sub-heading

This is an h2 heading

#### Sub-sub-heading

This is an h3 heading
