if(TARGET nsx_sdk_ambiqsuite_r5)
    return()
endif()

add_library(nsx_sdk_ambiqsuite_r5 INTERFACE)
set_target_properties(nsx_sdk_ambiqsuite_r5 PROPERTIES EXPORT_NAME sdk_ambiqsuite_r5)
add_library(nsx::sdk_ambiqsuite_r5 ALIAS nsx_sdk_ambiqsuite_r5)
add_library(nsx::ambiqsuite_r5 ALIAS nsx_sdk_ambiqsuite_r5)

target_compile_definitions(nsx_sdk_ambiqsuite_r5 INTERFACE
    NSX_SDK_AMBIQSUITE_R5
)

install(TARGETS
    nsx_sdk_ambiqsuite_r5
    EXPORT nsxTargets
)
