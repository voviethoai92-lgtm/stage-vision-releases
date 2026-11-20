# STAGE VISION 3D update channels

- `windows-stable/latest.json` — what installed Windows copies on the Stable channel check. The app accepts it only when
  `channel` is `stable`, the version is a plain `X.Y.Z` newer than the installed one, the installer URL is under
  `https://github.com/voviethoai92-lgtm/stage-vision-releases/releases/download/`, and the signature verifies against the
  updater public key embedded in the installed app.
- `windows-beta/latest.json` — optional beta channel (same rules, pre-releases allowed). Not published yet.

The feed is changed only after the release assets are public and their downloads and signatures were verified.
