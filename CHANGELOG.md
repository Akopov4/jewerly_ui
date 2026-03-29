# Changelog

## [1.3.7] — 2026-03-22

### Removed
- Debug console, debug toolbar, debug icons colors
- Test results, testing icons, coverage colors
- Output panel colors

## [1.3.6] — 2026-03-22

### Added
- INI file (*.ini) syntax highlighting for both Jewelry and Ocean Jewelry
- Highlighted tokens: section headers, keys, values, numbers, booleans, comments (# and ;)

## [1.3.5] — 2026-03-22

### Changed
- Aligned full ANSI 16-color palette with theme colors for Test Results panel text
- Jewelry: passed=green, failed=red, skipped=yellow, info=blue, types=teal
- Ocean Jewelry: passed=green, failed=coral, skipped=amber, info=ice blue, types=teal
- Updated output panel background and foreground for both themes

## [1.3.4] — 2026-03-22

### Added
- Full testing color support with all available VS Code testing keys:
  - All icon states: passed, failed, errored, skipped, queued, unset
  - Retired (dimmed) variants for all icon states
  - Peek view border and header colors
  - Inline error and info message badges, borders, backgrounds
  - Code coverage: covered/uncovered background, border and gutter colors
  - Uncovered branch background
  - Coverage count badge background and foreground

## [1.3.3] — 2026-03-22

### Added
- Test Results panel background, foreground and selection colors
- Output panel colors (background, foreground, selection, important items)
- Code coverage highlight colors (covered/uncovered background, border, gutter)
- ANSI terminal colors aligned with test runner output (passed=green, failed=red, skipped=yellow, info=blue)

## [1.3.2] — 2026-03-22

### Changed
- Test result skipped icon color changed to yellow (`#f9e2af` in Jewelry, `#ffa657` in Ocean Jewelry)

## [1.3.1] — 2026-03-22

### Added
- Debug Console colors (info, warning, error, source, input)
- Debug toolbar and stack frame highlight colors
- Breakpoint icons (active, disabled, unverified, current frame)
- Debug action icons (start, stop, pause, continue, step over/into/out, restart, disconnect)
- Test result icons (passed, failed, errored, skipped, queued)
- Test message inline decorations (error and info)

## [1.3.0] — 2026-03-22

### Added
- Integrated terminal colors for both Jewelry and Ocean Jewelry themes
- Works on Windows, Linux and macOS
- Full ANSI 16-color palette (normal + bright variants)
- Terminal background, foreground, cursor and selection colors

## [1.2.9] — 2026-03-22

### Changed
- Ocean Jewelry: XML tag punctuation (`<`, `>`, `</`, `/>`) changed to teal `#39d4c5`
- Ocean Jewelry: CDATA blocks changed to teal `#39d4c5`

## [1.2.7] — 2026-03-22

### Added
- Gherkin (.feature) support for both Jewelry and Ocean Jewelry themes
- Highlighted tokens: keywords (Feature, Scenario, Given, When, Then, And, But),
  scenario titles, step text, parameters, tags (@tag), data table pipes and cells,
  docstrings, comments, and Examples keyword

## [1.2.5] — 2026-03-16

### Changed
- Ocean Jewelry: XML tag punctuation (`<`, `>`, `</`, `/>`) changed to amber `#ffa657`
- Ocean Jewelry: CDATA blocks (`<![CDATA[ ... ]]>`) changed to amber `#ffa657`

## [1.2.2] — 2026-03-12

### Added
- Initial release of JewelryUI
- Syntax highlighting for Python, Java, JavaScript, TypeScript, C, C++, Rust
- Syntax highlighting for HTML, CSS, YAML, TOML, Bash, Dockerfile, Docker Compose
- Semantic token support for all languages
- Bundled editor defaults (tree indent, compact tabs, auto save, bracket colorization)
- Diamond gem icon
