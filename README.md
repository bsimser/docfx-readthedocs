# ReadTheDocsFX - A theme for DocFX!

[DocFX](https://dotnet.github.io/docfx/) template to create themed documentation similar to [Read the Docs](https://readthedocs.org/). This template overrides parts of the default template so you need to enable both in the `docfx.json` configuration file.

Supported DocFX version: [2.56.7](https://github.com/dotnet/docfx/releases/tag/v2.56.7)

## Changes from Default Template

* Full width (uses container-fluid instead of container)

## Installation

* Download the source from the [releases page](https://github.com/bsimser/docfx-readthedocs/releases)
* Extract the files into your root-level docfx project folder, next to your `api` and `articles` folders
* In your `docfx.json` configuration file, add `templates/readthedocsfx` path into the `build.template` property
  ```json
  {
    "build": {
      "template": ["default", "templates/readthedocsfx"]
    }
  }
* Compile your docfx project as you would normally

You can also apply the template using the command-line:
```
docfx -t default,templates/readthedocsfx
```

## Contributing

## TODO

- [ ] Add GitHub actions to publish changes to demo and release
- [ ] Add GitHub pages for demo

## Disclaimer

Notice of Non-Affiliation and Disclaimer

> We are not affiliated, associated, authorized, endorsed by, or in any way officially connected with Read the Docs, or any of its subsidiaries, partners or its affiliates. The official Read the Docs website can be found at https://readthedocs.org/. "Read the Docs", Read the Docs logos, and other Read the Docs trademarks are trademarks or registered trademarks of Read the Docs or its affiliates in the U.S. and elsewhere.
