# Copyright(C) 2016 LuaDist.
# Created by Peter Kapec
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project( lua-resty-template NONE )
cmake_minimum_required( VERSION 2.8 )
include( cmake/dist.cmake )
include( lua )

install_lua_module( resty.template 		lib/resty/template.lua )
install_lua_module( resty.template.html lib/resty/template/html.lua )
install_lua_module( resty.template.microbenchmark	lib/resty/template/microbenchmark.lua )

install_data( Changes.md README.md LICENSE )
