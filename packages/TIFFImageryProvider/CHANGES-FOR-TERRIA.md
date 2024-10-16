Changes have been made to this fork to facilitate its use in Terria while keeping the merge conflicts minimal.

- Replace `import {x} from "cesium"` with corresponding `terriajs-cesium` imports. To keep merge conflicts minimal this is done using an intermediary import file [terriajs-cesium-imports.ts](./packages/TIFFImageryProvider/src/terriajs-cesium-imports.ts)
- Added [.prettierignore](./packages/TIFFImageryProvider/.prettierignore) to ignore package files.
- Added [.editorconfig](./packages/.editorconfig) to match upstream formatting rules.
- Changed `rollup-web-worker-loader-plugin` target to `browser` ([link](https://github.com/TerriaJS/TIFFImageryProvider/blob/c7815d08b099bd11bf7fd31eae33e9f48297767a/packages/TIFFImageryProvider/rollup.config.js#L32))
