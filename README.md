## Introduction

Drupal 8 Context condition plugin that determines if a node has any members. Specifically, it executes the "Manage Members" View provided by the Islandora module and counts the results.

Note that this repo is a temporary home until this plugin is included in the base Islandora module, is packaged in its own module, etc. See the discussion at https://github.com/Islandora-CLAW/CLAW/issues/396 for more detail.

Also note that Context Conditions now show up in all block visibility settings. This is [standard](https://www.drupal.org/node/2287827) Drupal 8 behavior.

## Requirements

* [Islandora](https://github.com/Islandora-CLAW/islandora) a.k.a. CLAW

## Installation

This plugin needs to be placed in your Islandora site's `web/modules/contrib/islandora/src/Plugin/Condition` directory.

## Configuration

Works like any other Context condition. However, to limit this condition to Islandora objects, use it in conjuction with either the Node Bundle or Entity Bundle conditions provided by the core Islandora module, and be sure to check "Require all conditions."

## Maintainer

Mark Jordan

## License

[GPLv2](http://www.gnu.org/licenses/gpl-2.0.txt)
