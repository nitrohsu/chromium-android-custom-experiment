cmake_minimum_required(VERSION 3.4.1)

add_library(accessibility.cr SHARED IMPORTED)
set_target_properties(accessibility.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libaccessibility.cr.so)

add_library(animation.cr SHARED IMPORTED)
set_target_properties(animation.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libanimation.cr.so)

add_library(apdu.cr SHARED IMPORTED)
set_target_properties(apdu.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libapdu.cr.so)

add_library(base.cr SHARED IMPORTED)
set_target_properties(base.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libbase.cr.so)

add_library(base_i18n.cr SHARED IMPORTED)
set_target_properties(base_i18n.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libbase_i18n.cr.so)

add_library(bindings.cr SHARED IMPORTED)
set_target_properties(bindings.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libbindings.cr.so)

add_library(bindings_base.cr SHARED IMPORTED)
set_target_properties(bindings_base.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libbindings_base.cr.so)

add_library(blink_android_mojo_bindings_shared.cr SHARED IMPORTED)
set_target_properties(blink_android_mojo_bindings_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libblink_android_mojo_bindings_shared.cr.so)

add_library(blink_common.cr SHARED IMPORTED)
set_target_properties(blink_common.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libblink_common.cr.so)

add_library(blink_controller.cr SHARED IMPORTED)
set_target_properties(blink_controller.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libblink_controller.cr.so)

add_library(blink_core.cr SHARED IMPORTED)
set_target_properties(blink_core.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libblink_core.cr.so)

add_library(blink_core_mojo_bindings_shared.cr SHARED IMPORTED)
set_target_properties(blink_core_mojo_bindings_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libblink_core_mojo_bindings_shared.cr.so)

add_library(blink_embedded_frame_sink_mojo_bindings_shared.cr SHARED IMPORTED)
set_target_properties(blink_embedded_frame_sink_mojo_bindings_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libblink_embedded_frame_sink_mojo_bindings_shared.cr.so)

add_library(blink_modules.cr SHARED IMPORTED)
set_target_properties(blink_modules.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libblink_modules.cr.so)

add_library(blink_mojo_bindings_shared.cr SHARED IMPORTED)
set_target_properties(blink_mojo_bindings_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libblink_mojo_bindings_shared.cr.so)

add_library(blink_platform.cr SHARED IMPORTED)
set_target_properties(blink_platform.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libblink_platform.cr.so)

add_library(bluetooth.cr SHARED IMPORTED)
set_target_properties(bluetooth.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libbluetooth.cr.so)

add_library(boringssl.cr SHARED IMPORTED)
set_target_properties(boringssl.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libboringssl.cr.so)

add_library(c++_shared SHARED IMPORTED)
set_target_properties(c++_shared PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libc++_shared.so)

add_library(captive_portal.cr SHARED IMPORTED)
set_target_properties(captive_portal.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcaptive_portal.cr.so)

add_library(capture_base.cr SHARED IMPORTED)
set_target_properties(capture_base.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcapture_base.cr.so)

add_library(capture_ SHARED IMPORTED)
set_target_properties(capture_ PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcapture_.so)

add_library(catalog_ SHARED IMPORTED)
set_target_properties(catalog_ PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcatalog_.so)

add_library(cbor.cr SHARED IMPORTED)
set_target_properties(cbor.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcbor.cr.so)

add_library(cc.cr SHARED IMPORTED)
set_target_properties(cc.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcc.cr.so)

add_library(cc_animation.cr SHARED IMPORTED)
set_target_properties(cc_animation.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcc_animation.cr.so)

add_library(cc_base.cr SHARED IMPORTED)
set_target_properties(cc_base.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcc_base.cr.so)

add_library(cc_debug.cr SHARED IMPORTED)
set_target_properties(cc_debug.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcc_debug.cr.so)

add_library(cc_mojo_embedder.cr SHARED IMPORTED)
set_target_properties(cc_mojo_embedder.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcc_mojo_embedder.cr.so)

add_library(cc_paint.cr SHARED IMPORTED)
set_target_properties(cc_paint.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcc_paint.cr.so)

add_library(cdm_manager.cr SHARED IMPORTED)
set_target_properties(cdm_manager.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcdm_manager.cr.so)

