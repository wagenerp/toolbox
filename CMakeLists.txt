cmake_minimum_required (VERSION 3.21)
project (toolbox)



install(
  FILES bin/µconf bin/macroprocessor bin/q-run
  DESTINATION bin
  PERMISSIONS OWNER_READ OWNER_WRITE OWNER_EXECUTE GROUP_READ GROUP_WRITE GROUP_EXECUTE WORLD_READ WORLD_EXECUTE
)