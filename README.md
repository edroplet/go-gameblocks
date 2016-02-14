# go-gameblocks

Game engine toolkit for Go.

**Status**: Alpha. (No stability guarantee)

Some good stuff in here, but fairly specific to my own projects at the moment.
It may generalize more over time. Largely factored out of 
[shazow/linerage3d](https://github.com/shazow/linerage3d).

Some things that already work well:

- Cameras (Quat and Euler based, with lerping)
- Shader managing (with reloading support)
- Scene managing (basic for now, need to flesh it out into a tree-based thing)
- Control key binding


## Goals

- Multiple rendering backends
  - [x] Support golang.com/x/mobile backend
  - [ ] Support additional backends (glfw)

- More non-rendering things.


## License

MIT
