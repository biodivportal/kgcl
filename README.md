# KGCL: Knowledge Graph Change Language

KGCL is a standard datamodel for representing changes in ontologies and knowledge graphs.

This repository houses:

- The KGCL schema/standard
- The Python implementation of the standard (LinkML model, LARK grammar)

The following URIs will resolve to the KGCL standard:

- OWL: https://w3id.org/kgcl/kgcl.owl.ttl
- JSONLD: https://w3id.org/kgcl/kgcl.context.jsonld
- SHACL: https://w3id.org/kgcl/kgcl.shacl.ttl
- YAML: https://w3id.org/kgcl/kgcl.yaml

## Documentation

[Read more here.](https://incatools.github.io/kgcl/)

## How to run project locally
install python 3.9, using mise (optional), get mise from [here](https://mise.jdx.dev/)
```bash
mise install python 3.9
```
install poetry
```bash
pip install poetry
```
install dependencies
```bash
poetry install
```
run tests
```bash
poetry run pytest
```
