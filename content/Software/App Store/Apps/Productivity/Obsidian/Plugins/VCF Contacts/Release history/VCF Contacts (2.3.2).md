---
created: 2026-04-13T13:43:33Z
tags:
  - plugins/obsidian/_release
  - missing-wayback
---

| [Github](https://github.com/broekema41/obsidian-vcf-contacts/releases/tag/2.3.2) | Wayback |
| :------------------------------------------------------------------------------: | :-----: |
# Releasing 2.3.2 patch including #68 #73 #78 #79 #83 #84
---
Thanks too [@camadkins](https://github.com/camadkins) [@schutm](https://github.com/schutm) for posting their bugs and on the cardav integrations. this release had a great performance improvement for larger VCF databases
## Changes
- Refs: [#83](https://github.com/broekema41/obsidian-vcf-contacts/issues/83) initial experimentation adding a github workflow for release
- Refs: [#73](https://github.com/broekema41/obsidian-vcf-contacts/pull/73) first test set for the sync loop bug updateFromRemote
- Merge pull request [#73](https://github.com/broekema41/obsidian-vcf-contacts/pull/73) from schutm/patch-1
- Merge pull request [#78](https://github.com/broekema41/obsidian-vcf-contacts/pull/78) from broekema41/feature/68-performance-improvements-import
- Refs: [#68](https://github.com/broekema41/obsidian-vcf-contacts/issues/68) less waiting for files to be rendered during import
- Don't bail update via cardav when encountering UID, PHOTO or an empty value
### Contributors
 [![@schutm](https://avatars.githubusercontent.com/u/1652928?s=64&v=4)](https://github.com/schutm) [![@camadkins](https://avatars.githubusercontent.com/u/48412231?s=64&v=4)](https://github.com/camadkins)
schutm and camadkins