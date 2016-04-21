# Polymer
Polymer web UI framework - testing

https://www.polymer-project.org/1.0/docs/start/psk/set-up.html
Node.js
Node Package Manager (npm)

Download and install as admin..

~/source/Polymer/polymer-starter (master)
$ npm install
npm WARN optional dep failed, continuing fsevents@1.0.11
browser-sync@2.12.3 node_modules\browser-sync
├── ucfirst@1.0.0
├── emitter-steward@1.0.0
├── dev-ip@1.0.1
├── immutable@3.7.6
├── ua-parser-js@0.7.10
├── qs@6.1.0
├── opn@3.0.3 (object-assign@4.0.1)
├── browser-sync-client@2.4.2 (etag@1.7.0, fresh@0.3.0)
├── http-proxy@1.13.2 (eventemitter3@1.2.0, requires-port@1.0.0)
├── portscanner@1.0.0 (async@0.1.15)
├── serve-static@1.10.2 (escape-html@1.0.3, parseurl@1.3.1, send@0.13.1)
├── connect@3.4.1 (parseurl@1.3.1, utils-merge@1.0.0, debug@2.2.0, finalhandler@0.4.1)
├── resp-modifier@6.0.0 (debug@2.2.0, minimatch@2.0.10)
├── micromatch@2.3.7 (filename-regex@2.0.0, is-glob@2.0.1, is-extglob@1.0.0, normalize-path@2.0.1, extglob@0.3.2, array-unique@0.2.1, expand-brackets@0.1.5, regex-cache@0.4.3, arr-diff@2.0.0, kind-of@3.0.2, parse-glob@3.0.4, object.omit@2.0.0, braces@1.8.4)
├── fs-extra@0.26.7 (path-is-absolute@1.0.0, jsonfile@2.3.0, graceful-fs@4.1.3, klaw@1.2.0, rimraf@2.5.2)
├── socket.io@1.4.5 (has-binary@0.1.7, debug@2.2.0, socket.io-parser@2.2.6, socket.io-adapter@0.4.0, engine.io@1.6.8, socket.io-client@1.4.5)
├── serve-index@1.7.3 (escape-html@1.0.3, parseurl@1.3.1, batch@0.5.3, http-errors@1.3.1, mime-types@2.1.10, accepts@1.2.13, debug@2.2.0)
├── yargs@4.4.0 (camelcase@2.1.1, decamelize@1.2.0, y18n@3.2.1, yargs-parser@2.4.0, window-size@0.2.0, require-main-filename@1.0.1, lodash.assign@4.0.8, cliui@3.2.0, os-locale@1.4.0, string-width@1.0.1, pkg-conf@1.1.2, read-pkg-up@1.0.1)
├── localtunnel@1.8.1 (openurl@1.1.0, debug@2.2.0, yargs@3.29.0, request@2.65.0)
├── chokidar@1.4.3 (path-is-absolute@1.0.0, inherits@2.0.1, glob-parent@2.0.0, async-each@1.0.0, is-glob@2.0.1, anymatch@1.3.0, is-binary-path@1.0.1, readdirp@2.0.0)
├── bs-recipes@1.2.2
├── easy-extender@2.3.2 (lodash@3.10.1)
├── eazy-logger@2.1.3 (lodash.clonedeep@4.3.1, tfunk@3.0.2, opt-merger@1.1.1)
├── lodash@4.10.0
└── browser-sync-ui@0.5.19 (async-each-series@0.1.1, stream-throttle@0.1.3, weinre@2.0.0-pre-I0Z7U9OV)

$ npm install -g gulp
npm WARN deprecated graceful-fs@3.0.8: graceful-fs version 3 and before will fail on newer node releases. Please update to graceful-fs@^4.0.0 as soon as possible.
npm WARN deprecated lodash@1.0.2: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm WARN deprecated graceful-fs@1.2.3: graceful-fs version 3 and before will fail on newer node releases. Please update to graceful-fs@^4.0.0 as soon as possible.
C:\Users\auntiedt\AppData\Roaming\npm\gulp -> C:\Users\auntiedt\AppData\Roaming\npm\node_modules\gulp\bin\gulp.js
gulp@3.9.1 C:\Users\auntiedt\AppData\Roaming\npm\node_modules\gulp
├── interpret@1.0.0
├── pretty-hrtime@1.0.2
├── deprecated@0.0.1
├── archy@1.0.0
├── minimist@1.2.0
├── tildify@1.2.0 (os-homedir@1.0.1)
├── v8flags@2.0.11 (user-home@1.1.1)
├── semver@4.3.6
├── chalk@1.1.3 (escape-string-regexp@1.0.5, ansi-styles@2.2.1, supports-color@2.0.0, has-ansi@2.0.0, strip-ansi@3.0.1)
├── orchestrator@0.3.7 (stream-consume@0.1.0, sequencify@0.0.7, end-of-stream@0.1.5)
├── liftoff@2.2.1 (extend@2.0.1, rechoir@0.6.2, flagged-respawn@0.3.2, findup-sync@0.3.0, resolve@1.1.7)
├── vinyl-fs@0.3.14 (graceful-fs@3.0.8, strip-bom@1.0.0, defaults@1.0.3, vinyl@0.4.6, through2@0.6.5, mkdirp@0.5.1, glob-stream@3.1.18, glob-watcher@0.0.6)
└── gulp-util@3.0.7 (array-differ@1.0.0, array-uniq@1.0.2, lodash._reinterpolate@3.0.0, lodash._reescape@3.0.0, lodash._reevaluate@3.0.0, beeper@1.1.0, object-assign@3.0.0, replace-ext@0.0.1, fancy-log@1.2.0, has-gulplog@0.1.0, vinyl@0.5.3, gulplog@1.0.0, lodash.template@3.6.2, through2@2.0.1, multipipe@0.1.2, dateformat@1.0.12)

Build the app locally.
$ gulp
[17:59:41] Using gulpfile ~\source\Polymer\polymer-starter\gulpfile.js
[17:59:41] Starting 'clean'...
[17:59:41] Finished 'clean' after 7.39 ms
[17:59:41] Starting 'default'...
[17:59:41] Starting 'ensureFiles'...
[17:59:41] Finished 'ensureFiles' after 399 μs
[17:59:41] Starting 'copy'...
[17:59:43] Starting 'styles'...
[17:59:53] styles all files 120 B
[17:59:53] Finished 'styles' after 9.79 s
[17:59:54] copy all files 1.13 MB
[17:59:54] Finished 'copy' after 12 s
[17:59:54] Starting 'images'...
[18:00:03] Starting 'fonts'...
[18:00:03] Starting 'html'...
[18:00:13] Finished 'fonts' after 9.68 s
[18:00:15] html all files 54.8 kB
[18:00:15] Finished 'html' after 12 s
[18:00:15] gulp-imagemin: Minified 9 images (saved 1.27 kB - 1.9%)
[18:00:15] images all files 65.21 kB
[18:00:15] Finished 'images' after 22 s
[18:00:15] Starting 'vulcanize'...
[18:00:20] vulcanize all files 517.63 kB
[18:00:20] Finished 'vulcanize' after 5.02 s
[18:00:20] Finished 'default' after 39 s

gulp serve

