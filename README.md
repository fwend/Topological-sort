# Topological sort

Perform a topological sort

(from task description Rosetta Code)

Given a mapping between items, and items they depend on, a topological sort orders items so that no item precedes an item it depends upon.

```LIBRARY          LIBRARY DEPENDENCIES
=======          ====================
des_system_lib   std synopsys std_cell_lib des_system_lib dw02 dw01 ramlib ieee
dw01             ieee dw01 dware gtech
dw02             ieee dw02 dware
dw03             std synopsys dware dw03 dw02 dw01 ieee gtech
dw04             dw04 ieee dw01 dware gtech
dw05             dw05 ieee dware
dw06             dw06 ieee dware
dw07             ieee dware
dware            ieee dware
gtech            ieee gtech
ramlib           std ieee
std_cell_lib     ieee std_cell_lib
synopsys
```

Output:

Topologically sorted order:<br> 
[std,  ieee,  dware,  dw02,  dw05, dw06,  dw07,  gtech,  dw01,  dw04,  ramlib,  std_cell_lib,  synopsys,  des_system_lib,  dw03]
