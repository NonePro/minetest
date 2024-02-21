## 目录结构
├── CMakeLists.txt
├── CNAME
├── COPYING.LESSER
├── Dockerfile
├── LICENSE.txt
├── README.md
├── android
│   ├── app
│   ├── build.gradle
│   ├── gradle
│   ├── gradle.properties
│   ├── gradlew
│   ├── gradlew.bat
│   ├── icons
│   ├── keystore-minetest.jks
│   ├── native
│   └── settings.gradle
├── bin
│   └── minetest
├── build
│   ├── CMakeCache.txt
│   ├── CMakeCache.txt.tmpf90cd
│   ├── CMakeFiles
│   ├── CPackConfig.cmake
│   ├── CPackSourceConfig.cmake
│   ├── Makefile
│   ├── Testing
│   ├── build.ninja
│   ├── cmake_install.cmake
│   ├── compile_commands.json
│   ├── install_manifest.txt
│   ├── lib
│   ├── locale
│   ├── macos
│   └── src
├── builtin
│   ├── async
│   ├── client
│   ├── common
│   ├── emerge
│   ├── fstk
│   ├── game
│   ├── init.lua
│   ├── locale
│   ├── mainmenu
│   ├── profiler
│   └── settingtypes.txt
├── cache
│   └── cdb
├── client
│   ├── serverlist
│   └── shaders
├── clientmods
│   └── preview
├── cmake
│   └── Modules
├── debug.txt
├── doc
│   ├── Doxyfile.in
│   ├── android.md
│   ├── breakages.md
│   ├── builtin_entities.md
│   ├── client_lua_api.md
│   ├── compiling
│   ├── developing
│   ├── direction.md
│   ├── fst_api.txt
│   ├── lgpl-2.1.txt
│   ├── lua_api.md
│   ├── lua_api.txt
│   ├── main_page.dox
│   ├── menu_lua_api.md
│   ├── minetest.6
│   ├── minetestserver.6
│   ├── mkdocs
│   ├── mod_channels.png
│   ├── protocol.txt
│   ├── texture_packs.md
│   └── world_format.md
├── fonts
│   ├── Arimo-Bold.ttf
│   ├── Arimo-BoldItalic.ttf
│   ├── Arimo-Italic.ttf
│   ├── Arimo-LICENSE.txt
│   ├── Arimo-Regular.ttf
│   ├── Cousine-Bold.ttf
│   ├── Cousine-BoldItalic.ttf
│   ├── Cousine-Italic.ttf
│   ├── Cousine-LICENSE.txt
│   ├── Cousine-Regular.ttf
│   ├── DroidSansFallbackFull-LICENSE.txt
│   └── DroidSansFallbackFull.ttf
├── games
│   └── devtest
├── lib
│   ├── bitop
│   ├── catch2
│   ├── gmp
│   ├── irrlichtmt
│   ├── jsoncpp
│   └── lua
├── locale
│   ├── be
│   ├── bg
│   ├── ca
│   ├── cs
│   ├── cy
│   ├── da
│   ├── de
│   ├── el
│   ├── eo
│   ├── es
│   ├── et
│   ├── eu
│   ├── fa
│   ├── fi
│   ├── fil
│   ├── fr
│   ├── ga
│   ├── gd
│   ├── gl
│   ├── hu
│   ├── ia
│   ├── id
│   ├── it
│   ├── ja
│   ├── jbo
│   ├── jv
│   ├── kk
│   ├── ko
│   ├── ky
│   ├── lt
│   ├── lv
│   ├── lzh
│   ├── mi
│   ├── mn
│   ├── mr
│   ├── ms
│   ├── nb
│   ├── nl
│   ├── nn
│   ├── oc
│   ├── pl
│   ├── pt
│   ├── pt_BR
│   ├── ro
│   ├── ru
│   ├── sk
│   ├── sl
│   ├── sr_Cyrl
│   ├── sr_Latn
│   ├── sv
│   ├── sw
│   ├── tr
│   ├── tt
│   ├── uk
│   ├── vi
│   ├── yue
│   ├── zh_CN
│   └── zh_TW
├── minetest.conf
├── minetest.conf.example
├── misc
│   ├── AppImageBuilder.yml
│   ├── CPACK_WIX_UI_BANNER.BMP
│   ├── CPACK_WIX_UI_DIALOG.BMP
│   ├── Info.plist
│   ├── irrlichtmt_tag.txt
│   ├── make_redirects.sh
│   ├── minetest-icon-24x24.png
│   ├── minetest-icon.icns
│   ├── minetest-icon.ico
│   ├── minetest-xorg-icon-128.png
│   ├── minetest.exe.manifest
│   ├── minetest.svg
│   ├── net.minetest.minetest.appdata.xml
│   ├── net.minetest.minetest.desktop
│   ├── redirect.html
│   └── winresource.rc
├── mods
│   └── mods_here.txt
├── po
│   ├── ar
│   ├── be
│   ├── bg
│   ├── ca
│   ├── cs
│   ├── cy
│   ├── da
│   ├── de
│   ├── dv
│   ├── el
│   ├── eo
│   ├── es
│   ├── et
│   ├── eu
│   ├── fa
│   ├── fi
│   ├── fil
│   ├── fr
│   ├── ga
│   ├── gd
│   ├── gl
│   ├── he
│   ├── hi
│   ├── hu
│   ├── ia
│   ├── id
│   ├── it
│   ├── ja
│   ├── jbo
│   ├── jv
│   ├── kk
│   ├── kn
│   ├── ko
│   ├── ky
│   ├── lt
│   ├── lv
│   ├── lzh
│   ├── mi
│   ├── minetest.pot
│   ├── mn
│   ├── mr
│   ├── ms
│   ├── ms_Arab
│   ├── nb
│   ├── nl
│   ├── nn
│   ├── oc
│   ├── pl
│   ├── pt
│   ├── pt_BR
│   ├── ro
│   ├── ru
│   ├── sk
│   ├── sl
│   ├── sr_Cyrl
│   ├── sr_Latn
│   ├── sv
│   ├── sw
│   ├── th
│   ├── tr
│   ├── tt
│   ├── uk
│   ├── vi
│   ├── yue
│   ├── zh_CN
│   └── zh_TW
├── src
│   ├── CMakeLists.txt
│   ├── activeobject.h
│   ├── activeobjectmgr.h
│   ├── benchmark
│   ├── chat.cpp
│   ├── chat.h
│   ├── chat_interface.h
│   ├── chatmessage.h
│   ├── client
│   ├── clientdynamicinfo.h
│   ├── cmake_config.h.in
│   ├── cmake_config_githash.h.in
│   ├── collision.cpp
│   ├── collision.h
│   ├── config.h
│   ├── constants.h
│   ├── content
│   ├── content_mapnode.cpp
│   ├── content_mapnode.h
│   ├── content_nodemeta.cpp
│   ├── content_nodemeta.h
│   ├── convert_json.cpp
│   ├── convert_json.h
│   ├── craftdef.cpp
│   ├── craftdef.h
│   ├── database
│   ├── daynightratio.h
│   ├── debug.cpp
│   ├── debug.h
│   ├── defaultsettings.cpp
│   ├── defaultsettings.h
│   ├── dummygamedef.h
│   ├── dummymap.h
│   ├── emerge.cpp
│   ├── emerge.h
│   ├── emerge_internal.h
│   ├── environment.cpp
│   ├── environment.h
│   ├── exceptions.h
│   ├── face_position_cache.cpp
│   ├── face_position_cache.h
│   ├── filesys.cpp
│   ├── filesys.h
│   ├── gamedef.h
│   ├── gameparams.h
│   ├── gettext.cpp
│   ├── gettext.h
│   ├── gettime.h
│   ├── gui
│   ├── httpfetch.cpp
│   ├── httpfetch.h
│   ├── hud.cpp
│   ├── hud.h
│   ├── inventory.cpp
│   ├── inventory.h
│   ├── inventorymanager.cpp
│   ├── inventorymanager.h
│   ├── irr_aabb3d.h
│   ├── irr_ptr.h
│   ├── irr_v2d.h
│   ├── irr_v3d.h
│   ├── irrlicht_changes
│   ├── irrlichttypes.h
│   ├── irrlichttypes_bloated.h
│   ├── irrlichttypes_extrabloated.h
│   ├── itemdef.cpp
│   ├── itemdef.h
│   ├── itemgroup.h
│   ├── itemstackmetadata.cpp
│   ├── itemstackmetadata.h
│   ├── json-forwards.h
│   ├── light.cpp
│   ├── light.h
│   ├── lighting.cpp
│   ├── lighting.h
│   ├── log.cpp
│   ├── log.h
│   ├── main.cpp
│   ├── map.cpp
│   ├── map.h
│   ├── map_settings_manager.cpp
│   ├── map_settings_manager.h
│   ├── mapblock.cpp
│   ├── mapblock.h
│   ├── mapgen
│   ├── mapnode.cpp
│   ├── mapnode.h
│   ├── mapsector.cpp
│   ├── mapsector.h
│   ├── metadata.cpp
│   ├── metadata.h
│   ├── modchannels.cpp
│   ├── modchannels.h
│   ├── modifiedstate.h
│   ├── nameidmapping.cpp
│   ├── nameidmapping.h
│   ├── network
│   ├── nodedef.cpp
│   ├── nodedef.h
│   ├── nodemetadata.cpp
│   ├── nodemetadata.h
│   ├── nodetimer.cpp
│   ├── nodetimer.h
│   ├── noise.cpp
│   ├── noise.h
│   ├── objdef.cpp
│   ├── objdef.h
│   ├── object_properties.cpp
│   ├── object_properties.h
│   ├── particles.cpp
│   ├── particles.h
│   ├── pathfinder.cpp
│   ├── pathfinder.h
│   ├── player.cpp
│   ├── player.h
│   ├── porting.cpp
│   ├── porting.h
│   ├── porting_android.cpp
│   ├── porting_android.h
│   ├── profiler.cpp
│   ├── profiler.h
│   ├── raycast.cpp
│   ├── raycast.h
│   ├── reflowscan.cpp
│   ├── reflowscan.h
│   ├── remoteplayer.cpp
│   ├── remoteplayer.h
│   ├── rollback_interface.cpp
│   ├── rollback_interface.h
│   ├── script
│   ├── serialization.cpp
│   ├── serialization.h
│   ├── server
│   ├── server.cpp
│   ├── server.h
│   ├── serverenvironment.cpp
│   ├── serverenvironment.h
│   ├── settings.cpp
│   ├── settings.h
│   ├── settings_translation_file.cpp
│   ├── skyparams.h
│   ├── sound.h
│   ├── staticobject.cpp
│   ├── staticobject.h
│   ├── terminal_chat_console.cpp
│   ├── terminal_chat_console.h
│   ├── texture_override.cpp
│   ├── texture_override.h
│   ├── threading
│   ├── tileanimation.cpp
│   ├── tileanimation.h
│   ├── tool.cpp
│   ├── tool.h
│   ├── translation.cpp
│   ├── translation.h
│   ├── unittest
│   ├── unsupported_language_list.txt
│   ├── util
│   ├── version.cpp
│   ├── version.h
│   ├── voxel.cpp
│   ├── voxel.h
│   ├── voxelalgorithms.cpp
│   └── voxelalgorithms.h
├── textures
│   ├── base
│   └── texture_packs_here.txt
├── util
│   ├── README_mod_translation_updater.md
│   ├── buildbot
│   ├── bump_version.sh
│   ├── ci
│   ├── gather_git_credits.py
│   ├── helper_mod
│   ├── mod_translation_updater.py
│   ├── reorder_translation_commits.py
│   ├── stress_mapgen.sh
│   ├── test_multiplayer.sh
│   ├── updatepo.sh
│   └── wireshark
└── worlds
    └── worlds_here.txt

