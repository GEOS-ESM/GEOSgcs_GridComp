esma_set_this()

esma_add_library(${this}
   SRCS GEOS_GcsGridComp.F90
   DEPENDENCIES MAPL_Base GEOSgcm_GridComp GEOSana_GridComp
   INCLUDES ${INC_ESMF}
   )

