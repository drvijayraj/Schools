
## Play with the ESS MCPL-beamport description:
* Pick a folder on the cluster to work in
* Symlink one or more of MCPL files from either (on the reserved compute nodes!)
  * ```/tmp/MCPL/1e6/``` ~ 30 Mb each
  * ```/tmp/MCPL/1e7/``` ~ 300 Mb each
* Find the instrument ```ESS_butterfly_Guide_curved_test.instr ``` via Files, New From Template..., ESS in mcgui
* Look in the code for rotations + translations taking you from the MCNP / TCS to the McStas / beamline coordinate system
* Run the instrument for one or more combinations of Sector= and beamline=, both in ”simulation” and “trace” modes.

