# DF_01
there are two main errors till now
 
1- the object is shown very small, it needs to be scaled up to 100 to be seen
this can be done from: inspector >> nodes >> comau (the object to be scaled)
(we tried to change the UnitOfMeasureScale to 0.01 & 1 & 100 but it didn't fix the issue)

2- links 3 & 5 rotations in the urdf file are not coherent with the required look of the model.
we tried to use different GLB files with different configurations and the same error happened.
((temporarily, we tried to fix the rotations of link_3 & link_5 manually in another Json file))
