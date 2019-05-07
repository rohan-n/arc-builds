# arc-builds
Similar to `arc list`, but also lists the current build status for each
revision.

## Requirements
- Some python third-party libraries (TODO: remove these dependencies)
- An `.arcrc` config containing a Phabricator hostname with an API token

## Installation
To set up as an `arcanist` alias, run the following commands
```bash
git clone https://github.com/kaybinwang/arc-builds
cd arc-builds
arc alias builds '!'"$(pwd -P)"'/arc-builds'
```

After this, you should be able to list your Phabricator revisions with
```bash
arc builds
```
