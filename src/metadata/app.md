---
layout: ontology_detail
id: app
title: Apples
jobs:
  - id: https://travis-ci.org/nkauxue/apples
    type: travis-ci
build:
  checkout: git clone https://github.com/nkauxue/apples.git
  system: git
  path: "."
contact:
  email: cjmungall@lbl.gov
  label: Chris Mungall
description: Apples is an ontology...
domain: stuff
homepage: https://github.com/nkauxue/apples
products:
  - id: app.owl
  - id: app.obo
dependencies:
 - id: po
 - id: ro
 - id: pato
tracker: https://github.com/nkauxue/apples/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

Enter a detailed description of your ontology here
