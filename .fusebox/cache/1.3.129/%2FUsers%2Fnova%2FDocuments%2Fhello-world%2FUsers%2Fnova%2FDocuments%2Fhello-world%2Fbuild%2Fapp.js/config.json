const fsbx = require('fuse-box');

let fuse = fsbx.FuseBox.init({
    homeDir: "src/",
    globals: { default: "myLib" },
    outFile: "./build/app.js"
});

fuse.bundle(">index.js");