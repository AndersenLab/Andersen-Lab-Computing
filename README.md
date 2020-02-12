# [Andersen Lab Dry Guide](http://andersenlab.org/dry-guide/)

The Andersen lab [dry-lab computing guide](http://andersenlab.org/dry-guide/). The guide is built with [mkdocs](http://www.mkdocs.org/).

## Editing the site

1. Clone the repo
1. Make changes. Local editing can be done using `mkdocs serve`, after you have installed `mkdocs`.
1. Push changes to the master branch on github.
1. A github actions workflow will build the site.

## Versioning the site

If you are:

* Removing sections
* Adding new sections
* Making substantial changes to sections

Consider creating a new 'version' of the documentation, so people can see prior versions.

In the file `.github/actions/deploy_mkdocs.yml`, update the `$VERSION` variable to today's date and push your changes.
