# Nyaa Game Template

Forked from [Rust SDL2 Template](https://github.com/sgeos/sdl2_template/).

# Building

The following libraries need to be installed to build this project.

- SDL2
- SDL2 Mixer
- SDL2 Image
- SDL2 TTF
- SDL2 GFX

# Usage Examples

This template accepts command line arguments and environment variables.
Press ESC to exit the program.

```sh
# Basic Usage
cargo run

# Help and Version
cargo run -- --help
cargo run -- --version

# Command Line Arguments
cargo run -- --fullscreen
cargo run -- -t "Window Title" -w 200 -h200
cargo run -- -f21 -i1 -d7

# Environment Variables
FULLSCREEN=true cargo run
WINDOW_TITLE="Window Title" WINDOW_WIDTH=200 WINDOW_HEIGHT=200 cargo run
FLASH_INTERVAL=1 FLASH_DURATION=7 FPS=21 cargo run
```

