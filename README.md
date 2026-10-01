# Glitch Flow releases

Public downloads and update metadata for Glitch Flow. The application source
remains in its private repository; this repository contains release packages
and documentation.

## Downloads

Windows x86_64, macOS Apple silicon, and Linux x86_64/aarch64 packages will appear
on the [Releases page](https://github.com/SchizzY/glitch-flow-releases/releases).
There are no published builds yet. Automatic publication is pending the source
workflow reaching main and its publisher/build settings being configured.

## Updates

The application update feed is:

`https://github.com/SchizzY/glitch-flow-releases/releases/latest/download`

Each complete release includes `manifest.json` with its version and package
SHA-256 checksums, plus `latest.txt`. Packages are built from the source
repository's main branch. New numbered versions publish automatically once the
workflow is enabled; unchanged versions do not replace existing releases.
Metadata follows the latest complete release, while package downloads are pinned
to the version discovered in that metadata.

Existing installations need a build containing the new feed configuration, or
an explicit `GLITCH_FLOW_RELEASES_URL` override, to follow this repository.