add_library(chrome.cr SHARED IMPORTED)
set_target_properties(chrome.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libchrome.cr.so)

add_library(chromium_sqlite3.cr SHARED IMPORTED)
set_target_properties(chromium_sqlite3.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libchromium_sqlite3.cr.so)

add_library(client.cr SHARED IMPORTED)
set_target_properties(client.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libclient.cr.so)

add_library(cloud_policy_proto_generated_compile.cr SHARED IMPORTED)
set_target_properties(cloud_policy_proto_generated_compile.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcloud_policy_proto_generated_compile.cr.so)

add_library(codec.cr SHARED IMPORTED)
set_target_properties(codec.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcodec.cr.so)

add_library(color_space.cr SHARED IMPORTED)
set_target_properties(color_space.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcolor_space.cr.so)

add_library(common.cr SHARED IMPORTED)
set_target_properties(common.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcommon.cr.so)

add_library(compositor.cr SHARED IMPORTED)
set_target_properties(compositor.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcompositor.cr.so)

add_library(content.cr SHARED IMPORTED)
set_target_properties(content.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcontent.cr.so)

add_library(content_common_mojo_bindings_shared.cr SHARED IMPORTED)
set_target_properties(content_common_mojo_bindings_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcontent_common_mojo_bindings_shared.cr.so)

add_library(content_public_common_mojo_bindings_shared.cr SHARED IMPORTED)
set_target_properties(content_public_common_mojo_bindings_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcontent_public_common_mojo_bindings_shared.cr.so)

add_library(content_service_cpp.cr SHARED IMPORTED)
set_target_properties(content_service_cpp.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcontent_service_cpp.cr.so)

add_library(content_service_mojom.cr SHARED IMPORTED)
set_target_properties(content_service_mojom.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcontent_service_mojom.cr.so)

add_library(content_service_mojom_shared.cr SHARED IMPORTED)
set_target_properties(content_service_mojom_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcontent_service_mojom_shared.cr.so)

add_library(crash_key.cr SHARED IMPORTED)
set_target_properties(crash_key.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcrash_key.cr.so)

add_library(crcrypto.cr SHARED IMPORTED)
set_target_properties(crcrypto.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libcrcrypto.cr.so)

add_library(device_base.cr SHARED IMPORTED)
set_target_properties(device_base.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdevice_base.cr.so)

add_library(device_event_log.cr SHARED IMPORTED)
set_target_properties(device_event_log.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdevice_event_log.cr.so)

add_library(device_features.cr SHARED IMPORTED)
set_target_properties(device_features.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdevice_features.cr.so)

add_library(device_gamepad.cr SHARED IMPORTED)
set_target_properties(device_gamepad.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdevice_gamepad.cr.so)

add_library(device_vr.cr SHARED IMPORTED)
set_target_properties(device_vr.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdevice_vr.cr.so)

add_library(device_vr_mojo_bindings.cr SHARED IMPORTED)
set_target_properties(device_vr_mojo_bindings.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdevice_vr_mojo_bindings.cr.so)

add_library(device_vr_mojo_bindings_blink.cr SHARED IMPORTED)
set_target_properties(device_vr_mojo_bindings_blink.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdevice_vr_mojo_bindings_blink.cr.so)

add_library(device_vr_mojo_bindings_shared.cr SHARED IMPORTED)
set_target_properties(device_vr_mojo_bindings_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdevice_vr_mojo_bindings_shared.cr.so)

add_library(devices.cr SHARED IMPORTED)
set_target_properties(devices.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdevices.cr.so)

add_library(discardable_memory_client.cr SHARED IMPORTED)
set_target_properties(discardable_memory_client.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdiscardable_memory_client.cr.so)

add_library(discardable_memory_common.cr SHARED IMPORTED)
set_target_properties(discardable_memory_common.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdiscardable_memory_common.cr.so)

add_library(discardable_memory_service.cr SHARED IMPORTED)
set_target_properties(discardable_memory_service.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdiscardable_memory_service.cr.so)

add_library(display.cr SHARED IMPORTED)
set_target_properties(display.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdisplay.cr.so)

add_library(display_types.cr SHARED IMPORTED)
set_target_properties(display_types.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdisplay_types.cr.so)

add_library(display_util.cr SHARED IMPORTED)
set_target_properties(display_util.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdisplay_util.cr.so)

add_library(domain_reliability.cr SHARED IMPORTED)
set_target_properties(domain_reliability.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libdomain_reliability.cr.so)

