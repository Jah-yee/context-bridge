# Changelog

## [0.2.0] - 2026-10-02

### Changed
- **BREAKING (install name only): the distribution is renamed to
  `context-bridge-py`.** The bare `context-bridge` name on PyPI belongs to
  Ganzzi/context_bridge, an unrelated RAG documentation crawler, so this
  project could never be published under its own name and a documented
  `pip install context-bridge` silently installed that other author's
  package. The import package (`context_bridge`) and the console script
  (`context-bridge`) are unchanged.

## [0.1.0] - 2026-09-26

### Added
- Initial release