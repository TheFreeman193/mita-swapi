# Dummy Star Wars API for Modern IT Automation with PowerShell

This repository comprises a static implementation of the Star Wars API (SWAPI) for use with the examples from the chapter _The AAA Approach_ of [**Modern IT Automation with PowerShell**](https://leanpub.com/modernautomationwithpowershell), 1st edition.

There are six categories; films, people, planets, species, starships, and vehicles.

## Files

| Filename | Description |
|---|---|
|StarWarsData.ps1|PowerShell script containing a wrapper for searching and returning Star Wars people, planets and films|
|StarWarsData.Simple.Tests.ps1|Contains simple Pester tests|
|StarWarsData.Mocked.Tests.ps1|The same tests as Simple, but with a mocked backend _(in case the real backend is offline)_|
|StarWarsData.Complex.Tests.ps1|Contains slightly more complex Pester tests|

## Usage

Please see the [Extras repository](https://github.com/devops-collective-inc/Modern-IT-Automation-with-PowerShellExtras/edit/main/Edition-01/Starwars-Demo/README.md).

## License

The content of this repository is released under the [MIT License](./LICENSE). Please also attribute
[DevOps Collective, Inc.](https://github.com/devops-collective-inc/), the publisher of the book.
