# tkci

<p align="center">
  <img src="https://github.com/box1o/tkci/releases/latest/download/tkci-3d.png" alt="tkci IMG" width="720">
</p>

## How to use

Edit the KiCad project files on `dev`, then open a pull request into `release`. GitHub Actions runs KiBot, creates the manufacturing outputs, and publishes a release with the schematic PDF, manufacturing package, changelog, and latest isometric 3D render when `release` is updated.

Project metadata lives in `settings.env`:

- `PROJECT_NAME`: KiCad project basename.
- `BOARD_NAME`: output file basename.
- `PACKAGE_NAME`: release zip basename.
- `RELEASE_TITLE`: GitHub release title.

The image above is loaded from the latest GitHub release.
