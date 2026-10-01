# Glitch Flow releases

Public application downloads and update metadata for Glitch Flow.
Source code and build/deployment instructions remain in the private source repo.

## Downloads

Stable packages will appear on the
[Releases page](https://github.com/SchizzY/glitch-flow-releases/releases).
No stable release has been published yet.

Supported release packages cover Windows x86_64, macOS Apple silicon, and Linux
x86_64/aarch64. Release notes identify any platform or configuration limitations.

## Automatic updates

The application checks this public feed:

`https://github.com/SchizzY/glitch-flow-releases/releases/latest/download`

Complete releases include `manifest.json` with the version and package SHA-256
checksums, plus `latest.txt`. Package downloads are pinned to the discovered
version. Existing installations need a build containing this feed configuration
or an explicit update URL override to follow it.