add_library(embedder.cr SHARED IMPORTED)
set_target_properties(embedder.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libembedder.cr.so)

add_library(embedder_switches.cr SHARED IMPORTED)
set_target_properties(embedder_switches.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libembedder_switches.cr.so)

add_library(events.cr SHARED IMPORTED)
set_target_properties(events.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libevents.cr.so)

add_library(events_base.cr SHARED IMPORTED)
set_target_properties(events_base.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libevents_base.cr.so)

add_library(ffmpeg.cr SHARED IMPORTED)
set_target_properties(ffmpeg.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libffmpeg.cr.so)

add_library(fido.cr SHARED IMPORTED)
set_target_properties(fido.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libfido.cr.so)

add_library(fingerprint.cr SHARED IMPORTED)
set_target_properties(fingerprint.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libfingerprint.cr.so)

add_library(freetype_harfbuzz.cr SHARED IMPORTED)
set_target_properties(freetype_harfbuzz.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libfreetype_harfbuzz.cr.so)

add_library(gamepad_mojom.cr SHARED IMPORTED)
set_target_properties(gamepad_mojom.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgamepad_mojom.cr.so)

add_library(gamepad_mojom_blink.cr SHARED IMPORTED)
set_target_properties(gamepad_mojom_blink.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgamepad_mojom_blink.cr.so)

add_library(gamepad_mojom_shared.cr SHARED IMPORTED)
set_target_properties(gamepad_mojom_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgamepad_mojom_shared.cr.so)

add_library(gamepad_shared_typemap_traits.cr SHARED IMPORTED)
set_target_properties(gamepad_shared_typemap_traits.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgamepad_shared_typemap_traits.cr.so)

add_library(gcm.cr SHARED IMPORTED)
set_target_properties(gcm.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgcm.cr.so)

add_library(geometry.cr SHARED IMPORTED)
set_target_properties(geometry.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgeometry.cr.so)

add_library(geometry_skia.cr SHARED IMPORTED)
set_target_properties(geometry_skia.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgeometry_skia.cr.so)

add_library(gesture_detection.cr SHARED IMPORTED)
set_target_properties(gesture_detection.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgesture_detection.cr.so)

add_library(gfx.cr SHARED IMPORTED)
set_target_properties(gfx.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgfx.cr.so)

add_library(gfx_ipc.cr SHARED IMPORTED)
set_target_properties(gfx_ipc.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgfx_ipc.cr.so)

add_library(gfx_ipc_buffer_types.cr SHARED IMPORTED)
set_target_properties(gfx_ipc_buffer_types.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgfx_ipc_buffer_types.cr.so)

add_library(gfx_ipc_color.cr SHARED IMPORTED)
set_target_properties(gfx_ipc_color.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgfx_ipc_color.cr.so)

add_library(gfx_ipc_geometry.cr SHARED IMPORTED)
set_target_properties(gfx_ipc_geometry.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgfx_ipc_geometry.cr.so)

add_library(gfx_ipc_skia.cr SHARED IMPORTED)
set_target_properties(gfx_ipc_skia.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgfx_ipc_skia.cr.so)

add_library(gfx_switches.cr SHARED IMPORTED)
set_target_properties(gfx_switches.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgfx_switches.cr.so)

add_library(gin.cr SHARED IMPORTED)
set_target_properties(gin.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgin.cr.so)

add_library(gl_in_process_context.cr SHARED IMPORTED)
set_target_properties(gl_in_process_context.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgl_in_process_context.cr.so)

add_library(gl_init.cr SHARED IMPORTED)
set_target_properties(gl_init.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgl_init.cr.so)

add_library(gl_wrapper.cr SHARED IMPORTED)
set_target_properties(gl_wrapper.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgl_wrapper.cr.so)

add_library(gles2.cr SHARED IMPORTED)
set_target_properties(gles2.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgles2.cr.so)

add_library(gles2_implementation.cr SHARED IMPORTED)
set_target_properties(gles2_implementation.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgles2_implementation.cr.so)

add_library(gles2_utils.cr SHARED IMPORTED)
set_target_properties(gles2_utils.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgles2_utils.cr.so)

add_library(gpu.cr SHARED IMPORTED)
set_target_properties(gpu.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgpu.cr.so)

