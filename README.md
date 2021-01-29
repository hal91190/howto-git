# Introduction pratique à `git`

![Build with Asciidoctor and deploy on gh-pages](https://github.com/hal91190/howto-git/workflows/Build%20with%20Asciidoctor%20and%20deploy%20on%20gh-pages/badge.svg)

## Construction du document
Pour construire le cours, les outils suivants doivent être installés sur le système.
* bundler
* graphviz

### Installation des dépendances (gems)
```
$ bundle install
```

### Construction du document
```
$ asciidoctor -r asciidoctor-diagram index.adoc
```
