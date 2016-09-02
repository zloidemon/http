install(FILES json.lua DESTINATION ${TARANTOOL_INSTALL_LUADIR}/http/plugins)
install(FILES msgpack.lua DESTINATION ${TARANTOOL_INSTALL_LUADIR}/http/plugins)
add_subdirectory(jsonrpc)
