Changes have been made to this fork to facilitate its use in Terria while keeping the merge conflicts minimal.

- Replace `import {x} from "cesium"` with corresponding `terriajs-cesium` imports. To keep merge conflicts minimal this is done using an intermediary import file [terriajs-cesium-imports.ts](https://github.com/TerriaJS/TIFFImageryProvider/blob/main/packages/TIFFImageryProvider/src/terriajs-cesium-imports.ts).
- Added [.prettierignore](https://github.com/TerriaJS/TIFFImageryProvider/blob/main/packages/TIFFImageryProvider/.prettierignore) to ignore package files.
- Added [.editorconfig](https://github.com/TerriaJS/TIFFImageryProvider/blob/main/.editorconfig) to match upstream formatting rules.
- Changed `rollup-web-worker-loader-plugin` target to `browser` ([link](https://github.com/TerriaJS/TIFFImageryProvider/blob/c7815d08b099bd11bf7fd31eae33e9f48297767a/packages/TIFFImageryProvider/rollup.config.js#L32))
