 * Install KLayout, or have KLayout already installed
 * Open KLayout
 * Install the tf_import package
 * Inside KLayout, go to Tools
 * Manage Packages
 * Install New Packages
 * Select tf_import
 * Re-start KLayout
 * File -> Import some LEF. Any file is fine, you just get an error message without one.
 * File -> Import Cadence tech file
 * You have to select a tech file (found in the PDK, usually inside the Virtuoso folder)
 * You have to select a .drf file afterwards (found in the PDK’s Virtuoso folder).
 * Finally you have to select a layermap file (found in the Virtuoso folder)
 * File -> Save Layer Properties
