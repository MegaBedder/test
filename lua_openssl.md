Name | Version | OpenSSL/LibreSSL version | Dependencies | Description
-- | -- | -- | -- | --
[LuaSec](https://luarocks.org/modules/brunoos/luasec) | 0.7-1 (119 days ago) | OpenSSL >= 0.9.8f, < 1.1.0 | lua >= 5.1 and LuaSocket | LuaSec is a binding for OpenSSL library to provide TLS/SSL communication, and integrates with LuaSocket to make it easy to add secure connections to any Lua applications or scripts. [Integration with luaossl](https://github.com/brunoos/luasec/tree/master/samples/luaossl): Allow passing a luaossl context for socket creation/wrapping
[luaossl](https://luarocks.org/modules/daurnimator/luaossl) | 20180708-0 (108 days ago) | OpenSSL >= 1.0.0, < 1.1.0 or LibreSSL >= 2.0.0, < 2.7.0 | lua > 5.1, < 5.3 or LuaJIT | Most comprehensive OpenSSL module in the Lua universe.
[LuaCrypto](https://luarocks.org/modules/luarocks/luacrypto) | 0.3.2 [25/Apr/2013] | OpenSSL >= 0.9.7 | lua >= 5.1, < 5.2 | LuaCrypto provides a Lua frontend to the OpenSSL cryptographic library. This project is [deprecated](https://github.com/mkottman/luacrypto/issues/39), use luaossl
[LuaCrypto-baikal](https://luarocks.org/modules/ealogar/luacrypto-baikal) | 1.0-0 (0.3.2-fork) (358 days ago) | OpenSSL >= 0.9.7 | lua >= 5.1, < 5.4 | This is a [fork of LuaCrypto](https://github.com/mkottman/luacrypto/compare/master...greatwolf:master) v0.3.1
lua-[openssl](https://luarocks.org/modules/zhaozg/openssl) | 0.7.2 DEV (138 days ago) | OpenSSL >= 0.9.8 | Lua >= 5.1, < 5.2 or LuaJIT >= 2.0, < 2.1 | OpenSSL toolkit for Lua - A OpenSSL binding for Lua, which have [LuaCrypto-compat](http://mkottman.github.io/luacrypto/manual.html#reference) module and [luasec-compat](https://github.com/brunoos/luasec/wiki/LuaSec-0.5) module
[openssl-baikal](https://luarocks.org/modules/ealogar/openssl-baikal) | 1.0.0-1 (154 days ago) | OpenSSL <= 1.0.0 | lua >= 5.1, < 5.3 | This is a [fork of lua-openssl](https://github.com/zhaozg/lua-openssl/compare/master...ealogar:release/1.0.0) to avoid unexpected problems when installing it via luarocks. (The original repository owner does not publis releases and sometimes our installation breaks.)