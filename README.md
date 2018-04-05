# Installation

Install `Settings Repository` plugin: `File | Settings | Plugins | Browse repositories` -> type in `Settings Repository`.

# Configuration

In `File | Settings | Tools | Settings Repository` to Read-only Sources add `https://github.com/metyl/intellij-templates`.

Restart the IDEA and check if You have three `Demyst-`  live templates groups in `File | Settings | Editor | Live Templates`

TODO: move repo to DemystData GitHub org?

# Usage

Name of live templates should be self descriptive but please take a brief look at them.

I've try to use the same naming convention in live templates for `schema`, `source` and `test` and prefix test live schema with `a` from `assert` e.g.

`s` stand for field of type `String` so to use it type `s` in schema definition and in data provider.

To test it type `as` in data provider test.


TODO: Add list of available with descriptions.

TODO: Add live templates for all Demyst types.

TODO: Add live templates for XML based providers.

# Workflow

Copy the key/path from xls, use one of live templates it will take care of proper field name in schema, use copied value as key for in json and in test.

