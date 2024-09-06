---
title: glsl_fragment
description: loads and compiles a GLSL fragment shader into a module
categories:
  - object
pdcategory: Gem, Graphics
methods:
  - type: open <symbol>
    description: filename to load as GLSL fragment shader module
  - type: print
    description: print info about the GLSL-support in your openGL implementation

inlets:
  1st:
    - type: gemlist
      description:
outlets:
  1st:
    - type: gemlist
      description:
  2nd:
    - type: float
      description: ID of the GLSL-module
draft: false
---
