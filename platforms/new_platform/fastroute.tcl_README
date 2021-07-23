One should use the equivalent file from the sample platform as an example.
The fastroute.tcl file defines the user’s routing preference on this platform.

Using this default is recommended:

set_global_routing_layer_adjustment $::env(MIN_ROUTING_LAYER)-$::env(MAX_ROUTING_LAYER) 0.5

set_routing_layers -signal $::env(MIN_ROUTING_LAYER)-$::env(MAX_ROUTING_LAYER)

global_route -guide_file $::env(RESULTS_DIR)/route.guide -overflow_iterations 100  -verbose 2