add_library(gpu_ipc_service.cr SHARED IMPORTED)
set_target_properties(gpu_ipc_service.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgpu_ipc_service.cr.so)

add_library(gvr_shim.cr SHARED IMPORTED)
set_target_properties(gvr_shim.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libgvr_shim.cr.so)

add_library(host.cr SHARED IMPORTED)
set_target_properties(host.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libhost.cr.so)

add_library(icui18n.cr SHARED IMPORTED)
set_target_properties(icui18n.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libicui18n.cr.so)

add_library(icuuc.cr SHARED IMPORTED)
set_target_properties(icuuc.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libicuuc.cr.so)

add_library(interfaces_shared.cr SHARED IMPORTED)
set_target_properties(interfaces_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libinterfaces_shared.cr.so)

add_library(ipc.cr SHARED IMPORTED)
set_target_properties(ipc.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libipc.cr.so)

add_library(ipc_mojom.cr SHARED IMPORTED)
set_target_properties(ipc_mojom.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libipc_mojom.cr.so)

add_library(ipc_mojom_shared.cr SHARED IMPORTED)
set_target_properties(ipc_mojom_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libipc_mojom_shared.cr.so)

add_library(keyed_service_content.cr SHARED IMPORTED)
set_target_properties(keyed_service_content.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libkeyed_service_content.cr.so)

add_library(keyed_service_core.cr SHARED IMPORTED)
set_target_properties(keyed_service_core.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libkeyed_service_core.cr.so)

add_library(leveldatabase.cr SHARED IMPORTED)
set_target_properties(leveldatabase.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libleveldatabase.cr.so)

add_library(manager.cr SHARED IMPORTED)
set_target_properties(manager.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmanager.cr.so)

add_library(media.cr SHARED IMPORTED)
set_target_properties(media.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmedia.cr.so)

add_library(media_blink.cr SHARED IMPORTED)
set_target_properties(media_blink.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmedia_blink.cr.so)

add_library(media_devices_mojo_bindings_shared.cr SHARED IMPORTED)
set_target_properties(media_devices_mojo_bindings_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmedia_devices_mojo_bindings_shared.cr.so)

add_library(media_gpu.cr SHARED IMPORTED)
set_target_properties(media_gpu.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmedia_gpu.cr.so)

add_library(media_mojo_services.cr SHARED IMPORTED)
set_target_properties(media_mojo_services.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmedia_mojo_services.cr.so)

add_library(message_center.cr SHARED IMPORTED)
set_target_properties(message_center.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmessage_center.cr.so)

add_library(message_support.cr SHARED IMPORTED)
set_target_properties(message_support.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmessage_support.cr.so)

add_library(metrics_cpp.cr SHARED IMPORTED)
set_target_properties(metrics_cpp.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmetrics_cpp.cr.so)

add_library(midi.cr SHARED IMPORTED)
set_target_properties(midi.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmidi.cr.so)

add_library(mojo_base_ SHARED IMPORTED)
set_target_properties(mojo_base_ PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_base_.so)

add_library(mojo_base_mojom.cr SHARED IMPORTED)
set_target_properties(mojo_base_mojom.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_base_mojom.cr.so)

add_library(mojo_base_mojom_blink.cr SHARED IMPORTED)
set_target_properties(mojo_base_mojom_blink.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_base_mojom_blink.cr.so)

add_library(mojo_base_mojom_shared.cr SHARED IMPORTED)
set_target_properties(mojo_base_mojom_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_base_mojom_shared.cr.so)

add_library(mojo_base_shared_typemap_traits.cr SHARED IMPORTED)
set_target_properties(mojo_base_shared_typemap_traits.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_base_shared_typemap_traits.cr.so)

add_library(mojo_cpp_platform.cr SHARED IMPORTED)
set_target_properties(mojo_cpp_platform.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_cpp_platform.cr.so)

add_library(mojo_edk.cr SHARED IMPORTED)
set_target_properties(mojo_edk.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_edk.cr.so)

add_library(mojo_edk_internal.cr SHARED IMPORTED)
set_target_properties(mojo_edk_internal.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_edk_internal.cr.so)

add_library(mojo_edk_ports.cr SHARED IMPORTED)
set_target_properties(mojo_edk_ports.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_edk_ports.cr.so)

