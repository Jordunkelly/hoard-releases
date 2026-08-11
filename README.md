# hoard-releases
Public release channel for Hoard. Binaries only

[10:35:44 PM] 
[System] Starting sync execution (90 days lookback)...
[10:35:45 PM] [Error] node:internal/modules/cjs/loader:1155
  throw err;
  ^

Error: Cannot find module '../lib/wallet-client'
Require stack:
- C:\Users\jordu\AppData\Local\Programs\hoard-finance\resources\app\dist-scripts\scripts\import-banks.js
- C:\Users\jordu\AppData\Local\Programs\hoard-finance\resources\app\dist-scripts\scripts\run-sync.js
    at Module._resolveFilename (node:internal/modules/cjs/loader:1152:15)
    at Module._load (node:internal/modules/cjs/loader:993:27)
    at c._load (node:electron/js2c/node_init:2:13801)
    at Module.require (node:internal/modules/cjs/loader:1240:19)
    at require (node:internal/modules/helpers:179:18)
    at Object.<anonymous> (C:\Users\jordu\AppData\Local\Programs\hoard-finance\resources\app\dist-scripts\scripts\import-banks.js:42:25)
    at Module._compile (node:internal/modules/cjs/loader:1373:14)
    at Module._extensions..js (node:internal/modules/cjs/loader:1432:10)
    at Module.load (node:internal/modules/cjs/loader:1215:32)
    at Module._load (node:internal/modules/cjs/loader:1031:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    'C:\\Users\\jordu\\AppData\\Local\\Programs\\hoard-finance\\resources\\app\\dist-scripts\\scripts\\import-banks.js',
    'C:\\Users\\jordu\\AppData\\Local\\Programs\\hoard-finance\\resources\\app\\dist-scripts\\scripts\\run-sync.js'
  ]
}

Node.js v20.16.0
