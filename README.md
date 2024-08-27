[![Deploy Hugo site to Pages](https://github.com/adintegra/til/actions/workflows/hugo.yaml/badge.svg)](https://github.com/adintegra/til/actions/workflows/hugo.yaml)

## Usage

New posts get published on push to `main`.

Normally, you'd be able to create new posts by doing something like this to create a new post:

```sh
hugo new content/til/post.md
```

Hugo [0.133.0](https://github.com/gohugoio/hugo/releases/tag/v0.133.0) introduced some breaking changes and while the md file for the content is generated, it doesn't contain the template front matter anymore 🤷‍♂️

## Theme

Refer to [https://github.com/alex-shpak/hugo-book](https://github.com/alex-shpak/hugo-book) for documentation on the Theme.
