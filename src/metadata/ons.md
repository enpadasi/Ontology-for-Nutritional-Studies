---
layout: ontology_detail
id: ons
title: ons
jobs:
  - id: https://travis-ci.org/obophenotype/ons
    type: travis-ci
build:
  checkout: git clone https://github.com/obophenotype/ons.git
  system: git
  path: "."
contact:
  email: cjmungall@lbl.gov
  label: Chris Mungall
description: ons is an ontology...
domain: stuff
homepage: https://github.com/obophenotype/ons
products:
  - id: ons.owl
  - id: ons.obo
dependencies:
 - id: ro
tracker: https://github.com/obophenotype/ons/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

Enter a detailed description of your ontology here
