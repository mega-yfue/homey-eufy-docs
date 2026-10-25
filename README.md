# homey-eufy-docs

Publishes the help site for the Anker Eufy app on Homey at <https://mega-yfue.github.io/homey-eufy-docs/>.

**This repo contains no documentation.** Every page is generated from the app repo's `site/` folder on
each run of [`.github/workflows/pages.yml`](.github/workflows/pages.yml). Edit the pages there; the site
picks them up on the next build.

The site rebuilds nightly and on demand — Actions → `pages` → *Run workflow*.

## Setup

The app repo is private, so the workflow checks it out with a read-only deploy key. The steps are at
the top of [`pages.yml`](.github/workflows/pages.yml). Pages must be enabled with **GitHub Actions**
as its source: Settings → Pages → Build and deployment → Source.
