# Snake

`.github/workflows/snake.yml` with [Platane/snk](https://github.com/Platane/snk).

- runs every 12 hours, on push to `main` and by hand
- builds `snake-dark.svg` and `snake-light.svg`, publishes them to the `output` branch
- README picks the right one via `<picture>` + `prefers-color-scheme`
