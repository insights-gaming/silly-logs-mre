To see the silly logs behavior do:
1. `npm install`
2. `npm run build:gyp`

`node-gyp` with `@overwolf/ow-electron-builder@25.0.8` uses `--loglevel` as expected.
1. `npm install -D @overwolf/ow-electron-builder@25.0.8`
2. `npm run build:gyp`

If upgrading `@overwolf/ow-electron-builder` from `25.0.8` to `26.0.11`, it appears to work until the next `npm install`.
1. `npm install -D @overwolf/ow-electron-builder@26.0.11`
2. `npm install` (again)
3. `npm run build:gyp`
