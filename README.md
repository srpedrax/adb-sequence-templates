# ADB Sequence command templates

This public repository is the catalog source used by ADB Sequence:

`https://raw.githubusercontent.com/srpedrax/adb-sequence-templates/main/catalog.json`

## Catalog format

`catalog.json` is a versioned JSON document. Each template contains:

- a stable `id`, `name`, `category`, and short `description`;
- one or more `cells`, each with a shell `command` and `continueOnError` flag.

Templates are copied into the editor for review. The app never executes a template
when it is downloaded or added.

## Contributing

Keep templates focused, explain what they inspect, and avoid commands that delete,
modify, upload, or expose private data. Review every command on a test device before
opening a pull request. Do not include PINs, credentials, personal data, or device
identifiers in the catalog.
