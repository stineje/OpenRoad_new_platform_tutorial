The lef folder contains LEF descriptions of the standard cells used for a platform.
This can be taken as-is from the original platform, with one note to be made.

OpenROAD expects two separate LEF files:
 - A tech-LEF, .tlef, file that only contains the LEF technology rules
 - A separate LEF file containing LEF descriptions for all standard cells

LEF information must be provided in this format to ensure smooth operation of the tool.

Many PDKs already provide LEFs split in this manner. Should your target PDK not, simply split the LEF manually. Make sure that both resulting LEFs have a header.

Refer to the sample platform as an example of what goes in this folder.
