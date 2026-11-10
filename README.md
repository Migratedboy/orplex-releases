# Orplex Code — Release Artifacts

This repository holds compiled release binaries only: the platform installers,
their blockmaps and the updater channel files (`latest.yml`, `latest-mac.yml`,
`latest-linux.yml`). Nothing here is built from this repository — every release
is uploaded by the `Release App` workflow of
[`Migratedboy/orplex-frountend`](https://github.com/Migratedboy/orplex-frountend).

No source code, unpacked build tree, environment file or secret is published
here. The installers ship the app inside an asar archive, with source maps
disabled.
