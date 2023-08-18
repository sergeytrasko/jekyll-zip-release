# Jekyll site built and released as ZIP file

## Use Case

Imagine you have a documentation in markdown format that you want to publish.

One of the option is to publish it to [Github Pages](https://pages.github.com/), however it might not be possible due to security or other issues.

Alternative is to build it as Jekyll-based bundle and package it as ZIP release.

## How to add to project

**Assumption**: your documentation is already Jekyll-ready

Just copy [release.yml](.github/workflows/release.yml) to your project.

## When it is executed

The workflow is executed once a new GIT tag is created/pushed.

## How to use the release

Go to `releases` section and download `release.zip` file.

Extract it - the content will be set of HTML/CSS/JS files.

Either upload it to your hosting, or run a [web server locally](https://flaviocopes.com/local-web-server/).

Enjoy!

