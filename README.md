# Interpretation Course

[![CircleCI](https://circleci.com/gh/connectedacademy/interpretation/tree/master.svg?style=svg)](https://circleci.com/gh/connectedacademy/interpretation/tree/master)


Structure and content for the Test Class, for Connected Academy development.

## Build Step

The files in this repo should be edited using http://prose.io.

After each commit, the build script runs and checks the content is valid, then deploys the content to the gh-pages branch, which is hosted on GitHub pages, and served by a CDN.


## Creating a new course

Step 1 - Clone this repo - replace all occurences of previous course with the new name and domain of the course

Step 2 - Add domain (as CNAME) to cloudflare.com so that it aliases connectedacademy.github.io

Step 3 - Update GitHub Pages configuration on GitHub to point to custom domain