## src代码结构

├── CMakeLists.txt
├── activeobject.h
├── activeobjectmgr.h
├── benchmark
│   ├── CMakeLists.txt
│   ├── benchmark.cpp
│   ├── benchmark.h
│   ├── benchmark_lighting.cpp
│   ├── benchmark_mapblock.cpp
│   ├── benchmark_mapmodify.cpp
│   ├── benchmark_serialize.cpp
│   └── benchmark_setup.h
├── chat.cpp
├── chat.h
├── chat_interface.h
├── chatmessage.h
├── client
│   ├── CMakeLists.txt
│   ├── activeobjectmgr.cpp
│   ├── activeobjectmgr.h
│   ├── camera.cpp
│   ├── camera.h
│   ├── client.cpp
│   ├── client.h
│   ├── clientenvironment.cpp
│   ├── clientenvironment.h
│   ├── clientevent.h
│   ├── clientlauncher.cpp
│   ├── clientlauncher.h
│   ├── clientmap.cpp
│   ├── clientmap.h
│   ├── clientmedia.cpp
│   ├── clientmedia.h
│   ├── clientobject.cpp
│   ├── clientobject.h
│   ├── clientsimpleobject.h
│   ├── clouds.cpp
│   ├── clouds.h
│   ├── content_cao.cpp
│   ├── content_cao.h
│   ├── content_cso.cpp
│   ├── content_cso.h
│   ├── content_mapblock.cpp
│   ├── content_mapblock.h
│   ├── event_manager.h
│   ├── filecache.cpp
│   ├── filecache.h
│   ├── fontengine.cpp
│   ├── fontengine.h
│   ├── game.cpp
│   ├── game.h
│   ├── gameui.cpp
│   ├── gameui.h
│   ├── guiscalingfilter.cpp
│   ├── guiscalingfilter.h
│   ├── hud.cpp
│   ├── hud.h
│   ├── imagefilters.cpp
│   ├── imagefilters.h
│   ├── inputhandler.cpp
│   ├── inputhandler.h
│   ├── joystick_controller.cpp
│   ├── joystick_controller.h
│   ├── keycode.cpp
│   ├── keycode.h
│   ├── keys.h
│   ├── localplayer.cpp
│   ├── localplayer.h
│   ├── mapblock_mesh.cpp
│   ├── mapblock_mesh.h
│   ├── mesh.cpp
│   ├── mesh.h
│   ├── mesh_generator_thread.cpp
│   ├── mesh_generator_thread.h
│   ├── meshgen
│   │   ├── collector.cpp
│   │   └── collector.h
│   ├── minimap.cpp
│   ├── minimap.h
│   ├── mtevent.h
│   ├── particles.cpp
│   ├── particles.h
│   ├── render
│   │   ├── anaglyph.cpp
│   │   ├── anaglyph.h
│   │   ├── core.cpp
│   │   ├── core.h
│   │   ├── factory.cpp
│   │   ├── factory.h
│   │   ├── interlaced.cpp
│   │   ├── interlaced.h
│   │   ├── pipeline.cpp
│   │   ├── pipeline.h
│   │   ├── plain.cpp
│   │   ├── plain.h
│   │   ├── secondstage.cpp
│   │   ├── secondstage.h
│   │   ├── sidebyside.cpp
│   │   ├── sidebyside.h
│   │   ├── stereo.cpp
│   │   └── stereo.h
│   ├── renderingengine.cpp
│   ├── renderingengine.h
│   ├── shader.cpp
│   ├── shader.h
│   ├── shadows
│   │   ├── dynamicshadows.cpp
│   │   ├── dynamicshadows.h
│   │   ├── dynamicshadowsrender.cpp
│   │   ├── dynamicshadowsrender.h
│   │   ├── shadowsScreenQuad.cpp
│   │   ├── shadowsScreenQuad.h
│   │   ├── shadowsshadercallbacks.cpp
│   │   └── shadowsshadercallbacks.h
│   ├── sky.cpp
│   ├── sky.h
│   ├── sound
│   │   ├── al_extensions.cpp
│   │   ├── al_extensions.h
│   │   ├── al_helpers.cpp
│   │   ├── al_helpers.h
│   │   ├── ogg_file.cpp
│   │   ├── ogg_file.h
│   │   ├── playing_sound.cpp
│   │   ├── playing_sound.h
│   │   ├── proxy_sound_manager.cpp
│   │   ├── proxy_sound_manager.h
│   │   ├── sound_constants.h
│   │   ├── sound_data.cpp
│   │   ├── sound_data.h
│   │   ├── sound_manager.cpp
│   │   ├── sound_manager.h
│   │   ├── sound_manager_messages.h
│   │   ├── sound_openal.cpp
│   │   ├── sound_openal.h
│   │   ├── sound_singleton.cpp
│   │   └── sound_singleton.h
│   ├── sound.cpp
│   ├── sound.h
│   ├── tile.cpp
│   ├── tile.h
│   ├── wieldmesh.cpp
│   └── wieldmesh.h
├── clientdynamicinfo.h
├── cmake_config.h.in
├── cmake_config_githash.h.in
├── collision.cpp
├── collision.h
├── config.h
├── constants.h
├── content
│   ├── CMakeLists.txt
│   ├── content.cpp
│   ├── content.h
│   ├── mod_configuration.cpp
│   ├── mod_configuration.h
│   ├── mods.cpp
│   ├── mods.h
│   ├── subgames.cpp
│   └── subgames.h
├── content_mapnode.cpp
├── content_mapnode.h
├── content_nodemeta.cpp
├── content_nodemeta.h
├── convert_json.cpp
├── convert_json.h
├── craftdef.cpp
├── craftdef.h
├── database
│   ├── CMakeLists.txt
│   ├── database-dummy.cpp
│   ├── database-dummy.h
│   ├── database-files.cpp
│   ├── database-files.h
│   ├── database-leveldb.cpp
│   ├── database-leveldb.h
│   ├── database-postgresql.cpp
│   ├── database-postgresql.h
│   ├── database-redis.cpp
│   ├── database-redis.h
│   ├── database-sqlite3.cpp
│   ├── database-sqlite3.h
│   ├── database.cpp
│   └── database.h
├── daynightratio.h
├── debug.cpp
├── debug.h
├── defaultsettings.cpp
├── defaultsettings.h
├── dummygamedef.h
├── dummymap.h
├── emerge.cpp
├── emerge.h
├── emerge_internal.h
├── environment.cpp
├── environment.h
├── exceptions.h
├── face_position_cache.cpp
├── face_position_cache.h
├── filesys.cpp
├── filesys.h
├── gamedef.h
├── gameparams.h
├── gettext.cpp
├── gettext.h
├── gettime.h
├── gui
│   ├── CMakeLists.txt
│   ├── StyleSpec.h
│   ├── guiAnimatedImage.cpp
│   ├── guiAnimatedImage.h
│   ├── guiBackgroundImage.cpp
│   ├── guiBackgroundImage.h
│   ├── guiBox.cpp
│   ├── guiBox.h
│   ├── guiButton.cpp
│   ├── guiButton.h
│   ├── guiButtonImage.cpp
│   ├── guiButtonImage.h
│   ├── guiButtonItemImage.cpp
│   ├── guiButtonItemImage.h
│   ├── guiChatConsole.cpp
│   ├── guiChatConsole.h
│   ├── guiEditBox.cpp
│   ├── guiEditBox.h
│   ├── guiEditBoxWithScrollbar.cpp
│   ├── guiEditBoxWithScrollbar.h
│   ├── guiEngine.cpp
│   ├── guiEngine.h
│   ├── guiFormSpecMenu.cpp
│   ├── guiFormSpecMenu.h
│   ├── guiHyperText.cpp
│   ├── guiHyperText.h
│   ├── guiInventoryList.cpp
│   ├── guiInventoryList.h
│   ├── guiItemImage.cpp
│   ├── guiItemImage.h
│   ├── guiKeyChangeMenu.cpp
│   ├── guiKeyChangeMenu.h
│   ├── guiMainMenu.h
│   ├── guiPasswordChange.cpp
│   ├── guiPasswordChange.h
│   ├── guiPathSelectMenu.cpp
│   ├── guiPathSelectMenu.h
│   ├── guiScene.cpp
│   ├── guiScene.h
│   ├── guiScrollBar.cpp
│   ├── guiScrollBar.h
│   ├── guiScrollContainer.cpp
│   ├── guiScrollContainer.h
│   ├── guiSkin.cpp
│   ├── guiSkin.h
│   ├── guiTable.cpp
│   ├── guiTable.h
│   ├── guiVolumeChange.cpp
│   ├── guiVolumeChange.h
│   ├── mainmenumanager.h
│   ├── modalMenu.cpp
│   ├── modalMenu.h
│   ├── profilergraph.cpp
│   ├── profilergraph.h
│   ├── touchscreengui.cpp
│   └── touchscreengui.h
├── httpfetch.cpp
├── httpfetch.h
├── hud.cpp
├── hud.h
├── inventory.cpp
├── inventory.h
├── inventorymanager.cpp
├── inventorymanager.h
├── irr_aabb3d.h
├── irr_ptr.h
├── irr_v2d.h
├── irr_v3d.h
├── irrlicht_changes
│   ├── CGUITTFont.cpp
│   ├── CGUITTFont.h
│   ├── CMakeLists.txt
│   ├── printing.h
│   ├── static_text.cpp
│   └── static_text.h
├── irrlichttypes.h
├── irrlichttypes_bloated.h
├── irrlichttypes_extrabloated.h
├── itemdef.cpp
├── itemdef.h
├── itemgroup.h
├── itemstackmetadata.cpp
├── itemstackmetadata.h
├── json-forwards.h
├── light.cpp
├── light.h
├── lighting.cpp
├── lighting.h
├── log.cpp
├── log.h
├── main.cpp
├── map.cpp
├── map.h
├── map_settings_manager.cpp
├── map_settings_manager.h
├── mapblock.cpp
├── mapblock.h
├── mapgen
│   ├── CMakeLists.txt
│   ├── cavegen.cpp
│   ├── cavegen.h
│   ├── dungeongen.cpp
│   ├── dungeongen.h
│   ├── mapgen.cpp
│   ├── mapgen.h
│   ├── mapgen_carpathian.cpp
│   ├── mapgen_carpathian.h
│   ├── mapgen_flat.cpp
│   ├── mapgen_flat.h
│   ├── mapgen_fractal.cpp
│   ├── mapgen_fractal.h
│   ├── mapgen_singlenode.cpp
│   ├── mapgen_singlenode.h
│   ├── mapgen_v5.cpp
│   ├── mapgen_v5.h
│   ├── mapgen_v6.cpp
│   ├── mapgen_v6.h
│   ├── mapgen_v7.cpp
│   ├── mapgen_v7.h
│   ├── mapgen_valleys.cpp
│   ├── mapgen_valleys.h
│   ├── mg_biome.cpp
│   ├── mg_biome.h
│   ├── mg_decoration.cpp
│   ├── mg_decoration.h
│   ├── mg_ore.cpp
│   ├── mg_ore.h
│   ├── mg_schematic.cpp
│   ├── mg_schematic.h
│   ├── treegen.cpp
│   └── treegen.h
├── mapnode.cpp
├── mapnode.h
├── mapsector.cpp
├── mapsector.h
├── metadata.cpp
├── metadata.h
├── modchannels.cpp
├── modchannels.h
├── modifiedstate.h
├── nameidmapping.cpp
├── nameidmapping.h
├── network
│   ├── CMakeLists.txt
│   ├── address.cpp
│   ├── address.h
│   ├── clientopcodes.cpp
│   ├── clientopcodes.h
│   ├── clientpackethandler.cpp
│   ├── connection.cpp
│   ├── connection.h
│   ├── connectionthreads.cpp
│   ├── connectionthreads.h
│   ├── networkexceptions.h
│   ├── networkpacket.cpp
│   ├── networkpacket.h
│   ├── networkprotocol.h
│   ├── peerhandler.h
│   ├── serveropcodes.cpp
│   ├── serveropcodes.h
│   ├── serverpackethandler.cpp
│   ├── socket.cpp
│   └── socket.h
├── nodedef.cpp
├── nodedef.h
├── nodemetadata.cpp
├── nodemetadata.h
├── nodetimer.cpp
├── nodetimer.h
├── noise.cpp
├── noise.h
├── objdef.cpp
├── objdef.h
├── object_properties.cpp
├── object_properties.h
├── particles.cpp
├── particles.h
├── pathfinder.cpp
├── pathfinder.h
├── player.cpp
├── player.h
├── porting.cpp
├── porting.h
├── porting_android.cpp
├── porting_android.h
├── profiler.cpp
├── profiler.h
├── raycast.cpp
├── raycast.h
├── reflowscan.cpp
├── reflowscan.h
├── remoteplayer.cpp
├── remoteplayer.h
├── rollback_interface.cpp
├── rollback_interface.h
├── script
│   ├── CMakeLists.txt
│   ├── common
│   │   ├── CMakeLists.txt
│   │   ├── c_content.cpp
│   │   ├── c_content.h
│   │   ├── c_converter.cpp
│   │   ├── c_converter.h
│   │   ├── c_internal.cpp
│   │   ├── c_internal.h
│   │   ├── c_packer.cpp
│   │   ├── c_packer.h
│   │   ├── c_types.cpp
│   │   ├── c_types.h
│   │   ├── helper.cpp
│   │   └── helper.h
│   ├── cpp_api
│   │   ├── CMakeLists.txt
│   │   ├── s_async.cpp
│   │   ├── s_async.h
│   │   ├── s_base.cpp
│   │   ├── s_base.h
│   │   ├── s_client.cpp
│   │   ├── s_client.h
│   │   ├── s_entity.cpp
│   │   ├── s_entity.h
│   │   ├── s_env.cpp
│   │   ├── s_env.h
│   │   ├── s_internal.h
│   │   ├── s_inventory.cpp
│   │   ├── s_inventory.h
│   │   ├── s_item.cpp
│   │   ├── s_item.h
│   │   ├── s_mainmenu.cpp
│   │   ├── s_mainmenu.h
│   │   ├── s_mapgen.cpp
│   │   ├── s_mapgen.h
│   │   ├── s_modchannels.cpp
│   │   ├── s_modchannels.h
│   │   ├── s_node.cpp
│   │   ├── s_node.h
│   │   ├── s_nodemeta.cpp
│   │   ├── s_nodemeta.h
│   │   ├── s_player.cpp
│   │   ├── s_player.h
│   │   ├── s_security.cpp
│   │   ├── s_security.h
│   │   ├── s_server.cpp
│   │   └── s_server.h
│   ├── lua_api
│   │   ├── CMakeLists.txt
│   │   ├── l_areastore.cpp
│   │   ├── l_areastore.h
│   │   ├── l_auth.cpp
│   │   ├── l_auth.h
│   │   ├── l_base.cpp
│   │   ├── l_base.h
│   │   ├── l_camera.cpp
│   │   ├── l_camera.h
│   │   ├── l_client.cpp
│   │   ├── l_client.h
│   │   ├── l_client_sound.cpp
│   │   ├── l_client_sound.h
│   │   ├── l_craft.cpp
│   │   ├── l_craft.h
│   │   ├── l_env.cpp
│   │   ├── l_env.h
│   │   ├── l_http.cpp
│   │   ├── l_http.h
│   │   ├── l_internal.h
│   │   ├── l_inventory.cpp
│   │   ├── l_inventory.h
│   │   ├── l_item.cpp
│   │   ├── l_item.h
│   │   ├── l_itemstackmeta.cpp
│   │   ├── l_itemstackmeta.h
│   │   ├── l_localplayer.cpp
│   │   ├── l_localplayer.h
│   │   ├── l_mainmenu.cpp
│   │   ├── l_mainmenu.h
│   │   ├── l_mainmenu_sound.cpp
│   │   ├── l_mainmenu_sound.h
│   │   ├── l_mapgen.cpp
│   │   ├── l_mapgen.h
│   │   ├── l_metadata.cpp
│   │   ├── l_metadata.h
│   │   ├── l_minimap.cpp
│   │   ├── l_minimap.h
│   │   ├── l_modchannels.cpp
│   │   ├── l_modchannels.h
│   │   ├── l_nodemeta.cpp
│   │   ├── l_nodemeta.h
│   │   ├── l_nodetimer.cpp
│   │   ├── l_nodetimer.h
│   │   ├── l_noise.cpp
│   │   ├── l_noise.h
│   │   ├── l_object.cpp
│   │   ├── l_object.h
│   │   ├── l_particleparams.h
│   │   ├── l_particles.cpp
│   │   ├── l_particles.h
│   │   ├── l_particles_local.cpp
│   │   ├── l_particles_local.h
│   │   ├── l_playermeta.cpp
│   │   ├── l_playermeta.h
│   │   ├── l_rollback.cpp
│   │   ├── l_rollback.h
│   │   ├── l_server.cpp
│   │   ├── l_server.h
│   │   ├── l_settings.cpp
│   │   ├── l_settings.h
│   │   ├── l_storage.cpp
│   │   ├── l_storage.h
│   │   ├── l_util.cpp
│   │   ├── l_util.h
│   │   ├── l_vmanip.cpp
│   │   └── l_vmanip.h
│   ├── scripting_client.cpp
│   ├── scripting_client.h
│   ├── scripting_emerge.cpp
│   ├── scripting_emerge.h
│   ├── scripting_mainmenu.cpp
│   ├── scripting_mainmenu.h
│   ├── scripting_server.cpp
│   └── scripting_server.h
├── serialization.cpp
├── serialization.h
├── server
│   ├── CMakeLists.txt
│   ├── activeobjectmgr.cpp
│   ├── activeobjectmgr.h
│   ├── ban.cpp
│   ├── ban.h
│   ├── clientiface.cpp
│   ├── clientiface.h
│   ├── luaentity_sao.cpp
│   ├── luaentity_sao.h
│   ├── mods.cpp
│   ├── mods.h
│   ├── player_sao.cpp
│   ├── player_sao.h
│   ├── rollback.cpp
│   ├── rollback.h
│   ├── serveractiveobject.cpp
│   ├── serveractiveobject.h
│   ├── serverinventorymgr.cpp
│   ├── serverinventorymgr.h
│   ├── serverlist.cpp
│   ├── serverlist.h
│   ├── unit_sao.cpp
│   └── unit_sao.h
├── server.cpp
├── server.h
├── serverenvironment.cpp
├── serverenvironment.h
├── settings.cpp
├── settings.h
├── settings_translation_file.cpp
├── skyparams.h
├── sound.h
├── staticobject.cpp
├── staticobject.h
├── terminal_chat_console.cpp
├── terminal_chat_console.h
├── texture_override.cpp
├── texture_override.h
├── threading
│   ├── CMakeLists.txt
│   ├── event.cpp
│   ├── event.h
│   ├── mutex_auto_lock.h
│   ├── semaphore.cpp
│   ├── semaphore.h
│   ├── thread.cpp
│   └── thread.h
├── tileanimation.cpp
├── tileanimation.h
├── tool.cpp
├── tool.h
├── translation.cpp
├── translation.h
├── unittest
│   ├── CMakeLists.txt
│   ├── mock_activeobject.h
│   ├── mock_inventorymanager.h
│   ├── mock_server.h
│   ├── mock_serveractiveobject.h
│   ├── test.cpp
│   ├── test.h
│   ├── test_activeobject.cpp
│   ├── test_address.cpp
│   ├── test_areastore.cpp
│   ├── test_authdatabase.cpp
│   ├── test_ban.cpp
│   ├── test_clientactiveobjectmgr.cpp
│   ├── test_collision.cpp
│   ├── test_compression.cpp
│   ├── test_connection.cpp
│   ├── test_craft.cpp
│   ├── test_datastructures.cpp
│   ├── test_eventmanager.cpp
│   ├── test_filesys.cpp
│   ├── test_gameui.cpp
│   ├── test_gettext.cpp
│   ├── test_inventory.cpp
│   ├── test_irrptr.cpp
│   ├── test_keycode.cpp
│   ├── test_lua.cpp
│   ├── test_map.cpp
│   ├── test_map_settings_manager.cpp
│   ├── test_mapnode.cpp
│   ├── test_modchannels.cpp
│   ├── test_modstoragedatabase.cpp
│   ├── test_moveaction.cpp
│   ├── test_nodedef.cpp
│   ├── test_noderesolver.cpp
│   ├── test_noise.cpp
│   ├── test_objdef.cpp
│   ├── test_profiler.cpp
│   ├── test_random.cpp
│   ├── test_schematic.cpp
│   ├── test_serialization.cpp
│   ├── test_server_shutdown_state.cpp
│   ├── test_serveractiveobjectmgr.cpp
│   ├── test_servermodmanager.cpp
│   ├── test_settings.cpp
│   ├── test_socket.cpp
│   ├── test_threading.cpp
│   ├── test_utilities.cpp
│   ├── test_voxelalgorithms.cpp
│   ├── test_voxelarea.cpp
│   └── test_voxelmanipulator.cpp
├── unsupported_language_list.txt
├── util
│   ├── CMakeLists.txt
│   ├── areastore.cpp
│   ├── areastore.h
│   ├── auth.cpp
│   ├── auth.h
│   ├── base64.cpp
│   ├── base64.h
│   ├── basic_macros.h
│   ├── container.h
│   ├── directiontables.cpp
│   ├── directiontables.h
│   ├── enriched_string.cpp
│   ├── enriched_string.h
│   ├── hex.h
│   ├── ieee_float.cpp
│   ├── ieee_float.h
│   ├── metricsbackend.cpp
│   ├── metricsbackend.h
│   ├── numeric.cpp
│   ├── numeric.h
│   ├── png.cpp
│   ├── png.h
│   ├── pointabilities.cpp
│   ├── pointabilities.h
│   ├── pointedthing.cpp
│   ├── pointedthing.h
│   ├── pointer.h
│   ├── quicktune.cpp
│   ├── quicktune.h
│   ├── quicktune_shortcutter.h
│   ├── serialize.cpp
│   ├── serialize.h
│   ├── sha1.cpp
│   ├── sha1.h
│   ├── sha256.c
│   ├── sha256.h
│   ├── srp.cpp
│   ├── srp.h
│   ├── stream.h
│   ├── strfnd.h
│   ├── string.cpp
│   ├── string.h
│   ├── thread.h
│   ├── timetaker.cpp
│   └── timetaker.h
├── version.cpp
├── version.h
├── voxel.cpp
├── voxel.h
├── voxelalgorithms.cpp
└── voxelalgorithms.h