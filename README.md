# es4x-test-reproducer
Simple reproducer for es4x test module loading on windows

* to reproduce js loader error, use `npm run test-js`
* to reproduce mjs loader error, use `npm run test-mjs`
* to reproduce mjs loader error with test file in root directory, use `npm run test-index`

ES4X release 0.16.1 resolves some errors, but under the mjs loader import fails on non-trivial modules like @vertx/unit.
