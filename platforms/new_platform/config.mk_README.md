In the config.mk file there are several environment variables that need to be
changed to fit the specific platform that is being used. Specifically the paths
for the TECH_LEF, SC_LEF, LIB_FILES, GDS_FILES, FILL_CELLS, HOLD_BEF_CELLS, and
the TIEHI and TIELO cells need to be set. There are more lines in the config
file that need the names and paths changed so it is recommended that it is read
through completely and changed where needed.  There are also options inside
that can be changed to fit the requirements of the technology such as
MAX_WIRE_LENGTH, PLACE_DENSITY, etc.
