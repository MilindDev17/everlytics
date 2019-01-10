# everlytics
#NPm

E:\bootstrap\everlytics>npm install html-webpack-plugin --save-dev
npm WARN babel-loader@8.0.5 requires a peer of @babel/core@^7.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN everlytics@1.0.0 No description
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.4 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.4: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

+ html-webpack-plugin@3.2.0
added 38 packages from 60 contributors in 80.327s

E:\bootstrap\everlytics>
E:\bootstrap\everlytics>
E:\bootstrap\everlytics>npm run start

> everlytics@1.0.0 start E:\bootstrap\everlytics
> webpack-dev-server --mode development --open

× ｢wds｣: Invalid configuration object. Webpack has been initialised using a configuration object that does not match the API schema.
 - configuration has an unknown property 'plugin'. These properties are valid:
   object { amd?, bail?, cache?, context?, dependencies?, devServer?, devtool?, entry?, externals?, loader?, mode?, module?, name?, node?, optimization?, output?, parallelism?, performance?, plugins?, profile?, recordsInputPath?, recordsOutputPath?, recordsPath?, resolve?, resolveLoader?, serve?, stats?, target?, watch?, watchOptions? }
   For typos: please correct them.
   For loader options: webpack >= v2.0.0 no longer allows custom properties in configuration.
     Loaders should be updated to allow passing options via loader options in module.rules.
     Until loaders are updated one can use the LoaderOptionsPlugin to pass these options to the loader:
     plugins: [
       new webpack.LoaderOptionsPlugin({
         // test: /\.xxx$/, // may apply this only for some modules
         options: {
           plugin: …
         }
       })
     ]
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! everlytics@1.0.0 start: `webpack-dev-server --mode development --open`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the everlytics@1.0.0 start script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\MILIND_Dev.MILIND\AppData\Roaming\npm-cache\_logs\2019-01-10T09_08_39_338Z-debug.log

E:\bootstrap\everlytics>
E:\bootstrap\everlytics>
E:\bootstrap\everlytics>npm run build

> everlytics@1.0.0 build E:\bootstrap\everlytics
> webpack --mode production

Invalid configuration object. Webpack has been initialised using a configuration object that does not match the API schema.
 - configuration has an unknown property 'plugin'. These properties are valid:
   object { amd?, bail?, cache?, context?, dependencies?, devServer?, devtool?, entry?, externals?, loader?, mode?, module?, name?, node?, optimization?, output?, parallelism?, performance?, plugins?, profile?, recordsInputPath?, recordsOutputPath?, recordsPath?, resolve?, resolveLoader?, serve?, stats?, target?, watch?, watchOptions? }
   For typos: please correct them.
   For loader options: webpack >= v2.0.0 no longer allows custom properties in configuration.
     Loaders should be updated to allow passing options via loader options in module.rules.
     Until loaders are updated one can use the LoaderOptionsPlugin to pass these options to the loader:
     plugins: [
       new webpack.LoaderOptionsPlugin({
         // test: /\.xxx$/, // may apply this only for some modules
         options: {
           plugin: …
         }
       })
     ]
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! everlytics@1.0.0 build: `webpack --mode production`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the everlytics@1.0.0 build script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\MILIND_Dev.MILIND\AppData\Roaming\npm-cache\_logs\2019-01-10T09_09_03_653Z-debug.log

E:\bootstrap\everlytics>npm run start

> everlytics@1.0.0 start E:\bootstrap\everlytics
> webpack-dev-server --mode development --open

× ｢wds｣: Invalid configuration object. Webpack has been initialised using a configuration object that does not match the API schema.
 - configuration has an unknown property 'plugin'. These properties are valid:
   object { amd?, bail?, cache?, context?, dependencies?, devServer?, devtool?, entry?, externals?, loader?, mode?, module?, name?, node?, optimization?, output?, parallelism?, performance?, plugins?, profile?, recordsInputPath?, recordsOutputPath?, recordsPath?, resolve?, resolveLoader?, serve?, stats?, target?, watch?, watchOptions? }
   For typos: please correct them.
   For loader options: webpack >= v2.0.0 no longer allows custom properties in configuration.
     Loaders should be updated to allow passing options via loader options in module.rules.
     Until loaders are updated one can use the LoaderOptionsPlugin to pass these options to the loader:
     plugins: [
       new webpack.LoaderOptionsPlugin({
         // test: /\.xxx$/, // may apply this only for some modules
         options: {
           plugin: …
         }
       })
     ]
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! everlytics@1.0.0 start: `webpack-dev-server --mode development --open`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the everlytics@1.0.0 start script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\MILIND_Dev.MILIND\AppData\Roaming\npm-cache\_logs\2019-01-10T09_09_56_319Z-debug.log

