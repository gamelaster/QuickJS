# QuickJS
Fork of QuickJS with improvements (mostly Windows support)

# Compilation

## Windows (MSVC)

Open solution and build it

## Windows (Cross-compile on Debian/Ubuntu)

(enable the WIN32 macro in Makefile):
```bash
sudo apt install gcc-mingw-w64-i686
make
```

# Actual state

Most of things are implemented, although, some features couldn't work.
List of working and planned features:
- [x] 32 bit support
- [x] 64 bit support
- [x] libquickjs.lib static library
- [x] qjs.exe
- [x] qjsc.exe
- [x] test_builtin.js test passed
- [x] test_loop.js test passed
- [x] test_op.js test passed
- [ ] Bignum support
- [ ] .dll modules support
- [ ] microbench.js test passed
- [ ] test_bjson.js test passed
- [ ] test_closure.js test passed
- [ ] test_std.js test passed