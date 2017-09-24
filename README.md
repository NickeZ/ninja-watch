# Ninja watch

Ninja watch is a helper script that uses inotify on linux to listen for changed
and created files that would trigger a rebuild by ninja.

It passes through any argument to the real ninja build.

## Example usage

```
ninja-watch -C build
```
