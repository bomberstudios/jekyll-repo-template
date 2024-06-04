# jekyll-repo-template

A template for Jekyll 4, deployed to GitHub Pages using GitHub Actions, with local development using Docker.

This project supports plugins and other features that are not available in the default GitHub Pages environment. For example, it installs the `jekyll-default-layout` plugin to set a default layout for all pages, and the excellent [Just the Docs](https://just-the-docs.com/) theme.

## How to use

- Create a new repository using this template by clicking the 'Use this template' button, or running `degit` from a command line:

  ```shell
  npx degit bomberstudios/jekyll-repo-template my-new-repo
  ```

- Enable GitHub Pages in your repository settings, making sure it's set to use GitHub Actions as the source.
- Edit `_config.yml` with your own data (see <https://just-the-docs.com/docs/configuration/> for more information).
- Edit `index.html` with your own content.
- Add more posts in `_posts`, as needed.
- Push to your repository.
- Enjoy!

## Build and run locally

```shell
docker compose up
```
