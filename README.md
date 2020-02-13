# HKSYU Departments Website Pimcore CMS user manual


## The document build with MkDoc
For full documentation visit [mkdocs.org](https://mkdocs.org).

## How to build?
1. You need Python3
2. Create an vitral environment\
   `virtualenv -p /usr/local/bin/python3 _env`\
   If you don't know the path, you can find it with command `which python3`
3. Active the vitral environment,
   you need to active it when strat the project everytime\
   `source _env/bin/activate`
4. Start the preview server
   `mkdocs serve`

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Deploying
1.  `mkdocs build`
2.  upload the site files to https://designquest.com.hk/docs/hksyu-departments/