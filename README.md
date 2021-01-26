# Introduction pratique à `git`

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
