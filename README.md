# Active Filter Design

This repo contains all the filter design files. The software used was LTspice. The aim of the project is to design a 5th order maximally flat filter using: RLC, Gm macro model and Gm manually designed using MOSFETs.

  - # MaxFlat.asc
    RLC filter design.

  - # GmCMaxFlatIdeal.asc
    Filter design Gm macro model available in LTspice.

  - # GmUsingTrans.asc
    Tranconductor designed using MOSFETS with gm = 1mS.
 
  - # GmMaxFlatTrans.asc
    Filter designed using the Gm from the previous file. 
  
  - # my_mos_model.txt
    Model file used for MOSFET.