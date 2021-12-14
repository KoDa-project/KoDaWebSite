# KoDaWebSite

This repository was used to create the contents of the KoDa web page while waiting for it to be published on Trafiklab.
The website files can be found in the directory [content](./content).

# Web site structure

All documentation goes into /content/data/. News goes into /content/news/, use cases go into /content/cases/. Each
folder should include an _index.md file to correctly detect the site structure. Each file contains front-matter,
separated from the main content by 3 dashes (---). The front matter should always at least include a title. 

The hierarchy of the website can be seen below

```
content/koda
│
├── _index.md : documentation landing page
│
├── koda-api
│   └── _index.md for menu structure
│   └── content pages
├── jupyter-hub
│   └── _index.md for menu structure
│   └── content pages
```
