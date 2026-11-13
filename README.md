# Bardrop upgrade bridge

Bardrop is becoming **Barscene**, a GIF and short-video editor for Windows,
made by Bardevco.

[Barscene product page](https://bardevco.com/apps/barscene) ·
[Canonical Barscene downloads](https://github.com/mistercr0wbar/Barscene-releases/releases)

This repository keeps the original update channel available to existing
Bardrop installations. The transition release uses the old installer and
feed filenames while installing the same Barscene build. Existing settings
and library locations are retained; Barscene uses its new channel for later
updates. All previous Bardrop release assets remain available.

The new canonical channel includes installers, portable and standalone
downloads, release notes, signed update feeds, third-party notices and the
corresponding FFmpeg source and build recipe.

Signed update verification is separate from Authenticode publisher signing.
The application currently has no Windows publisher certificate.

## Publication

Releases are verified and uploaded directly from the locally tested build by
the private source repository's release command. GitHub Actions is disabled;
this repository has no hosted publishing workflow. Published binaries and
previous releases are never replaced.
