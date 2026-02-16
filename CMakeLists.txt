#####
# 'ReferenceDeployment' Deployment:
#
# This registers the 'ReferenceDeployment' deployment to the build system.
# Custom components that have not been added at the project-level should be added to
# the list below.
#
#####

###
# Topology and Components
###
add_library(sparkfun_pico_sfe_psram_zephyr STATIC "${CMAKE_CURRENT_LIST_DIR}/sparkfun_pico/sfe_psram_zephyr.cpp")
