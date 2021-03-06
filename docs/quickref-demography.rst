
+------------------------------------------+-------------------------------------------+
| :class:`.Demography`                     |  Description of a demographic model       |
+------------------------------------------+-------------------------------------------+
| **Constructing simple models**                                                       |
+------------------------------------------+-------------------------------------------+
| :meth:`.Demography.isolated_model`       | A model of isolated populations           |
+------------------------------------------+-------------------------------------------+
| :meth:`.Demography.island_model`         | An interconnected web of populations      |
+------------------------------------------+-------------------------------------------+
| :meth:`.Demography.stepping_stone_model` | Simple spatial model                      |
+------------------------------------------+-------------------------------------------+
| **Constructing models from existing definitions**                                    |
+------------------------------------------+-------------------------------------------+
| :meth:`.Demography.from_species_tree`    | Parse a newick species tree               |
+------------------------------------------+-------------------------------------------+
| :meth:`.Demography.from_starbeast`       | Parse StarBeast output                    |
+------------------------------------------+-------------------------------------------+
| :meth:`.Demography.from_old_style`       | Demography from msprime 0.x inputs        |
+------------------------------------------+-------------------------------------------+
| **Debugging**                                                                        |
+------------------------------------------+-------------------------------------------+
| :meth:`.Demography.debug`                |  Get a Debugger for a demography          |
+------------------------------------------+-------------------------------------------+
| :class:`.DemographyDebugger`             |  Debugger for demographic models          |
+------------------------------------------+-------------------------------------------+
