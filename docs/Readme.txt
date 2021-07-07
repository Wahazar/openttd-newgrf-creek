
Creeks (fake rivers as objects)

Usage:
Four variants of river, when placed, automatically join to adjacent tile with fake river objet or real water.
Can be used for making scenario with minor rivers acting as obstacles, while being not navigable by ships.

Parameters:
placement costs can be set as -
Low/High/Only Scenario Editor.
Removal costs also can be set as -
Low/High/Only Scenario Editor.

If removal is possible in Scenario Editor only, placement is also possible in Scenario Editor, regardless of first option.
Thus possible settings combinations are:
a) 
placement: Lo/Hi
removal: Lo/Hi
b)
placement: Editor Only
removal: Lo/Hi
c)
placement: Editor Only
removal: Editor Only

Compilation:
gcc -E -x c CreekObjectsMC.pnml -o CreekObjectsMC.nml
nmlc CreekObjectsMC.nml
then copy nmlc CreekObjectsMC.grf to openttd/newgrf folder.

Authors:

Credits goes to GarryG, creator of creeks graphics.

NML code: GarryG and McZapkie

