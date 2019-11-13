# Changelog
All notable changes to this project will be documented in this file.

The format is inspired from [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and the versioning aim to respect [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

Here is a template for new release sections

```
## [_._._] - 20XX-MM-DD

### Added
-
### Changed
-
### Removed
-
```
## [Unreleased]

### Added
- factsheet categories (#47)
- storage technologies (#47)
- `ObjectProperty` `has_normal_state_of_matter` (#39)
- add individuals `solid`, `liquid`, `gaseous`, `plasmatic` (#39)
- Add has_normal_state_of_matter value solid/liquid/gaseous/plasmatic to fuels (#39)
- object properties: 'has_disposition', 'has_role', 'has_function',
  'has_quality' (#51)
### Changed
- FluorinatedGreenhouseGas (#88)
- agent and subclasses (#51)
- pollutant and subclasses (#51)
- structure of the ontology (#47)
- change peat to solid and not gas (#39)
- StateOfMatter and subclasses (#45)

### Removed
- `ObjectProperty` `has_stateofmatter` (#39)
- some superclasses of unsatisfiable classes and some that made the
  ontology inconsistent (#51)
