3d_ls_statistics_experiment
===========================
test steps:</br>
  1\input data is thickness, uint 8  origion short  skeleton,uint 8
  2\if test more than one data ,put them into a folder , then put the path
  in statistics define
  3\evething is ok ,make sure the project is X64
  thickness data is get from the 3d_ls_colon prokectthen compute by an Euclide distance in imageJ,
  if you compute more than one data ,there is a MACRO in my csdn blog where is swfa1 
  origion data is the clean data sets
  skeleton could be compute in by imageJ skeleton plugin

  the result will be the thickness histgram and HU histgram ,then output two txts.
  the result for thickness histgram will not be the exact data ,because if the max thickness is 5 ,then the thickness 1-4 
  will be mimus 2 *thickness5 for more than once.
 but if you don;t do the last step ,it doesn,t matter,because the data is a rate.
