# DF_01
there are two main errors till now
 
1- the object is shown very small, it needs to be scaled up to 100 to be seen
this can be done from: inspector >> nodes >> comau (the object to be scaled)
(we tried to change the UnitOfMeasureScale to 0.01 & 1 & 100 but it didn't fix the issue)

2- links 3 & 5 rotations in the urdf file are not coherent with the required look of the model.
we tried to use different GLB files with different configurations and the same error happened.
((temporarily, we tried to fix the rotations of link_3 & link_5 manually in another Json file Output_01_y_14.json ))

links to try the json files

the original json
http://ec2-54-174-51-194.compute-1.amazonaws.com/vebjs/?inputscene=https://raw.githubusercontent.com/AsemShabayek/DF_01/main/Output_01_y_14.json&repoMod3d

the manually modified json
http://ec2-54-174-51-194.compute-1.amazonaws.com/vebjs/?inputscene=https://raw.githubusercontent.com/AsemShabayek/DF_01/main/Output_01_y_14.json&repoMod3d


