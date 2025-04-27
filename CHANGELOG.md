# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.1](https://github.com/mkaramuk/tohum/releases/tag/v0.0.1) - 2025-04-27

### Added

- initial release
- *(template)* template for node.js ts project
- include author in the pre-defined variables
- refactor and better interface
- error message if the target dir is exist
- add target-path argument for project directory customization
- add metadata reader and related structs
- change variable name in all project
- arg parser
- get template command added
- add react-ts template
- cli template for golang
- first example template for Golang CLI
- initial commit

### Fixed

- *(cargo)* remove redundant license file field
- delete metadata.json after the init is done
- *(template)* wrong go version usage
- replace project_name variable
- remove debug logs
- correct dir structure
- remove sub directory inside template
- use variables from the command line
- apply new changes to the tests
- correct error return from main
- update all variables from the files
- missing public fields from structs
- optional name extract fix

### Other

- use release-plz
- add git-cliff
- fix dagger parameters
- update cd pipeline
- add github action for CD
- .gitkeep file for changelogs dir
- change dagger directory
- dagger CI implemented
- rename the from "maker" to "tohum"
- release
- add more information fields to cargo.toml
- add new template
- fix template identifier
- split command creation to another file
- no need to use absolute path for current dir
- add comments
- update README to include custom path option for project initialization
- add .gitignore patterns and cargo lock file
- Initial commit
