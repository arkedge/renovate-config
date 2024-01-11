# renovate-config

[Shareable Renovate config presets](https://docs.renovatebot.com/config-presets/) used in [ArkEdge Space](https://arkedgespace.com)

## Available presets

### `cargo-chef-docker.json5`

A package rule to constrain Rust and [cargo-chef-docker](https://github.com/sksat/cargo-chef-docker) to be same version.

### `earthfile.json5`

A custom manager to maintain dependencies in [`Earthfile`](https://earthly.dev) the same way as `Dockerfile`.

### `rust-toolchain.json`

A custom manager to maintain Rust version that described in `rust-toolchain`.
