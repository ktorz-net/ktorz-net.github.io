# Ktroz-net


## New Modules: 

Source of the public website: [https://ktorz-net.github.io/](https://ktorz-net.github.io).

## Prerequisites

- [MkDocs](https://www.mkdocs.org/) to generate statics pages from markdown files

## How to install?

- Install:

```
pip install mkdocs
git clone git@github.com:imt-mobisyst/imt-mobisyst.webpages.git
cd imt-mobisyst
```

- Local server:

```
mkdocs serve
```

[http://localhost:8000/](http://localhost:8000/).

<!--
## Deployement

Deployoment is achieved with a public github repository:

```
git clone git@github.com:imt-mobisyst/imt-mobisyst.github.io.git github.io
cp -R site github.io
```

You have to build the static pages with mkdocs.
You can also serve the generated website using NodeJs.

```
mkdocs build
npx http-server site
```

Local website: [http://localhost:8080/](http://localhost:8080/).

You can now commit and push the new version of the site web.

```
cd site
git restore README.md
git add *
git commit -m 'new version'
git push
```
-->