add_library(mojo_mojom_bindings.cr SHARED IMPORTED)
set_target_properties(mojo_mojom_bindings.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_mojom_bindings.cr.so)

add_library(mojo_mojom_bindings_shared.cr SHARED IMPORTED)
set_target_properties(mojo_mojom_bindings_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_mojom_bindings_shared.cr.so)

add_library(mojo_public_system.cr SHARED IMPORTED)
set_target_properties(mojo_public_system.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_public_system.cr.so)

add_library(mojo_public_system_cpp.cr SHARED IMPORTED)
set_target_properties(mojo_public_system_cpp.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojo_public_system_cpp.cr.so)

add_library(mojom_core_shared.cr SHARED IMPORTED)
set_target_properties(mojom_core_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojom_core_shared.cr.so)

add_library(mojom_platform_shared.cr SHARED IMPORTED)
set_target_properties(mojom_platform_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libmojom_platform_shared.cr.so)

add_library(native_theme.cr SHARED IMPORTED)
set_target_properties(native_theme.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libnative_theme.cr.so)

add_library(net.cr SHARED IMPORTED)
set_target_properties(net.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libnet.cr.so)

add_library(net_with_v8.cr SHARED IMPORTED)
set_target_properties(net_with_v8.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libnet_with_v8.cr.so)

add_library(network_cpp.cr SHARED IMPORTED)
set_target_properties(network_cpp.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libnetwork_cpp.cr.so)

add_library(network_cpp_base.cr SHARED IMPORTED)
set_target_properties(network_cpp_base.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libnetwork_cpp_base.cr.so)

add_library(network_service.cr SHARED IMPORTED)
set_target_properties(network_service.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libnetwork_service.cr.so)

add_library(network_session_configurator.cr SHARED IMPORTED)
set_target_properties(network_session_configurator.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libnetwork_session_configurator.cr.so)

add_library(onc.cr SHARED IMPORTED)
set_target_properties(onc.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libonc.cr.so)

add_library(perfetto.cr SHARED IMPORTED)
set_target_properties(perfetto.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libperfetto.cr.so)

add_library(platform.cr SHARED IMPORTED)
set_target_properties(platform.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libplatform.cr.so)

add_library(policy_component.cr SHARED IMPORTED)
set_target_properties(policy_component.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libpolicy_component.cr.so)

add_library(policy_proto.cr SHARED IMPORTED)
set_target_properties(policy_proto.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libpolicy_proto.cr.so)

add_library(prefs.cr SHARED IMPORTED)
set_target_properties(prefs.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libprefs.cr.so)

add_library(printing.cr SHARED IMPORTED)
set_target_properties(printing.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libprinting.cr.so)

add_library(protobuf_lite.cr SHARED IMPORTED)
set_target_properties(protobuf_lite.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libprotobuf_lite.cr.so)

add_library(proxy_config.cr SHARED IMPORTED)
set_target_properties(proxy_config.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libproxy_config.cr.so)

add_library(public.cr SHARED IMPORTED)
set_target_properties(public.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libpublic.cr.so)

add_library(range.cr SHARED IMPORTED)
set_target_properties(range.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/librange.cr.so)

add_library(raster.cr SHARED IMPORTED)
set_target_properties(raster.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libraster.cr.so)

add_library(resource_coordinator_cpp.cr SHARED IMPORTED)
set_target_properties(resource_coordinator_cpp.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libresource_coordinator_cpp.cr.so)

add_library(resource_coordinator_cpp_base.cr SHARED IMPORTED)
set_target_properties(resource_coordinator_cpp_base.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libresource_coordinator_cpp_base.cr.so)

add_library(resource_coordinator_public_mojom.cr SHARED IMPORTED)
set_target_properties(resource_coordinator_public_mojom.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libresource_coordinator_public_mojom.cr.so)

add_library(resource_coordinator_public_mojom_blink.cr SHARED IMPORTED)
set_target_properties(resource_coordinator_public_mojom_blink.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libresource_coordinator_public_mojom_blink.cr.so)

add_library(resource_coordinator_public_mojom_shared.cr SHARED IMPORTED)
set_target_properties(resource_coordinator_public_mojom_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libresource_coordinator_public_mojom_shared.cr.so)

add_library(sandbox.cr SHARED IMPORTED)
set_target_properties(sandbox.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libsandbox.cr.so)

