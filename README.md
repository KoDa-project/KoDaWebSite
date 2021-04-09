# KoDaWebSite
This repository is used to create the contents of the KoDa web page.

All files related to the design, implementation as well as content for the KoDa web site can be found in this repository.

The website files can be found in the directory [content](./content). 

# Web site structure

The hierarchy of the website can be seen below

```
index.md
│
├── KoDaDatabase.md
│
├── KoDaAPI.md
│   └── Links to Swagger API documentation
│
└── examples.md
    └── Links to Jupyter Hub server with interactive examples
```

# Testing the website

To render the website locally, run `hugo -server -config=./config/config.toml`