E:\bootstrap\everlytics>
E:\bootstrap\everlytics>npm run start

> everlytics@1.0.0 start E:\bootstrap\everlytics
> webpack-dev-server --mode development --open

i ｢wds｣: Project is running at http://localhost:8080/
i ｢wds｣: webpack output is served from /
i ｢wds｣: Content not from webpack is served from ./dist
i ｢wdm｣: Hash: 5f5f6dfb68a1c78b8011
Version: webpack 4.28.1
Time: 3280ms
Built at: 2019-01-10 14:41:15
    Asset     Size  Chunks             Chunk Names
bundle.js  344 KiB    main  [emitted]  main
Entrypoint main = bundle.js
[0] multi (webpack)-dev-server/client?http://localhost:8080 ./src/js/index.js 40 bytes {main} [built]
[./node_modules/ansi-html/index.js] 4.16 KiB {main} [built]
[./node_modules/events/events.js] 8.13 KiB {main} [built]
[./node_modules/html-entities/index.js] 231 bytes {main} [built]
[./node_modules/loglevel/lib/loglevel.js] 7.68 KiB {main} [built]
[./node_modules/node-libs-browser/node_modules/punycode/punycode.js] 14.3 KiB {main} [built]
[./node_modules/url/url.js] 22.8 KiB {main} [built]
[./node_modules/webpack-dev-server/client/index.js?http://localhost:8080] (webpack)-dev-server/client?http://localhost:8080 7.78 KiB {main} [built]
[./node_modules/webpack-dev-server/client/overlay.js] (webpack)-dev-server/client/overlay.js 3.58 KiB {main} [built]
[./node_modules/webpack-dev-server/client/socket.js] (webpack)-dev-server/client/socket.js 1.05 KiB {main} [built]
[./node_modules/webpack-dev-server/node_modules/strip-ansi/index.js] (webpack)-dev-server/node_modules/strip-ansi/index.js 161 bytes {main} [built]
[./node_modules/webpack/hot sync ^\.\/log$] (webpack)/hot sync nonrecursive ^\.\/log$ 170 bytes {main} [built]
[./node_modules/webpack/hot/emitter.js] (webpack)/hot/emitter.js 75 bytes {main} [built]
[./src/js/index.js] 1.37 KiB {main} [built]
[./src/js/test.js] 56 bytes {main} [built]
    + 12 hidden modules
i ｢wdm｣: Compiled successfully.
i ｢wdm｣: Compiling...
i ｢wdm｣: Hash: 5f5f6dfb68a1c78b8011
Version: webpack 4.28.1
Time: 119ms
Built at: 2019-01-10 14:42:01
 1 asset
Entrypoint main = bundle.js
[./src/js/index.js] 1.37 KiB {main} [built]
    + 26 hidden modules
i ｢wdm｣: Compiled successfully.
i ｢wdm｣: Compiling...
i ｢wdm｣: Hash: f70a8dfc7ead6d7bce15
Version: webpack 4.28.1
Time: 110ms
Built at: 2019-01-10 14:42:10
    Asset     Size  Chunks             Chunk Names
bundle.js  344 KiB    main  [emitted]  main
Entrypoint main = bundle.js
[./src/js/test.js] 56 bytes {main} [built]
    + 26 hidden modules
i ｢wdm｣: Compiled successfully.
Terminate batch job (Y/N)? y

E:\bootstrap\everlytics>npm run start

> everlytics@1.0.0 start E:\bootstrap\everlytics
> webpack-dev-server --mode development --open

× ｢wds｣: Invalid configuration object. Webpack has been initialised using a configuration object that does not match the API schema.
 - configuration has an unknown property 'plugin'. These properties are valid:
   object { amd?, bail?, cache?, context?, dependencies?, devServer?, devtool?, entry?, externals?, loader?, mode?, module?, name?, node?, optimization?, output?, parallelism?, performance?, plugins?, profile?, recordsInputPath?, recordsOutputPath?, recordsPath?, resolve?, resolveLoader?, serve?, stats?, target?, watch?, watchOptions? }
   For typos: please correct them.
   For loader options: webpack >= v2.0.0 no longer allows custom properties in configuration.
     Loaders should be updated to allow passing options via loader options in module.rules.
     Until loaders are updated one can use the LoaderOptionsPlugin to pass these options to the loader:
     plugins: [
       new webpack.LoaderOptionsPlugin({
         // test: /\.xxx$/, // may apply this only for some modules
         options: {
           plugin: …
         }
       })
     ]
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! everlytics@1.0.0 start: `webpack-dev-server --mode development --open`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the everlytics@1.0.0 start script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\MILIND_Dev.MILIND\AppData\Roaming\npm-cache\_logs\2019-01-10T09_15_01_575Z-debug.log

E:\bootstrap\everlytics>npm run start

> everlytics@1.0.0 start E:\bootstrap\everlytics
> webpack-dev-server --mode development --open

× ｢wds｣: Invalid configuration object. Webpack has been initialised using a configuration object that does not match the API schema.
 - configuration has an unknown property 'plugin'. These properties are valid:
   object { amd?, bail?, cache?, context?, dependencies?, devServer?, devtool?, entry?, externals?, loader?, mode?, module?, name?, node?, optimization?, output?, parallelism?, performance?, plugins?, profile?, recordsInputPath?, recordsOutputPath?, recordsPath?, resolve?, resolveLoader?, serve?, stats?, target?, watch?, watchOptions? }
   For typos: please correct them.
   For loader options: webpack >= v2.0.0 no longer allows custom properties in configuration.
     Loaders should be updated to allow passing options via loader options in module.rules.
     Until loaders are updated one can use the LoaderOptionsPlugin to pass these options to the loader:
     plugins: [
       new webpack.LoaderOptionsPlugin({
         // test: /\.xxx$/, // may apply this only for some modules
         options: {
           plugin: …
         }
       })
     ]
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! everlytics@1.0.0 start: `webpack-dev-server --mode development --open`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the everlytics@1.0.0 start script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\MILIND_Dev.MILIND\AppData\Roaming\npm-cache\_logs\2019-01-10T09_15_37_603Z-debug.log

E:\bootstrap\everlytics>npm install html-webpack-plugin --save-dev
npm WARN babel-loader@8.0.5 requires a peer of @babel/core@^7.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN everlytics@1.0.0 No description
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.4 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.4: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

+ html-webpack-plugin@3.2.0
updated 1 package in 26.71s

E:\bootstrap\everlytics>npm run start

> everlytics@1.0.0 start E:\bootstrap\everlytics
> webpack-dev-server --mode development --open

× ｢wds｣: Invalid configuration object. Webpack has been initialised using a configuration object that does not match the API schema.
 - configuration has an unknown property 'plugin'. These properties are valid:
   object { amd?, bail?, cache?, context?, dependencies?, devServer?, devtool?, entry?, externals?, loader?, mode?, module?, name?, node?, optimization?, output?, parallelism?, performance?, plugins?, profile?, recordsInputPath?, recordsOutputPath?, recordsPath?, resolve?, resolveLoader?, serve?, stats?, target?, watch?, watchOptions? }
   For typos: please correct them.
   For loader options: webpack >= v2.0.0 no longer allows custom properties in configuration.
     Loaders should be updated to allow passing options via loader options in module.rules.
     Until loaders are updated one can use the LoaderOptionsPlugin to pass these options to the loader:
     plugins: [
       new webpack.LoaderOptionsPlugin({
         // test: /\.xxx$/, // may apply this only for some modules
         options: {
           plugin: …
         }
       })
     ]
npm ERR! code ELIFECYCLE
npm ERR! errno 1
npm ERR! everlytics@1.0.0 start: `webpack-dev-server --mode development --open`
npm ERR! Exit status 1
npm ERR!
npm ERR! Failed at the everlytics@1.0.0 start script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\MILIND_Dev.MILIND\AppData\Roaming\npm-cache\_logs\2019-01-10T09_16_54_331Z-debug.log

E:\bootstrap\everlytics>npm run start

> everlytics@1.0.0 start E:\bootstrap\everlytics
> webpack-dev-server --mode development --open

i ｢wds｣: Project is running at http://localhost:8080/
i ｢wds｣: webpack output is served from /
i ｢wds｣: Content not from webpack is served from ./dist
× ｢wdm｣: Hash: c41856b06ce4122c35c1
Version: webpack 4.28.1
Time: 3120ms
Built at: 2019-01-10 14:47:55
       Asset      Size  Chunks             Chunk Names
  index.html  1.02 KiB          [emitted]
js/bundle.js   344 KiB    main  [emitted]  main
Entrypoint main = js/bundle.js
[0] multi (webpack)-dev-server/client?http://localhost:8080 ./src/js/index.js 40 bytes {main} [built]
[./node_modules/ansi-html/index.js] 4.16 KiB {main} [built]
[./node_modules/events/events.js] 8.13 KiB {main} [built]
[./node_modules/html-entities/index.js] 231 bytes {main} [built]
[./node_modules/loglevel/lib/loglevel.js] 7.68 KiB {main} [built]
[./node_modules/node-libs-browser/node_modules/punycode/punycode.js] 14.3 KiB {main} [built]
[./node_modules/url/url.js] 22.8 KiB {main} [built]
[./node_modules/webpack-dev-server/client/index.js?http://localhost:8080] (webpack)-dev-server/client?http://localhost:8080 7.78 KiB {main} [built]
[./node_modules/webpack-dev-server/client/overlay.js] (webpack)-dev-server/client/overlay.js 3.58 KiB {main} [built]
[./node_modules/webpack-dev-server/client/socket.js] (webpack)-dev-server/client/socket.js 1.05 KiB {main} [built]
[./node_modules/webpack-dev-server/node_modules/strip-ansi/index.js] (webpack)-dev-server/node_modules/strip-ansi/index.js 161 bytes {main} [built]
[./node_modules/webpack/hot sync ^\.\/log$] (webpack)/hot sync nonrecursive ^\.\/log$ 170 bytes {main} [built]
[./node_modules/webpack/hot/emitter.js] (webpack)/hot/emitter.js 75 bytes {main} [built]
[./src/js/index.js] 1.37 KiB {main} [built]
[./src/js/test.js] 56 bytes {main} [built]
    + 12 hidden modules

ERROR in   Error: Child compilation failed:
  Entry module not found: Error: Can't resolve 'E:\bootstrap\everlytics\src\index.html' in 'E:\bootstrap\everlytics':
  Error: Can't resolve 'E:\bootstrap\everlytics\src\index.html' in 'E:\bootstrap\everlytics'

  - compiler.js:79 childCompiler.runAsChild
    [everlytics]/[html-webpack-plugin]/lib/compiler.js:79:16

  - Compiler.js:296 compile
    [everlytics]/[webpack]/lib/Compiler.js:296:11

  - Compiler.js:552 hooks.afterCompile.callAsync.err
    [everlytics]/[webpack]/lib/Compiler.js:552:14


  - Hook.js:154 AsyncSeriesHook.lazyCompileHook
    [everlytics]/[tapable]/lib/Hook.js:154:20

  - Compiler.js:549 compilation.seal.err
    [everlytics]/[webpack]/lib/Compiler.js:549:30


  - Hook.js:154 AsyncSeriesHook.lazyCompileHook
    [everlytics]/[tapable]/lib/Hook.js:154:20

  - Compilation.js:1323 hooks.optimizeAssets.callAsync.err
    [everlytics]/[webpack]/lib/Compilation.js:1323:35



Child html-webpack-plugin for "index.html":

    ERROR in Entry module not found: Error: Can't resolve 'E:\bootstrap\everlytics\src\index.html' in 'E:\bootstrap\everlytics'
i ｢wdm｣: Failed to compile.
Terminate batch job (Y/N)?
Terminate batch job (Y/N)? y

E:\bootstrap\everlytics>npm run start

> everlytics@1.0.0 start E:\bootstrap\everlytics
> webpack-dev-server --mode development --open

i ｢wds｣: Project is running at http://localhost:8080/
i ｢wds｣: webpack output is served from /
i ｢wds｣: Content not from webpack is served from ./dist
i ｢wdm｣: wait until bundle finished: /
× ｢wdm｣: Hash: c41856b06ce4122c35c1
Version: webpack 4.28.1
Time: 3487ms
Built at: 2019-01-10 14:51:32
       Asset      Size  Chunks             Chunk Names
  index.html  1.02 KiB          [emitted]
js/bundle.js   344 KiB    main  [emitted]  main
Entrypoint main = js/bundle.js
[0] multi (webpack)-dev-server/client?http://localhost:8080 ./src/js/index.js 40 bytes {main} [built]
[./node_modules/ansi-html/index.js] 4.16 KiB {main} [built]
[./node_modules/events/events.js] 8.13 KiB {main} [built]
[./node_modules/html-entities/index.js] 231 bytes {main} [built]
[./node_modules/loglevel/lib/loglevel.js] 7.68 KiB {main} [built]
[./node_modules/node-libs-browser/node_modules/punycode/punycode.js] 14.3 KiB {main} [built]
[./node_modules/url/url.js] 22.8 KiB {main} [built]
[./node_modules/webpack-dev-server/client/index.js?http://localhost:8080] (webpack)-dev-server/client?http://localhost:8080 7.78 KiB {main} [built]
[./node_modules/webpack-dev-server/client/overlay.js] (webpack)-dev-server/client/overlay.js 3.58 KiB {main} [built]
[./node_modules/webpack-dev-server/client/socket.js] (webpack)-dev-server/client/socket.js 1.05 KiB {main} [built]
[./node_modules/webpack-dev-server/node_modules/strip-ansi/index.js] (webpack)-dev-server/node_modules/strip-ansi/index.js 161 bytes {main} [built]
[./node_modules/webpack/hot sync ^\.\/log$] (webpack)/hot sync nonrecursive ^\.\/log$ 170 bytes {main} [built]
[./node_modules/webpack/hot/emitter.js] (webpack)/hot/emitter.js 75 bytes {main} [built]
[./src/js/index.js] 1.37 KiB {main} [built]
[./src/js/test.js] 56 bytes {main} [built]
    + 12 hidden modules

ERROR in   Error: Child compilation failed:
  Entry module not found: Error: Can't resolve 'E:\bootstrap\everlytics\src\index.html' in 'E:\bootstrap\everlytics':
  Error: Can't resolve 'E:\bootstrap\everlytics\src\index.html' in 'E:\bootstrap\everlytics'

  - compiler.js:79 childCompiler.runAsChild
    [everlytics]/[html-webpack-plugin]/lib/compiler.js:79:16

  - Compiler.js:296 compile
    [everlytics]/[webpack]/lib/Compiler.js:296:11

  - Compiler.js:552 hooks.afterCompile.callAsync.err
    [everlytics]/[webpack]/lib/Compiler.js:552:14


  - Hook.js:154 AsyncSeriesHook.lazyCompileHook
    [everlytics]/[tapable]/lib/Hook.js:154:20

  - Compiler.js:549 compilation.seal.err
    [everlytics]/[webpack]/lib/Compiler.js:549:30


  - Hook.js:154 AsyncSeriesHook.lazyCompileHook
    [everlytics]/[tapable]/lib/Hook.js:154:20

  - Compilation.js:1323 hooks.optimizeAssets.callAsync.err
    [everlytics]/[webpack]/lib/Compilation.js:1323:35



Child html-webpack-plugin for "index.html":

    ERROR in Entry module not found: Error: Can't resolve 'E:\bootstrap\everlytics\src\index.html' in 'E:\bootstrap\everlytics'
i ｢wdm｣: Failed to compile.
Terminate batch job (Y/N)? y

E:\bootstrap\everlytics>npm run start

> everlytics@1.0.0 start E:\bootstrap\everlytics
> webpack-dev-server --mode development --open

i ｢wds｣: Project is running at http://localhost:8080/
i ｢wds｣: webpack output is served from /
i ｢wds｣: Content not from webpack is served from ./dist
i ｢wdm｣: wait until bundle finished: /
i ｢wdm｣: Hash: 8c60c9122abd0afaa985
Version: webpack 4.28.1
Time: 2462ms
Built at: 2019-01-10 14:53:29
       Asset       Size  Chunks             Chunk Names
  index.html  185 bytes          [emitted]
js/bundle.js    344 KiB    main  [emitted]  main
Entrypoint main = js/bundle.js
[0] multi (webpack)-dev-server/client?http://localhost:8080 ./src/js/index.js 40 bytes {main} [built]
[./node_modules/ansi-html/index.js] 4.16 KiB {main} [built]
[./node_modules/events/events.js] 8.13 KiB {main} [built]
[./node_modules/html-entities/index.js] 231 bytes {main} [built]
[./node_modules/loglevel/lib/loglevel.js] 7.68 KiB {main} [built]
[./node_modules/node-libs-browser/node_modules/punycode/punycode.js] 14.3 KiB {main} [built]
[./node_modules/url/url.js] 22.8 KiB {main} [built]
[./node_modules/webpack-dev-server/client/index.js?http://localhost:8080] (webpack)-dev-server/client?http://localhost:8080 7.78 KiB {main} [built]
[./node_modules/webpack-dev-server/client/overlay.js] (webpack)-dev-server/client/overlay.js 3.58 KiB {main} [built]
[./node_modules/webpack-dev-server/client/socket.js] (webpack)-dev-server/client/socket.js 1.05 KiB {main} [built]
[./node_modules/webpack-dev-server/node_modules/strip-ansi/index.js] (webpack)-dev-server/node_modules/strip-ansi/index.js 161 bytes {main} [built]
[./node_modules/webpack/hot sync ^\.\/log$] (webpack)/hot sync nonrecursive ^\.\/log$ 170 bytes {main} [built]
[./node_modules/webpack/hot/emitter.js] (webpack)/hot/emitter.js 75 bytes {main} [built]
[./src/js/index.js] 1.37 KiB {main} [built]
[./src/js/test.js] 56 bytes {main} [built]
    + 12 hidden modules
Child html-webpack-plugin for "index.html":
     1 asset
    Entrypoint undefined = index.html
    [./node_modules/html-webpack-plugin/lib/loader.js!./node_modules/html-webpack-plugin/default_index.ejs] 376 bytes {0} [built]
    [./node_modules/lodash/lodash.js] 527 KiB {0} [built]
    [./node_modules/webpack/buildin/global.js] (webpack)/buildin/global.js 472 bytes {0} [built]
    [./node_modules/webpack/buildin/module.js] (webpack)/buildin/module.js 497 bytes {0} [built]
i ｢wdm｣: Compiled successfully.
Terminate batch job (Y/N)? y

E:\bootstrap\everlytics>npm run start

> everlytics@1.0.0 start E:\bootstrap\everlytics
> webpack-dev-server --mode development --open

i ｢wds｣: Project is running at http://localhost:8080/
i ｢wds｣: webpack output is served from /
i ｢wds｣: Content not from webpack is served from ./dist
i ｢wdm｣: wait until bundle finished: /
i ｢wdm｣: Hash: 0fd45eff85587db07414
Version: webpack 4.28.1
Time: 2229ms
Built at: 2019-01-10 14:55:10
       Asset      Size  Chunks             Chunk Names
  index.html  10.7 KiB          [emitted]
js/bundle.js   344 KiB    main  [emitted]  main
Entrypoint main = js/bundle.js
[0] multi (webpack)-dev-server/client?http://localhost:8080 ./src/js/index.js 40 bytes {main} [built]
[./node_modules/ansi-html/index.js] 4.16 KiB {main} [built]
[./node_modules/events/events.js] 8.13 KiB {main} [built]
[./node_modules/html-entities/index.js] 231 bytes {main} [built]
[./node_modules/loglevel/lib/loglevel.js] 7.68 KiB {main} [built]
[./node_modules/node-libs-browser/node_modules/punycode/punycode.js] 14.3 KiB {main} [built]
[./node_modules/url/url.js] 22.8 KiB {main} [built]
[./node_modules/webpack-dev-server/client/index.js?http://localhost:8080] (webpack)-dev-server/client?http://localhost:8080 7.78 KiB {main} [built]
[./node_modules/webpack-dev-server/client/overlay.js] (webpack)-dev-server/client/overlay.js 3.58 KiB {main} [built]
[./node_modules/webpack-dev-server/client/socket.js] (webpack)-dev-server/client/socket.js 1.05 KiB {main} [built]
[./node_modules/webpack-dev-server/node_modules/strip-ansi/index.js] (webpack)-dev-server/node_modules/strip-ansi/index.js 161 bytes {main} [built]
[./node_modules/webpack/hot sync ^\.\/log$] (webpack)/hot sync nonrecursive ^\.\/log$ 170 bytes {main} [built]
[./node_modules/webpack/hot/emitter.js] (webpack)/hot/emitter.js 75 bytes {main} [built]
[./src/js/index.js] 1.37 KiB {main} [built]
[./src/js/test.js] 56 bytes {main} [built]
    + 12 hidden modules
Child html-webpack-plugin for "index.html":
     1 asset
    Entrypoint undefined = index.html
    [./node_modules/html-webpack-plugin/lib/loader.js!./index.html] 11.3 KiB {0} [built]
    [./node_modules/lodash/lodash.js] 527 KiB {0} [built]
    [./node_modules/webpack/buildin/global.js] (webpack)/buildin/global.js 472 bytes {0} [built]
    [./node_modules/webpack/buildin/module.js] (webpack)/buildin/module.js 497 bytes {0} [built]
i ｢wdm｣: Compiled successfully.
Terminate batch job (Y/N)? y

E:\bootstrap\everlytics>npm install babel-core babel-preset-env babel-loader --save-dev
npm WARN babel-loader@8.0.5 requires a peer of @babel/core@^7.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN everlytics@1.0.0 No description
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.4 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.4: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

+ babel-core@6.26.3
+ babel-loader@8.0.5
+ babel-preset-env@1.7.0
updated 3 packages in 64.145s

E:\bootstrap\everlytics>
E:\bootstrap\everlytics>npm install babel-polyfill --save
npm WARN babel-loader@8.0.5 requires a peer of @babel/core@^7.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN everlytics@1.0.0 No description
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.4 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.4: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

+ babel-polyfill@6.26.0
added 2 packages from 2 contributors in 22.417s

E:\bootstrap\everlytics>npm run start

> everlytics@1.0.0 start E:\bootstrap\everlytics
> webpack-dev-server --mode development --open

i ｢wds｣: Project is running at http://localhost:8080/
i ｢wds｣: webpack output is served from /
i ｢wds｣: Content not from webpack is served from ./dist
i ｢wdm｣: wait until bundle finished: /
i ｢wdm｣: wait until bundle finished: /
i ｢wdm｣: Hash: 6464ebe6d0e845554206
Version: webpack 4.28.1
Time: 12153ms
Built at: 2019-01-10 15:27:31
       Asset      Size  Chunks             Chunk Names
  index.html  10.7 KiB          [emitted]
js/bundle.js   817 KiB    main  [emitted]  main
Entrypoint main = js/bundle.js
[0] multi (webpack)-dev-server/client?http://localhost:8080 babel-polyfill ./src/js/index.js 52 bytes {main} [built]
[./node_modules/babel-polyfill/lib/index.js] 833 bytes {main} [built]
[./node_modules/babel-polyfill/node_modules/regenerator-runtime/runtime.js] 23.9 KiB {main} [built]
[./node_modules/core-js/fn/regexp/escape.js] 108 bytes {main} [built]
[./node_modules/core-js/shim.js] 8.03 KiB {main} [built]
[./node_modules/loglevel/lib/loglevel.js] 7.68 KiB {main} [built]
[./node_modules/url/url.js] 22.8 KiB {main} [built]
[./node_modules/webpack-dev-server/client/index.js?http://localhost:8080] (webpack)-dev-server/client?http://localhost:8080 7.78 KiB {main} [built]
[./node_modules/webpack-dev-server/client/overlay.js] (webpack)-dev-server/client/overlay.js 3.58 KiB {main} [built]
[./node_modules/webpack-dev-server/client/socket.js] (webpack)-dev-server/client/socket.js 1.05 KiB {main} [built]
[./node_modules/webpack-dev-server/node_modules/strip-ansi/index.js] (webpack)-dev-server/node_modules/strip-ansi/index.js 161 bytes {main} [built]
[./node_modules/webpack/buildin/global.js] (webpack)/buildin/global.js 472 bytes {main} [built]
[./node_modules/webpack/hot sync ^\.\/log$] (webpack)/hot sync nonrecursive ^\.\/log$ 170 bytes {main} [built]
[./node_modules/webpack/hot/emitter.js] (webpack)/hot/emitter.js 75 bytes {main} [built]
[./src/js/index.js] 1.39 KiB {main} [built]
    + 342 hidden modules
Child html-webpack-plugin for "index.html":
     1 asset
    Entrypoint undefined = index.html
    [./node_modules/html-webpack-plugin/lib/loader.js!./index.html] 11.3 KiB {0} [built]
    [./node_modules/lodash/lodash.js] 527 KiB {0} [built]
    [./node_modules/webpack/buildin/global.js] (webpack)/buildin/global.js 472 bytes {0} [built]
    [./node_modules/webpack/buildin/module.js] (webpack)/buildin/module.js 497 bytes {0} [built]
i ｢wdm｣: Compiled successfully.
