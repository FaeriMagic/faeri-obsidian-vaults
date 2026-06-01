---
title: 2.2. tp.config
---
# Config Module

This module exposes Templater's running configuration.

This is mostly useful when writing scripts requiring some context information.

- [[#Documentation]]
    - [[#tp.config.active_file?]]
    - [[#tp.config.run_mode]]
    - [[#tp.config.target_file]]
    - [[#tp.config.template_file]]

## Documentation
### `tp.config.active_file?`

The active file (if existing) when launching Templater.

### `tp.config.run_mode`

The `RunMode`, representing the way Templater was launched (Create new from template, Append to active file, ...).

### `tp.config.target_file`

The `TFile` object representing the target file where the template will be inserted.

### `tp.config.template_file`

The `TFile` object representing the template file.

← Go to [[Templater - Documentation (2.1. tp.app)|previous page]] | Go to [[Templater - Documentation (2.3. tp.date)|next page]] →