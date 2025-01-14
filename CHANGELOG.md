# Changelog

All notable changes to this project will be documented in this file.

## [0.4.1] - 2023-08-28

### Bug Fixes

- *(docs)* Add missing flags to README
- Properly check if a file exists before generating


## [0.4.0] - 2023-08-26

### Bug Fixes

- *(bench)* Use the new Scaffolder struct


### Features

- *(cli)* Pass solidity version as an arg (#17)


### Refactor

- *(scaffold)* Add a Scaffolder struct replacing scaffold


## [0.3.0] - 2023-08-25

### Features

- Add support for the 'given' keyword (#16)


## [0.2.2] - 2023-08-24

### Bug Fixes

- *(cli)* Stop overwriting output files (#15)


## [0.2.1] - 2023-08-24

### Bug Fixes

- *(emit)* Use foundry's naming practices for tests (#13)
- *(emit)* Co-locate modifiers with test functions (#14)


### Documentation

- *(README)* Update BTT reference tweet (#5)


### Features

- *(bench)* Add benchmarks using the criterion crate (#6)


## [0.2.0] - 2023-08-10

### Bug Fixes

- *(docs)* Fix typo in README


### Features

- *(docs)* Add logo to README
- Start using git-cliff
- Introduce the Compiled struct to allow setting the output file


### Miscellaneous Tasks

- Generate CHANGELOG.md


### Refactor

- *(docs)* Add missing tag to README


## [0.1.1] - 2023-08-06

### Bug Fixes

- *(README)* Fix typo
- *(tests)* Remove ticks from identifiers
- Support the ~/code/rust character in identifiers
- Support ticks in identifiers


### Miscellaneous Tasks

- Update pkg version


### Refactor

- *(docs)* Update README's example indentation
- *(lint)* Appease clippy


## [0.1.0] - 2023-08-05

### Bug Fixes

- *(cargo)* Update keyword length
- *(ci)* Set proper permissions for clippy
- *(emitter)* Maintain modifier order
- *(emitter)* Remove unnecessary extra space after
- *(parser)* Proper parsing cadence
- *(parser)* Properly parse based on indentation
- *(parser)* Parse filenames with an extension
- *(tokenizer)* Restrict possible character in WHEN/IT blocks
- *(tokenizer)* Start rework to parse filenames and identifiers
- *(tokenizer)* Finish rework to parse filenames and identifiers
- *(tokenizer)* Properly parse filenames
- Support all characters in strings for now


### Features

- *(bulloak)* Initial commit
- *(cargo)* Add missing metadata to Cargo.toml
- *(docs)* Add comments all over the place
- *(docs)* Add commentary to the parser
- *(docs)* Add commentary to the emitter
- *(docs)* Add commentary to semantic analysis
- *(docs)* Add README skeleton
- *(docs)* Add a CONTRIBUTING.md file
- *(docs)* Add documentation to lib.rs
- *(docs)* Update README
- *(docs)* Add doc comment to
- *(emitter)* Add modifier discoverer
- *(emitter)* Add solidity test emitter
- *(emitter)* Add test for edge cases
- *(emitter)* Test emitter flags
- *(error)* Implement nice error formatting
- *(error)* Improve error formatting
- *(parser)* Start parser implementation
- *(semantics)* Add a simple semantic analyzer
- *(tests)* Add unit tests for comments
- *(visitor)* Add the visitor trait
- Add tokenizer
- Properly setup bin entrypoint
- Add the --write-files option


### Refactor

- *(ast)* Remove unused Empty variant
- *(emitter)* Rename with_comments -> with_it_as_comments
- *(error)* Update error kind naming convention
- *(fmt)* Fix formatting
- *(semantics)* Simplify types a bit
- *(tests)* Revamp tokenizer tests
- *(tokenizer)* Remove the TokenStream abstraction
- Use full qualifier for the tokenizer mod
- Rename LICENSE_MIT -> LICENSE-MIT
- Rework tests across the binary
- Apply clippy rules
- Flesh out public API


### Build

- *(ci)* Improve ci workflow
- Add basic github workflow


