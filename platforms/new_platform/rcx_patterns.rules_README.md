Navigate to OpenROAD/src/rcx/calibration/script/user_env.tcl and set the
correct paths for the TECH_LEF, MACRO_LEF, and golden_spef.

Once complete, run the calibration script in the calibration folder to
generate the rules file.

OpenROAD MUST be built before running the script since a soft-link will be
created to generate the file.
