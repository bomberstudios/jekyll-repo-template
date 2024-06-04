# jekyll-repo-template

A template for Jekyll 4, deployed to GitHub Pages using GitHub Actions, with local development using Docker.

## How to use

- Create a new repository using this template.

  You can click the 'Use this template' button on the repository page, or use `degit` to use the template from the command line:

  ```shell
  npx degit bomberstudios/jekyll-repo-template my-new-repo
  ```

- Enable GitHub Pages in your repository settings, making sure it's set to use GitHub Actions as the source.
- Edit `_config.yml` with your own data.
- Edit `index.html` with your own content.
- Add more posts in `_posts`, as needed.
- Push to your repository.
- Enjoy!

## Build and run locally

```shell
docker compose up
```