add_library(sandbox_services.cr SHARED IMPORTED)
set_target_properties(sandbox_services.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libsandbox_services.cr.so)

add_library(seccomp_bpf.cr SHARED IMPORTED)
set_target_properties(seccomp_bpf.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libseccomp_bpf.cr.so)

add_library(seccomp_starter_android.cr SHARED IMPORTED)
set_target_properties(seccomp_starter_android.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libseccomp_starter_android.cr.so)

add_library(service.cr SHARED IMPORTED)
set_target_properties(service.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libservice.cr.so)

add_library(service_manager_cpp.cr SHARED IMPORTED)
set_target_properties(service_manager_cpp.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libservice_manager_cpp.cr.so)

add_library(service_manager_cpp_types.cr SHARED IMPORTED)
set_target_properties(service_manager_cpp_types.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libservice_manager_cpp_types.cr.so)

add_library(service_manager_mojom.cr SHARED IMPORTED)
set_target_properties(service_manager_mojom.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libservice_manager_mojom.cr.so)

add_library(service_manager_mojom_blink.cr SHARED IMPORTED)
set_target_properties(service_manager_mojom_blink.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libservice_manager_mojom_blink.cr.so)

add_library(service_manager_mojom_constants.cr SHARED IMPORTED)
set_target_properties(service_manager_mojom_constants.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libservice_manager_mojom_constants.cr.so)

add_library(service_manager_mojom_constants_blink.cr SHARED IMPORTED)
set_target_properties(service_manager_mojom_constants_blink.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libservice_manager_mojom_constants_blink.cr.so)

add_library(service_manager_mojom_constants_shared.cr SHARED IMPORTED)
set_target_properties(service_manager_mojom_constants_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libservice_manager_mojom_constants_shared.cr.so)

add_library(service_manager_mojom_shared.cr SHARED IMPORTED)
set_target_properties(service_manager_mojom_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libservice_manager_mojom_shared.cr.so)

add_library(sessions.cr SHARED IMPORTED)
set_target_properties(sessions.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libsessions.cr.so)

add_library(shared_memory_support.cr SHARED IMPORTED)
set_target_properties(shared_memory_support.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libshared_memory_support.cr.so)

add_library(shell_dialogs.cr SHARED IMPORTED)
set_target_properties(shell_dialogs.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libshell_dialogs.cr.so)

add_library(skia.cr SHARED IMPORTED)
set_target_properties(skia.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libskia.cr.so)

add_library(snapshot.cr SHARED IMPORTED)
set_target_properties(snapshot.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libsnapshot.cr.so)

add_library(sql.cr SHARED IMPORTED)
set_target_properties(sql.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libsql.cr.so)

add_library(startup_tracing.cr SHARED IMPORTED)
set_target_properties(startup_tracing.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libstartup_tracing.cr.so)

add_library(storage_browser.cr SHARED IMPORTED)
set_target_properties(storage_browser.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libstorage_browser.cr.so)

add_library(storage_common.cr SHARED IMPORTED)
set_target_properties(storage_common.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libstorage_common.cr.so)

add_library(surface.cr SHARED IMPORTED)
set_target_properties(surface.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libsurface.cr.so)

add_library(tracing.cr SHARED IMPORTED)
set_target_properties(tracing.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libtracing.cr.so)

add_library(tracing_cpp.cr SHARED IMPORTED)
set_target_properties(tracing_cpp.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libtracing_cpp.cr.so)

add_library(tracing_mojom.cr SHARED IMPORTED)
set_target_properties(tracing_mojom.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libtracing_mojom.cr.so)

add_library(tracing_mojom_shared.cr SHARED IMPORTED)
set_target_properties(tracing_mojom_shared.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libtracing_mojom_shared.cr.so)

add_library(ui_android.cr SHARED IMPORTED)
set_target_properties(ui_android.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libui_android.cr.so)

add_library(ui_base.cr SHARED IMPORTED)
set_target_properties(ui_base.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libui_base.cr.so)

add_library(ui_base_ime.cr SHARED IMPORTED)
set_target_properties(ui_base_ime.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libui_base_ime.cr.so)

add_library(ui_data_pack.cr SHARED IMPORTED)
set_target_properties(ui_data_pack.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libui_data_pack.cr.so)

