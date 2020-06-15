# UCSF Enterprise Calendar SILK template


[SILK](http://support.localist.com/article/227-article) template for [UCSF's enterprise calendar](http://ucsf.enterprise.localist.com).

## Local installation for development

1. Install node packages
    ```bash
    npm ci
    ```
2. Watch scss files and compile to css.
    ```bash
    npm start
    ```

### Optional Jekyll Development
1. Install [Jekyll](http://jekyllrb.com/).
2. From within your local repository root, run Jekyll.

    ```bash
    jekyll serve --watch
    ```
3. Visit `localhost:4000` in your browser.


## Deployment

1. Merge you changes into the `gh-pages` branch, and they will be automatically deployed to [GitHub Pages](http://ucsf-web-services.github.io/ucsf-localist-silk/). This may take up to a few minutes.
2. Once the changes have propagated to GH Pages, [update your SILK wrapper](http://support.localist.com/article/89-article) on Localist.
