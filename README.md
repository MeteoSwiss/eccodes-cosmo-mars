# eccodes-cosmo-mars
mars definitions for cosmo operational data at MeteoSwiss

Note:
* Concepts in the directory `definitions/grib2/` are *global* concepts, i.e., *replace* the concepts of eccodes, or do not have an effect depending on the order the resources are specified in `GRIB_DEFINITION_PATH` / `ECCODES_DEFINITION_PATH`.
* Concepts in the directory `definitions/grib2/localConcepts/<centre>/` are *additive* to the global concepts (from eccodes or `definitions/grib2/`), and only apply for the respective `<centre>`.