add_library(ui_devtools.cr SHARED IMPORTED)
set_target_properties(ui_devtools.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libui_devtools.cr.so)

add_library(ui_message_center_cpp.cr SHARED IMPORTED)
set_target_properties(ui_message_center_cpp.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libui_message_center_cpp.cr.so)

add_library(ui_touch_selection.cr SHARED IMPORTED)
set_target_properties(ui_touch_selection.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libui_touch_selection.cr.so)

add_library(url.cr SHARED IMPORTED)
set_target_properties(url.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/liburl.cr.so)

add_library(url_ipc.cr SHARED IMPORTED)
set_target_properties(url_ipc.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/liburl_ipc.cr.so)

add_library(url_matcher.cr SHARED IMPORTED)
set_target_properties(url_matcher.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/liburl_matcher.cr.so)

add_library(user_manager.cr SHARED IMPORTED)
set_target_properties(user_manager.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libuser_manager.cr.so)

add_library(user_prefs.cr SHARED IMPORTED)
set_target_properties(user_prefs.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libuser_prefs.cr.so)

add_library(v8.cr SHARED IMPORTED)
set_target_properties(v8.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libv8.cr.so)

add_library(v8_ SHARED IMPORTED)
set_target_properties(v8_ PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libv8_.so)

add_library(viz_common.cr SHARED IMPORTED)
set_target_properties(viz_common.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libviz_common.cr.so)

add_library(viz_resource_format.cr SHARED IMPORTED)
set_target_properties(viz_resource_format.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libviz_resource_format.cr.so)

add_library(vr_common.cr SHARED IMPORTED)
set_target_properties(vr_common.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libvr_common.cr.so)

add_library(web_dialogs.cr SHARED IMPORTED)
set_target_properties(web_dialogs.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libweb_dialogs.cr.so)

add_library(webdata_common.cr SHARED IMPORTED)
set_target_properties(webdata_common.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libwebdata_common.cr.so)

add_library(wtf.cr SHARED IMPORTED)
set_target_properties(wtf.cr PROPERTIES IMPORTED_LOCATION src/main/jniLibs/${ANDROID_ABI}/libwtf.cr.so)

find_library(log-lib log)

add_library(native-lib SHARED
        src/main/cpp/native-lib.cpp)

