# Photo Avelton

Photo Avelton is part of the Avelton creative suite, based on the open-source [PhotoCraft](https://github.com/storytold/photocraft) project.

- Browser: https://photo.avelton.online
- Windows, macOS and Linux alpha downloads: https://github.com/avelton-ai/photo-avelton/releases
- Support and bugs: https://github.com/avelton-ai/photo-avelton/issues

The first Avelton releases are unsigned alpha builds. macOS packages use ad-hoc signatures and are not notarized. Projects stay on your device; the hosted browser app has no Avelton account or cloud project storage. Browser capabilities and file support depend on the upstream implementation.

## Build and verify

Install Rust (see `rust-version` in Cargo.toml), the wasm32-unknown-unknown target and the native platform dependencies described in the upstream development documentation. Run `cargo xtask ci` for the repository's checks. Desktop: `cargo run --release -p photocraft`. CLI: `cargo run --release -p photocraft-cli -- --help`. Release scripts are under `packaging/`; the Avelton release workflow builds browser and native packages together.

Rust crate names, command APIs and project file formats retain upstream identifiers for compatibility. Installed binary names are `photo-avelton` and `photo-avelton-cli`. Avelton uses a separate application identifier (`online.avelton.photo`), installer identities and settings directory.

## Attribution and updates

Source: https://github.com/storytold/photocraft, initial commit `7b3ded0f8bec6c801c9cd95311602e077ca891af`. Original copyright notices, contributors, third-party credits and MIT/Apache licences are preserved. Avelton branding is independent original artwork; bundled Inter lettering remains OFL-1.1. See NOTICE and the asset attribution files. The original ArtCraft brand artwork is excluded from this fork's distributions.

Upstream updates are reviewed and tested manually before an Avelton release. This fork is independently maintained and is not an official ArtCraft distribution.

## Tools

<h4>🧰 52 tools</h4>
Move · Rectangular and Elliptical Marquee · Lasso · Polygonal Lasso · Magnetic Lasso · Object Selection · Quick Selection · Magic Wand · Crop · Slice · Slice Select · Eyedropper · Ruler · Note · Count · Spot Healing Brush · Healing Brush · Patch · Content-Aware Move · Red Eye · Brush · Pencil · Mixer Brush · Clone Stamp · Pattern Stamp · History Brush · Eraser · Background Eraser · Magic Eraser · Gradient · Paint Bucket · Blur · Sharpen · Smudge · Dodge · Burn · Sponge · Pen · Horizontal and Vertical Type · Path Selection · Direct Selection · Rectangle · Ellipse · Triangle · Polygon · Line · Custom Shape · Hand · Rotate View · Zoom