target_link_libraries(native-lib ${accessibility.cr} ${animation.cr} ${apdu.cr} ${base.cr} ${base_i18n.cr} ${bindings.cr} ${bindings_base.cr} ${blink_android_mojo_bindings_shared.cr} ${blink_common.cr} ${blink_controller.cr} ${blink_core.cr} ${blink_core_mojo_bindings_shared.cr} ${blink_embedded_frame_sink_mojo_bindings_shared.cr} ${blink_modules.cr} ${blink_mojo_bindings_shared.cr} ${blink_platform.cr} ${bluetooth.cr} ${boringssl.cr} ${c++_shared} ${captive_portal.cr} ${capture_base.cr} ${capture_} ${catalog_} ${cbor.cr} ${cc.cr} ${cc_animation.cr} ${cc_base.cr} ${cc_debug.cr} ${cc_mojo_embedder.cr} ${cc_paint.cr} ${cdm_manager.cr} ${chrome.cr} ${chromium_sqlite3.cr} ${client.cr} ${cloud_policy_proto_generated_compile.cr} ${codec.cr} ${color_space.cr} ${common.cr} ${compositor.cr} ${content.cr} ${content_common_mojo_bindings_shared.cr} ${content_public_common_mojo_bindings_shared.cr} ${content_service_cpp.cr} ${content_service_mojom.cr} ${content_service_mojom_shared.cr} ${crash_key.cr} ${crcrypto.cr} ${device_base.cr} ${device_event_log.cr} ${device_features.cr} ${device_gamepad.cr} ${device_vr.cr} ${device_vr_mojo_bindings.cr} ${device_vr_mojo_bindings_blink.cr} ${device_vr_mojo_bindings_shared.cr} ${devices.cr} ${discardable_memory_client.cr} ${discardable_memory_common.cr} ${discardable_memory_service.cr} ${display.cr} ${display_types.cr} ${display_util.cr} ${domain_reliability.cr} ${embedder.cr} ${embedder_switches.cr} ${events.cr} ${events_base.cr} ${ffmpeg.cr} ${fido.cr} ${fingerprint.cr} ${freetype_harfbuzz.cr} ${gamepad_mojom.cr} ${gamepad_mojom_blink.cr} ${gamepad_mojom_shared.cr} ${gamepad_shared_typemap_traits.cr} ${gcm.cr} ${geometry.cr} ${geometry_skia.cr} ${gesture_detection.cr} ${gfx.cr} ${gfx_ipc.cr} ${gfx_ipc_buffer_types.cr} ${gfx_ipc_color.cr} ${gfx_ipc_geometry.cr} ${gfx_ipc_skia.cr} ${gfx_switches.cr} ${gin.cr} ${gl_in_process_context.cr} ${gl_init.cr} ${gl_wrapper.cr} ${gles2.cr} ${gles2_implementation.cr} ${gles2_utils.cr} ${gpu.cr} ${gpu_ipc_service.cr} ${gvr_shim.cr} ${host.cr} ${icui18n.cr} ${icuuc.cr} ${interfaces_shared.cr} ${ipc.cr} ${ipc_mojom.cr} ${ipc_mojom_shared.cr} ${keyed_service_content.cr} ${keyed_service_core.cr} ${leveldatabase.cr} ${manager.cr} ${media.cr} ${media_blink.cr} ${media_devices_mojo_bindings_shared.cr} ${media_gpu.cr} ${media_mojo_services.cr} ${message_center.cr} ${message_support.cr} ${metrics_cpp.cr} ${midi.cr} ${mojo_base_} ${mojo_base_mojom.cr} ${mojo_base_mojom_blink.cr} ${mojo_base_mojom_shared.cr} ${mojo_base_shared_typemap_traits.cr} ${mojo_cpp_platform.cr} ${mojo_edk.cr} ${mojo_edk_internal.cr} ${mojo_edk_ports.cr} ${mojo_mojom_bindings.cr} ${mojo_mojom_bindings_shared.cr} ${mojo_public_system.cr} ${mojo_public_system_cpp.cr} ${mojom_core_shared.cr} ${mojom_platform_shared.cr} ${native_theme.cr} ${net.cr} ${net_with_v8.cr} ${network_cpp.cr} ${network_cpp_base.cr} ${network_service.cr} ${network_session_configurator.cr} ${onc.cr} ${perfetto.cr} ${platform.cr} ${policy_component.cr} ${policy_proto.cr} ${prefs.cr} ${printing.cr} ${protobuf_lite.cr} ${proxy_config.cr} ${public.cr} ${range.cr} ${raster.cr} ${resource_coordinator_cpp.cr} ${resource_coordinator_cpp_base.cr} ${resource_coordinator_public_mojom.cr} ${resource_coordinator_public_mojom_blink.cr} ${resource_coordinator_public_mojom_shared.cr} ${sandbox.cr} ${sandbox_services.cr} ${seccomp_bpf.cr} ${seccomp_starter_android.cr} ${service.cr} ${service_manager_cpp.cr} ${service_manager_cpp_types.cr} ${service_manager_mojom.cr} ${service_manager_mojom_blink.cr} ${service_manager_mojom_constants.cr} ${service_manager_mojom_constants_blink.cr} ${service_manager_mojom_constants_shared.cr} ${service_manager_mojom_shared.cr} ${sessions.cr} ${shared_memory_support.cr} ${shell_dialogs.cr} ${skia.cr} ${snapshot.cr} ${sql.cr} ${startup_tracing.cr} ${storage_browser.cr} ${storage_common.cr} ${surface.cr} ${tracing.cr} ${tracing_cpp.cr} ${tracing_mojom.cr} ${tracing_mojom_shared.cr} ${ui_android.cr} ${ui_base.cr} ${ui_base_ime.cr} ${ui_data_pack.cr} ${ui_devtools.cr} ${ui_message_center_cpp.cr} ${ui_touch_selection.cr} ${url.cr} ${url_ipc.cr} ${url_matcher.cr} ${user_manager.cr} ${user_prefs.cr} ${v8.cr} ${v8_} ${viz_common.cr} ${viz_resource_format.cr} ${vr_common.cr} ${web_dialogs.cr} ${webdata_common.cr} ${wtf.cr} ${log-lib})